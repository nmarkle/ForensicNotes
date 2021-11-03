# Windows Logon Events

## 2 - Interactive
    * A user logged on to this computer
## 3 - Network
    * A user or computer logged on to this computer from the network
## 4 - Batch
    * Batch logon type is used by batch servers where processes may be executing on behalf of a user without their direct intervention
## 5 - Service
    * A service was started by the Serivce Control Manager
## 7 - Unlock
    * This workstation was unlocked. Indicative of a manual interaction with the host.
## 8 - NetworkCleartext
    * A user logged on to this computer from the network. The user's password was passed to the authentication package in its unhashed form. The built-in authentication packages all hash credentials before sending them across the network. The credentials do not traverse the network in plaintext.
## 9 - NewCredentials
    * A caller cloned its current token and specified new credentials for outbound connections. The new logon session has the same local identity, but uses different credentials for other network connections.
## 10 - RemoteInteraction
    * A user logged on to this computer remotely using Terminal Services or Remote Desktop
## 11 - CachedInteractive
    * A user logged on to this computer with network credentials that were stored locally on the computer. The domain controller was not contacted to verify the credentials.