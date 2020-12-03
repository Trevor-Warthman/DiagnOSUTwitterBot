# DiagnOSUTwitterBot
Converting DiagnOSU into a bot that generates messages from people on twitter

How to use our program:
- tweet @DiagnOSU
- run the python file
- recieve reply from dr.brutus

NOTES:
If IBM WAtson isn't working, make your own IBM Cloud account and put the moonshot json file in it, and replace Adam's credentials in the python file with your own (skill-id, URL, etc)
If an error is triggered, it is likely due to the presence of a tab in the tweet or due to dr.brutus already having replied to that tweet. Fix: require tweets to not contain tab or newline, and new tweets are run first so create new tweets.

Input: Live Tweets when someone hashtags or @'s our bot

Output: Twitter reply 

INFO: JSON file on git. Put this in your ibm cloud account. Python file to run on google drive colab

Diagnosu twitter:
user: @DiagnOSU
password: ask trevor (440-787-5778)

DiagnOSU drive:
https://drive.google.com/drive/folders/1F5GjTh-D3fAOcBPae1Q8_VQtCETuoE-r?ths=true

Features to Add: 
Make DiagnOSU only reply to tweets that he hasn't replied to before using the Twitter API
Allow tweets to contain a tab or new line.
