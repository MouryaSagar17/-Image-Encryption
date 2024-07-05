#  Image Encryption

The images must be encrypted in such a way that even with arbitrary access to them via the internet, the image must not be decryptable without a secure key. This project would help you delve into the basics of cybersecurity and develop your cryptography skills.

+ [Requirements](#Requirements) 
+ [Execution](#Execution)
+ [Image Encryption](#encryption)
+ [Image Decryption](#decryption)
+ [ Output ](#Output)

### Requirements <a name="Requirements"></a>
  1. Python Idle
  2. Visual Studio Code (VS Code)
  3.  Any IMAGE FOR INPUT 

### Execution and Input <a name="Execution"></a>

# Image Encryption <a name="encryption"></a>
  1. Converted image files into a suitable format (e.g., byte arrays).
  2. Applied the chosen encryption algorithm to the image data using a secure key.
  3. Ensured that the encrypted image data could be stored and transmitted securely.


 1. For Input 

* `Image Encryption` usage:
```Python
python encrypt_decrypt.py -e input_image.jpg -o encrypted_image.enc -k keyfile.key

```
# Input image : 
![input_image](https://github.com/MouryaSagar17/-Image-Encryption/assets/143429477/a2300cdc-0978-4769-8815-bc07e00a9959)


# After Encryption the Key is generated with .key extension 

![Key file](https://github.com/MouryaSagar17/-Image-Encryption/assets/143429477/d5272326-07c6-44de-8d8a-b818776118d5)



# Image Decryption <a name="decryption"></a>

1. Verified that the encrypted images could be decrypted accurately using the secure key.
2. Implemented checks to ensure that without the secure key, the encrypted data remains unintelligible.


* ` Image Decryption ` usage:
```Python 
python encrypt_decrypt.py -d encrypted_image.enc -o decrypted_image.jpg -k keyfile.key

```
# After Decryption the image is :

![decrypted_image](https://github.com/MouryaSagar17/-Image-Encryption/assets/143429477/d995ea35-03c5-4d1a-a28a-80c15c95b202)



### Output: <a name="Output"></a>

![output for  Image Encryption](https://github.com/MouryaSagar17/-Image-Encryption/assets/143429477/c1b3010a-5e20-4c19-8c5b-d573c96b79d7)


Successfully encrypted and decrypted image files using the selected algorithm.
Demonstrated that the images remain secure when accessed over the internet, requiring the secure key for decryption.
Evaluated the performance of the encryption process, noting any impacts on processing time and resource usage.









  
