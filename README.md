**1)**
Make sure NetworkManager is installed

**2)**
add 
```bash
export PYTHONPATH="${PYTHONPATH}:/home/user/Documents/rasp" #"rasp" is the module containing python-function for sending the mail
export EMAIL_USR="email@hotmail.com"
export EMAIL_PWD="strong_password" 
```

to `~/.profile`

**3)**
go to `/etc/NetworkManager/dispatcher` and add the `send_mail` file here.
