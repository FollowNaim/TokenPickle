# How To Generate Token Pickle With Android Easily After Google Auth2.0 New policy update. Without any kind of error.

### 1. Install Termux [F-Droid](https://f-droid.org/en/packages/com.termux/)

### 2. Open Termux and just copy paste all the commands that described below, Make sure you have internet connection. if you see Y/n then Type y.

```
apt update && apt upgrade -y && apt install git python3 -y && apt upgrade python3 -y && pkg install python-cryptography && pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib
```

### 3.

```
apt update && apt upgrade
```

### 4.

```
git clone https://github.com/FollowNaim/TokenPickle
```

### 5. make sure Credentials.json file present in your storage folder not in Sd card. if not then just move credentials.json file into the sdcard. Not in any folder.

### 6. you have to give storage permission to termux. for that use this command.

```
termux-setup-storage
```

### 7.

```
cd /sdcard
```

### 8.

```
cp -r credentials.json /data/data/com.termux/files/home/TokenPickle
```

### 9.
```
cd
```

### 10.

```
cd TokenPickle
```

### 11.

```
python3 GenerateTokenPickle.py
```

### 12. You'll find a url https://accounts.google.com/o/oauth2/=offline like this. just copy this url and paste on browser and login into your google account. that's it. you'll see 'The authentication flow has completed. You may close this window' this massage. then you're done.

### 13.

```
cp -r token.pickle /sdcard
```

### 14. Boom 💥!

goto your sdcard (phone memory) you'll find token.pickle there.

We're Done.

# Enjoy And don't forget to star this repo 🙂

# Credits...

[`Anasty17`](https://github.com/anasty17)
