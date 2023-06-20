# SECURE_FILE_TRANSMISSION
This project is about securing any format of file 
Initially the application will ask the user to choose whether he/she need to encrypt or decrypt the file 
After selecting the required option, it will provide user to choose the file 
For encrypting it will ask user to give password and same for decrypting process
Here we have used vignere cipher for encrypting and decrypting the file 
after encrypting the file, we are using SHA 512 to hash the encrypted file, even if the intruder tries to access the file he can’t get the information or modify the information in the file 
on the other end,  the receiver will have to give the same password to decrypt the file
The Vigenere cipher is a type of polyalphabetic substitution cipher that uses a keyword to encrypt and decrypt messages. While it has some advantages over other ciphers in certain situations, it also has some weaknesses that make it unsuitable in other scenarios.
One advantage of the Vigenere cipher is that it is more resistant to frequency analysis attacks than simple substitution ciphers, such as the Caesar cipher. This is because each letter in the plaintext can be encrypted using a different letter in the alphabet, depending on its position in the message and the key used. This makes it harder for an attacker to detect patterns in the ciphertext that could be used to guess the key and decrypt the message.
SHA-512 is a cryptographic hashing algorithm that produces a fixed-length output of 512 bits. It is designed to be secure against various attacks, including collision attacks, preimage attacks, and birthday attacks.
One advantage of SHA-512 over other hashing techniques is its strength and security. It is considered to be one of the most secure hashing algorithms currently available and is widely used in various applications, including digital signatures, password storage, and message authentication. SHA-512 is also approved by government agencies, including the National Security Agency (NSA) and the National Institute of Standards and Technology (NIST).
Another advantage of SHA-512 is its efficiency. It is faster than some other secure hashing algorithms, such as SHA-3 and BLAKE2, while still maintaining a high level of security.
