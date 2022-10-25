## [Exercise]() 7

### Task:

* Create a bash script to run at every hour, saving system memory (RAM) usage to a specified file and at midnight it sends the content of the file to a specified email address, then starts over for the new day.

### Instruction:

- [ ] Submit the content of your script, cronjob and a sample of the email sent, all in the folder for this exercise.  


## Solution  

I named my script *'script.sh'*. Below is the content of the bash script.  


![Bash_Script](https://user-images.githubusercontent.com/67663655/197780370-99a886a0-2a4a-4d86-b895-5004371c5cd8.png)  

Here is the Cronjob i scheduled for the script.  


![crontab -e (to schedule bash script execution)](https://user-images.githubusercontent.com/67663655/197780546-ff21048d-70e3-49c8-a581-d7d36de5e0bf.png)  

Then i got this mail.  

![bash script mail](https://user-images.githubusercontent.com/67663655/197781109-926803b3-5be7-4341-b65e-78d3b3ff1882.png)  

Here is the content of the log file created by my bash script and sent to my e-mail address.  

![log file content](https://user-images.githubusercontent.com/67663655/197781298-52b1d772-1e68-4f58-b1cb-6955622f151d.png)


