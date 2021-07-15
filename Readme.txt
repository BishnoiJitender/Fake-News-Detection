Follow the steps given below to use this Fake News Detection Model:
Step1:Download the zip file and extract it at desktop inside a folder for e.g. "Fake News Detection".
Step2:Now go to your "Anaconda Prompt 3" and change the directory where you extracted the file.
for e.g. if you extracted it at desktop then I will give the following path after "cd" command like:
                          cd C:\Users\dell\Desktop\Fake News Detection
Step3:After changing the directory, run the app.py file in Anaconda prompt3 by typing in the command:
                          app.py
Step4:After typing in the command, it will take a while and will then generate a URL for your personal use which will look like this:
                         http://127.0.0.1:5000/
Copy this URL and paste it inside your browser, and it will take you to the website/UI which we created to take URL of news articles from the user.
Step5:Now search any news article on Google(preferably related to US news and Election) and copy its URL.
Step6:Now go to the tab where we opened the website using Step4 and paste the URL there and click on the button "predict".
Step7:Now the model will predict the news article as "Real" or "Fake".

Note:This model is under development and does not guarantee 100% accurate results. If you have any suggestion or recommendation for this Project, please contact me on "jitenderishnoi37@gmail.com" to further discuss it with me.
No permissions are required to use this project for personal use or to make any changes in it until and unless it is being used for commercial purpose.

The dataset used in this project to train the model can be downloaded using the given link:
                            https://www.kaggle.com/hassanamin/textdb3
