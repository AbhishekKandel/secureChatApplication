# secureChatApplication
A project for completion of the J component of Information Security Management course.

Our project is a secure chat application with aes encryption and google firebase authentication for extra security, will store the db in google firebase, and our application can be used with any android device.

Advanced Encryption Standard
AES is a popular and widely adopted symmetric encryption algorithm, in which same key is used for both encryption of plain text and decryption of the cipher text.
It is based on ‘substitution–permutation network’. It comprises of a series of linked operations, some of which involve replacing inputs by specific outputs (substitutions) and others involve shuffling bits around (permutations).
We'll be using 128 bit i.e. 16 byte key for encryption and decryption operation.

Security model
1) The sender type Text Message (TM)
2) TM converted to Bytes Array (BA)
3) Encrypt the BA (EBA): performed by AES with the Generated secure key
4) Convert the EBA to String (ES) 
5) Send the ES to  the  server 
6) The recipient receives the ES
7) Convert the received ES to Bytes Array (EBA) 
8) Decrypt the EBA (BA)
9) Convert the BA to string which is same as the sender's message (TM)

To sign a user into our app, user will be asked for authentication credentials. (eg.user's id, phone and otp) Then, these credentials will be passed to the Firebase Authentication SDK for user authentication.
so, this app will allow users to chat securely from android devices. 


Flowchart


![image](https://user-images.githubusercontent.com/89520561/169235586-24541690-b046-464e-839f-af57e4c39a4c.png)




Firebase


![image](https://user-images.githubusercontent.com/89520561/169236110-b731f860-3cf1-4326-a5e8-1743e0e111cc.png)



Users
![image](https://user-images.githubusercontent.com/89520561/169236705-a6adb17f-9363-423a-bccf-19aa74a0e295.png)



Encrypted Messages


![image](https://user-images.githubusercontent.com/89520561/169237136-d73ca383-140f-4843-bec2-7c3d0f61d92c.png)


![image](https://user-images.githubusercontent.com/89520561/169237217-20222c18-4aa3-46cc-b4ac-adf70934205a.png)



App
Registration and login


![image](https://user-images.githubusercontent.com/89520561/169237470-24e2df92-61ef-47cf-b4f4-1eee85bcf1a0.png)


![image](https://user-images.githubusercontent.com/89520561/169237515-1875ea62-fc7d-4abe-b236-19598f6a42cf.png)



Chat Screen


![image](https://user-images.githubusercontent.com/89520561/169237846-23e9b939-fb63-487c-af70-f474ac1e9b87.png)
![image](https://user-images.githubusercontent.com/89520561/169237894-6f2b51b4-d5e0-4b3f-87cc-4b58433f8960.png)



