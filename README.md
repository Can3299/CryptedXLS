# CryptedXLS

 CryptedXLS is a program that can perform basic and advanced encryption and decryption. CryptedXLS uses a 256-bit 2-layer encryption logic. In addition to 256-bit encryption, it makes passwords even stronger by using KDF and salt. Thanks to KDF, CryptedXLS allows more secure passwords to be created than simple passwords, so the user's data is encrypted with additional security methods. 

 CryptedXLS has a wide range of downloads and supports most commonly used operating systems. CryptedXLS also supports most processor architectures such as Arm64 X86_64 and IA-64. It can also produce special versions for you if your device does not support CryptedXLS.

 
## What News? 1.0.0
- **Added two-layer encryption-decryption**
- **Basic interface added**
- **User encryption added**


> ### How does KDA work?
>  KDA recreates the same password as a different password, thus  converting a simple password into a stronger one. And it does this  without requiring you to memorize a new password. Below, as an example, the same two passwords have been re-encrypted with KDA.
> ```
> KDA: MyPassword = b74cde1a6c8d6743e1e9f47c2e4d5d75e2fef9b1b6e78b7e2f5a8d57e90a1234
> ```
> ```
> KDA: MyPassword = c58d1e7f43b5a9b9c1d6e2f3e4f7d8e2b9c0a1d2e3f4g5h6i7j8k9l0m1n2o3p
> ```


> ### What is 256-bit Encryption?
>  This algorithm is one of the most secure and modern encryption algorithms that can be preferred after 128-bit and 192-bit encryption algorithms. 256-bit encryption makes all data much more secure in case they can break 128-bit encryption.
> 
>  The higher the bit rate in encryption, the stronger and more unpredictable the encryption will be. For example, the probability of repeating some characters in 128-bit encryption is very low in 256-bit encryption.
> ```
> 128-bit: Hello World = fOOQBTkM1wZ7htaaQRGJDw==
> ```
> ```
> 192-bit: Hello World = s6iZhTsAVLjTeumxYR7Q6A==
> ```
> ```
> 256-bit: Hello World = +yOl56UaaNo/FvD0Wh1J0w==
> ```


## Installation Guide
### Windows (X86_64/Arm64/IA-64)

### Mac OS(X86_64/Arm64)

### Linux (X86_64/Arm64)

### Android (X86_64/Arm64)

 Android needs an additional application to run bash files as it cannot run bash files independently. The recommended application to run CryptedXLS on Android is Termux. To run CryptedXLS, you need to download it from [the official github page of Termux](https://github.com/termux/termux-app). If you are running Termux for the first time, it is recommended to update Termux. To run the bash file of CryptedXLS, Termux needs to access your device's storage, this is because it will run the bash file and give you an output accordingly.

> #### Update Termux
> To update Termux, simply type these codes into Termux and press **`enter`**. Also, if it asks you a question, it is recommended that you put a yes (**`y`**) sign and press **`enter`**.
> ```
> pkg update
> ```
> ```
> pkg upgrade
> ```

> #### Storage Permission
> To give storage permission to Termux, just type these codes and **`press`** enter. After pressing enter, a screen asking for permission from the Android system appears and you should click on the **`allow`** button on this screen.
> ```
> termux-setup-storage
> ```

> #### Find The File That Suits You
> Before running the file in Termux, you need to find which file you will download. To do this, you can enter the following command in Termux.
> ```
> uname -m
> ```
> After you type this command in Termux and press **`enter`**, it will give you some output. According to this output, which files you will download are stated below*.
> 
> **X86_64** = CryptedXLS_Linux_X86_64_*version*
> 
> **aarch64** = CryptedXLS_Linux_Arm64_*version*
> 
> *If the output you get when you type the command is not below, please let us know and we will prepare a suitable file for you.

 After finding the file you need to download, you need to transfer CryptedXLS to Termux so that the file can be run more easily. Assuming that the default download folder is "downloads" to transfer CryptedXLS to Termux, you can transfer CryptedXLS to Termux by entering the following commands.
> ```
> cd storage/
> ```
> These commands allow you to enter your home directory. For example, you can access your downloads folder and documents folder within this directory.
