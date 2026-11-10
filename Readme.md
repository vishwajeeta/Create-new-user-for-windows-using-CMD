You can create a new local Windows 11 user directly using CMD.



\### 1. Create a new user



For example, create an account named `Vishwajeet`:



```

net user Vishwajeet \* /add

```



Windows will prompt you to enter and confirm a password (it won't display while typing).



\### 2. Give administrator privileges



```

net localgroup Administrators Vishwajeet /add

```



\### 3. Verify the account



```

net user Vishwajeet

```



\### 4. Sign in



Restart your computer:



```

shutdown /r /t 0

```



At the login screen, select Vishwajeet and enter the password you created.
