# StegoMedia
Steganography using Image Encryption and decryption
#In this project there are option of Encode and Decode. In Encode there are option of upload image after that Enter message that you want to encrypt and enter password.
#After click on encrypt data button they give download button to download an image in our systen/device after that If you want to decode this image go another option Decode and upload an downloaded image and enter the password that you enter when you encrypt the data and click on Decrypt data and If the password is correct then you will see your Encrypted message.

#for run server/ backend
cd stegomedia/server
npm install jimp    #if this give error then use below command

npm uninstall jimp
npm install jimp@0.16.1
node server.js

#for run frondend
cd stegomedia/client
npm start
