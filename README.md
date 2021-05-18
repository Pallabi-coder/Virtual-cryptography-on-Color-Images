# Virtual-cryptography-on-Color-Images
Visual cryptography is a cryptographic technique which allows visual information (pictures, text, etc.) to be encrypted in such a way that decryption can be done just by sight reading. Visual cryptography, degree associated rising cryptography technology, uses the characteristics of human vision to rewrite encrypted photos. 
![image](https://user-images.githubusercontent.com/69750612/118719595-4c2a6380-b846-11eb-9c18-3880c1d7d24d.png)

![image](https://user-images.githubusercontent.com/69750612/118719640-58aebc00-b846-11eb-8c12-daea58252c97.png)

# Problem Statement
The main motto is to provide the high security, increase in the number of shares and reduce the pixel expansion problem and high resolution to visualize the secret color image. Information send through any network have a chance to attack by Intruders. Encryption provides an obvious approach for information security, and encryption programs are readily available. The encryption provides a desirable form to send information without anyone even noticing that information has been sent secret information.
![image](https://user-images.githubusercontent.com/69750612/118719696-6e23e600-b846-11eb-82a7-02a882b58c6b.png)

# Propsed System
In this project we take any image which is to be shared secretly. This image is encrypted using a key given by the user. Further, the encrypted image is divided into N different shares using K N Secret Sharing Algorithm. These N shares can be distributed but, the end user needs only K of these shares to generate the original image. After the original image is generated it is still in encrypted form. The key which is used to encrypt the image originally is now required again to decrypt it, thus providing an additional level of security.


![image](https://user-images.githubusercontent.com/69750612/118719893-9f9cb180-b846-11eb-844f-d1bee55f4904.png)

# Observation

We experimented K-N sharing algorithm on Lena image.
Number of shares (n) = 10
Number of shares to be taken (k) = 6,
The experimental result after encryption by the k n encryption algorithm is given below: 
We can get the original image only by stacking k or more shares. If value of k is less than required (in this case k = 6), we will get a partial image. After choosing any number of shares of all the generated shares


AES encryption results
          A symmetric key based encryption (AES encryption) at both the ends of KN Shares
           Algorithm is added to make the image more secure.
 Thus, after encrypting the original image with AES first, and then, regenerating the shares give more better and noisy image. Now, the image will require at-least k shares  along with the symmetric key in order to decrypt the image to its original form.
![image](https://user-images.githubusercontent.com/69750612/118720107-d1ae1380-b846-11eb-9038-2e34cc5b923e.png)

![image](https://user-images.githubusercontent.com/69750612/118720130-d96db800-b846-11eb-8456-7d2ebd8d0c61.png)

Reference:https://github.com/srajat/Visual-Cryptography-Using-K-N-Secret-Sharing#aes
