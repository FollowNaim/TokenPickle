# How To Generate Token Pickle With Android Easily After Google Auth2.0 New policy update.
### 1. Install Termux [F-Droid](https://f-droid.org/en/packages/com.termux/)
### 2. Open Termux and just copy paste all the commands that described below, Make sure you have internet connection.
```
apt update && apt upgrade && pkg i git && pkg i python3 && pkg update python && pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib && pip install --upgrade pip
```
### 3.
```
git clone https://github.com/TheNaimBro/TokenPickle
```
### 4. make sure Credentials.json file present in your storage/download folder. if not then just move credentials.json file into the download folder.
### 5. 
```
cd /sdcard/download
```
### 6. 
```
cp -r credentials.json /data/data/com.termux/files/home/TokenPickle
```
### 7. Just exit from termux and reopen it.
### 8.
```
cd TokenPickle
```
### 9. 
```
python3 GenerateTokenPickle.py
```
### 10. You'll find a url https://drive.google.com/..... like this. just copy this url and paste on browser and login into your google account. that's it. you don't have to copy code or anything else.
### 11. 
```
cp -r token.pickle /sdcard/download
```
### 12. Boom 💥! 
goto your sdcard/download folder you'll find token.pickle there.

We're Done.
# Enjoy And don't forget to star this repo 🙂

# Credits...
[`Anasty17`](https://github.com/anasty17)
