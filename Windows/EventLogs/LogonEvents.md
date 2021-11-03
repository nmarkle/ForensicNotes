# Windows Logon Events

## 4624 - A user successfully logged on to a computer.
```
    * Will contain the following:
        * User account logged into
        * Depending on the connection:
            * Where the user logged into the account from
    * Useful for determining the source of the activity to provide additional context as to how the activity occurred
```

## 4625 - Logon failure.
```
    * Will contain the following:
        * User account attempted to be logged into
    * Useful for determining potential targets of initial compromise and lateral movement
```

## 4634 - The logoff process was completed for a user.
```
    * The user account finished logging off the host
```

## 4647 - A user initiated the logoff process.
```
    * The user account started the logoff process
```

## 20001 - New hardware is connected to your computer
```
    * Types of hardware events:
        * 0 - Installation Successful
        * 2 - File Not Found
```