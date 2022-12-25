## Twitter Profanity 

To download the files use git to clone the repository<br>
git clone < repository link > <br>
<br>
slurs.txt: A .txt file for collection of all the slurs seperated by 'enter' <br>
tweets.txt: A .txt file for collection of all the tweets seperated by 'enter' <br>
Twitter.ipynb: Python file which contains the pipeline for calculating the degree of profanity<br>
Run the file to calculate the degree of profanity for each sentence. <br><br>
Assumptions:<br>
1. All the data for slurs and tweets are provided in a .txt file<br>
2. The degree of profanity is calculated on the slurs provided in the file only, if any deviations from the slurs<br>
   are present in the text it will not be detected. 
3. The degree of profanity is calculated as (slurs detected in sentence)/(total words in sentence)*100 %<br>
