# Decrypt-Discord-Token
in one of discords recent updates they started encrypting user tokens to prevent token logging by script kiddies and retards. unfournately if you have a single brain cell you can find out that discord stores the encryption key within their files. It is stored in the 'local state' file in json format. this python script allows the decryption of encrypted tokens from both user input and local discord files. educational purposes only

note: if you want to look into it further discord encrypts the token in local storage but not in requests. discord uses electron's safeStorage for encryption. 
