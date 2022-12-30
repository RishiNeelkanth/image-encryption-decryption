![Untitled design (44)](https://user-images.githubusercontent.com/71087332/210039174-c3ef8137-ce35-4039-8f2d-ed8e0550a89d.png)


# Image encryption and decryption using DES Algorithm

Project Description:

In this project we have attempted to use core JAVA to implement encryption and decryption of image using DES Algorithm.

The code is pretty simple and makes use of cipher class already inbuilt in JAVA for implementing the encryption.

We have also used basic file handling to write and read files from our local directory.

Overall it is a good beginner’s project for people learning JAVA or experts/individuals who just want to learn how to encrypt/decrypt images in their own projects


## Installation

You should have java development kit installed on your system.
Along with a ide such as vscode or eclipse. 
    
## Algorithm Used

Data encryption standard (DES) has been found vulnerable against very 
powerful attacks and therefore, the popularity of DES has been found slightly on 
the decline.
DES is a block cipher and encrypts data in blocks of size of 64 bits each, which 
means 64 bits of plain text goes as the input to DES, which produces 64 bits 
of ciphertext. The same algorithm and key are used for encryption and decryption,
with minor differences.

## Java Libraries

import java.io.File;

import java.io.FileInputStream;

import java.io.FileOutputStream;

import java.security.InvalidKeyException;

import java.security.Key;

import javax.crypto.KeyGenerator;

import javax.crypto.NoSuchPaddingException;

import java.security.NoSuchAlgorithmException;

import javax.crypto.Cipher;  

import javax.crypto.CipherInputStream;

## Deployment

We will complete the java code using aur algorithm and java libraries
and after the code is done we will save the file with extension .java

And then using our command line prompt we will execute the java code.


## Screenshots

Before Code Execution: 



![image](https://user-images.githubusercontent.com/71087332/210038058-6221160d-20fe-4d71-b6fd-2f6fd3c2bd4e.png) 


After Code Execution:



![image](https://user-images.githubusercontent.com/71087332/210038151-90da1e45-2879-459e-833b-6215b6814368.png)



## Conclusion

We have successfully created a image encryption and decryption project where we are encrypting a image and then decrypting it.We are using DES algorithm i.e. Data 
Encryption standard algorithm to encrypt the image and then decrypt it back to the 
original image. 

