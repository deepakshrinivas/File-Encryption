# File-Encryption

Installation:
The cryptography library can be installed using the below command:

pip install cryptography

Generate Key to encrypt the file
In the cryptography library, there is a cryptography algorithm called fernet. We will use the fernet module to encrypt the file.

Above code will generate a file with the name filekey.key. The file will contain one line, which is a string acting as a key i.e. J64ZHFpCWFlS9zT7y5zxuQN1Gb09y7cucne_EhuWyDM=

Encrypt the file using the key generated

Now we have an encrypted key and file to be encrypted. Now write code to encrypt this file:

1. Open the file that contains the key.
2. Initialize the Fernet object and store it in the fernet variable.
3. Read the original file.
4. Encrypt the file and store it into an object.
5. Then write the encrypted data into the same file nba.csv.
