# video : pinterest.mp4
# run command: npm start or nodemon


/ - login and register page
/register
/login
/profile - profile page with boards
/feed - feed page with all different pins
/save/:pinid - save karege pin ko kisi board mein
/delete/:pinid - delete karege pin ko kisi board se
/logout
/edit
/upload

---

npm i mongoose passport-local passport-local-mongoose express-session


# error ( port already in use {port_number})

1.  1.  find PID of running port => netstat -ano | findstr :3000 (in gitbash)
    2.  check PID i.e number in front of word LISTENING
    3.  close it ( write this ans in terminal powershell, not in gitbash)
        ans => taskkill /PID 15824 /F
    4.  example
        ~/Desktop/pinterest (master) $ netstat -ano | findstr :3000
        TCP 0.0.0.0:3000 0.0.0.0:0 LISTENING 15824
        TCP [::]:3000 [::]:0 LISTENING 15824
        TCP [::1]:62585 [::1]:3000 TIME_WAIT 0

# run project

ans=> npm start or nodemon
