# Messenger-Data-Analysis

This project is based on Facebook/Meta available personal data for Messenger conversations.
Here I collected, clean-up and plotted some statistics for a group chat with me and some friends. He had more than 400,000 messages over more than 5 years.

This simple analysis focus on the time statistics for each participant: how much message each participant sends for a given period of the day, which days of the week they are more active and how that changed with years.

I also considered the 'react' dynamics (emojis that one can react to messagens among ourselves): who reacted more, who gets more reacts and how the participants reacted among themselves.

### Language:
Python

### Libraries used:
os, pandas, numpy, matplotlib, json and datetime

### Input data:
Facebook/Meta conversation as JSON files downloaded from [here](https://www.facebook.com/help/212802592074644/?helpref=uf_share)

### Results:
Can be found in the folder results in this reposity. Plots generated using the notebook also in this repository.

### To-Do list:
1) Fix the emoji encoding to plot the results using matplotlib

### Key points:
1) We are more active after 10am with message peaking around 8-9pm

2) Our messages are consistent for all days of week with more chat during 2020 (pandemic)

3) The overall reaction probability is around 4-12%

4) The most used emoji for react, by far, is 😆
