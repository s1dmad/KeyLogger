Key loggers are activity-monitoring software programs that give hackers access to your data. The software is installed on your computer and records everything you type. Then it sends this log file to a server, where cybercriminals wait to use all this sensitive information.

### This key logger can not only detect & record your keystrokes but can also:

- Takes screenshot at a particular interval of time

- Records audio

- Record your System’s information & IP Address

- Sends the data to the remote server using [Twilio](https://www.twilio.com/)

- Keep track of your clipboard information

## Technologies on which it is built:
```
1. Python
2. Socket
3. Platform
4. Win32
5. Pynput
6. Scipy
7. Sound-Device
8. Cryptography
9. Twilio
```
## Why Our Keylogger?

- It will broaden the way of thinking of researchers about how we can innovate the key loggers.
- It will help identify the loopholes in the current anti key loggers software.
- Multi software hack: pyKeylogger is packed with many modules to make it more advance than traditional keyloggers.

#### Capable of deleting all the records after sending them to the remote server.


#### Encrypts the data & generates a new key (Asymmetric Key Encryption) that only the person at the remote server can decrypt.


#### Using Twilio for transferring the data to a remote server!


## How to use?
After cloning & installing all the dependencies, run
```
>>> python GenerateKey.py
```
It will generate the encryption key. Paste this key into `DecryptFile.py` & `Keylogger.py`. Then run,
```
>>> python Keylogger.py
```

