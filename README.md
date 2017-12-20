# HideThis Encryption (DLL File)
This repository contains a dll file which can be used to encrypt and decrypt data.
This is a .Net C# dll which can be referenced into any .net project and be used to encrypt or decrypt data.
The namespace HideThis contains Hider class
Functions:
  1. Constructor:
      You need to pass a string password which is predefined by me. Mail me at adarsh.pradyut@gmail.com to get the password
      USE:
          using HideThis
          :
              Hider encryptor = new Hider(<string> <ENTER PASSWORD HERE>);
          :
  2. Encrypt:
      Parameters:
          Data in string format
      Returns:
          Encrypted data in string format
  
  3. Decrypt:
      Parameters:
          Encrypted data in string format
      Returns:
          Decrypted data in string format
  
  4. getStatus:
      Returns bool denoting the activeness of the encryptor object. The encryptor only works if the password is correct.
