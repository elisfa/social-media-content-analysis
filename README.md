# social-media-content-analysis
What are the best performing words on our social media copy?
The script was originally created for an analysis with purpose to discover if there are magic keywords that make our content perform better. 
For the purpose of this we used as data an excel export from Social Bakers, but Twitter API data can be used as well. 

The final result is a csv file with 5 columns:
  1. index
  2. word/phrase
  3. Frequency of the word on our copies
  4. Likes
  5. Avg likes per frequency

The likes are being calculated as a sum of likes of a copy that contains the word/phrase raised.
