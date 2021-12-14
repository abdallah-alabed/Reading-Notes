# Configuring Django Settings

**Issues while managing django**:
1. Different environments : Each environment can have its own specific settings.
2. Sensitive data: Secret Key, JWT and other api keys!
3. Sharing settings between team members: a developer may add a third-party app or some API integration and fail to add specific settings.
4. Django settings are a Python code:instead of key-value pairs, settings.py can have a very tricky logic.

**How to Approach It**:
1. settings_local.py

  |Pros | Cons| 
  |-----|-----| 
  |Secrets not in VCS.| you can lose some of your Django environment settings.|
  |-| can have some non-obvious logic.|

2. Separate settings file for each environment

  |Pros | Cons| 
  |-----|-----| 
  |All environments are in VCS.| You need to find a way to handle secret passwords and tokens.|
  |It’s easy to share settings between developers.| “Inheritance” of settings can be hard to trace and maintain.|
  
3. Environment variables

  |Pros | Cons| 
  |-----|-----| 
  |Configuration is separated from code.| You need to handle sharing default config between developers.|
  |No inheritance in settings, and cleaner and more consistent code.|-|
  |Environment parity – you have the same code for all environments.|-|
  
#### So We Have To Use django-environ!

## 12 Factors
1. Codebase
2. Dependencies
3. Config
4. Backing services
5. Build, release, run
6. Processes
7. Port binding
8. Concurrency
9. Disposability
10. Dev/prod parity
11. Logs
12. Admin processes


## SSH 
Secure Shell, a remote administration protocol that allows users to control and modify their remote servers over the Internet. 

### How Does SSH Works?
1. utilize a client (PUTTY)
2. command consists on 3 parts ( ssh {user}@{host} )
3. Encryption
4. authenticating the user: his/her credentials

### Encryption Techniques
1. Symmetric Encryption:  a secret key is used for both encryption and decryption of a message by both the client and the host. Effectively, any one possessing the key can decrypt the message being transferred.
2. Asymmetric Encryption: asymmetrical encryption uses two separate keys for encryption and decryption. These two keys are known as the public key and the private key. Together, both these keys form a public-private key pair.
3. Hashing: They generate a unique value of a fixed length for each input that shows no clear trend which can exploited. This makes them practically impossible to reverse.


