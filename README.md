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


![image](https://user-images.githubusercontent.com/69750612/118720130-d96db800-b846-11eb-8456-7d2ebd8d0c61.png)

# Application
There are many applications of Visual Cryptography some of them are following:
1. Secret Communication
2. Copyright Protection
3. Document Authentication
4. Secret data storing




Reference:https://github.com/srajat/Visual-Cryptography-Using-K-N-Secret-Sharing#aes
InKoo Kang, Member, IEEE, Gonzalo R. Arce, Fellow, IEEE, and Heung-Kyu Lee, Member, IEEE, “Color Extended Visual Cryptography Using Error Diffusion”, IEEE TRANSACTIONS ON IMAGE PROCESSING, VOL. 20, NO. 1, JANUARY 2011. 
Shyamalendu Kandar , Arnab Maiti,” K-N secret sharing visual cryptography scheme for color image using Random number”,vol 3,no.3,Mar 2011.  
M. Naor and A. Shamir, “Visual cryptography,” in Proc. EUROCRYPT, 1994, pp. 1–12. 
G. Ateniese, C. Blundo, A. D. Santis, and D. R. Stinson, “Visual cryptography for general access structures,” Inf. Comput., vol. 129, no. 2, pp. 86–106, 1996. 
 Y.C. Hou, F. Lin, C.Y. Chang, A new approach on 256 colorsecret image sharing technique, MIS Review, No. 9, December1999, pp. 89–105.  
 Y.C. Hou, C.Y. Chang, F. Lin, Visual cryptography for colorimages based on color decomposition, Proceedings of the FifthConference on Information Management, Taipei, November1999, pp. 584–591.
  Asoke Nath, Saima Ghosh, Meheboob Alam Mallik, Symmetric Key Cryptography using Random Key generator : “Proceedings of International conference on security and management(SAM’10” held at Las Vegas, USA Jull 12-15, 2010), Vol-2, Page: 239-244(2010). 
 Asoke Nath, Sankar Das, Amlan Chakraborti, Data Hiding and Retrieval : published in IEEE “Proceedings of International Conference on Computational Intelligence and Communication Networks (CICN 2010)” held from 26- 28 NOV’2010 at Bhupal, Page: 392-397(2010).
Feng Liu and chuankun Wu.(2011), ‘Embedded Extended Visual Cryptography Schemes’, IEEE TRANSACTIONS ON INFORMATION FORENSICS AND SECURITY, VOL. 6, NO. 2, pp. 307-322


