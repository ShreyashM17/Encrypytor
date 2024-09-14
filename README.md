# Encrypytor
It is a code for encryption of passwords, and it has an inbuilt decryptor as well, it is coded purely in python with no external libraries

### Example:-
#### Encrypting a password
```
value = 'Password'
encryption = encoder(value)
print(f'Result: {encryption}')
```
> Result: y^9PaNq+ssIo_wo0HSrd324e
#### Decrypting a password
```
value = 'y^9PaNq+ssIo_wo0HSrd324e'
decryption = decoder(value)
print(f'Result: {decryption}')
```
> Result: Password
