# Face-Recognition-using-aws-services
![image](https://user-images.githubusercontent.com/87887762/232319682-f3577412-9271-49a2-a327-a45dadf8b77a.png)
A face analyzer is software that uses a person's face to recognize or verify their identification. It operates by recognizing and quantifying face characteristics in images. Facial recognition technology can recognize human faces in pictures or videos, assess whether a face appears in two different pictures of the same person, or look for a face in a big database of pictures that have already been taken. Facial recognition is a technique used by biometric security systems to more reliably identify users during user registration or login processes. Face analysis technology is also often used in mobile and personal devices to ensure device security.
With the help of the service Amazon Rekognition, it's simple to integrate picture analysis into your apps. It is built on the same deep learning technique that Amazon's computer vision experts created to analyse billions of photographs every day for Amazon Prime Photos, which is well-proven and extremely scalable. You can identify similar faces in a big number of pictures using facial recognition. The services which will help for face recognition.
Amazon S3 bucket
Amazon Lambda
DynamoDB
Amazon Rekognition
Here are a few advantages of facial recognition systems:
Reliable security: A rapid and effective verification method is facial recognition. In comparison to other biometric methods like fingerprint or retinal scans, it is quicker and more practical. Comparing face recognition to typing passwords or PINs, there are also fewer touchpoints. Multifactor authentication is supported for a second layer of security check.
Improved accuracy: When identifying people, facial recognition is more reliable than using just a phone number, email address, address, or IP address. For instance, the majority of exchange services, including those for stocks and cryptocurrencies, now rely on face recognition to safeguard clients' money.
Easier integration: The majority of security software is compatible with and readily integrated with face recognition technologies. For instance, software or algorithms for face recognition are already supported by smartphones with front-facing cameras.
The indexing approach for your collection will be determined by your use case, as follows: 
Face match: You might need to locate a match for a certain face among a group of faces (as in the case of our present example). Numerous use cases may be supported by Face Match. For instance, blacklisting individuals to identify undesirable actors or supporting logging circumstances. Whitelisting a set of people for a VIP experience. In those circumstances, you would build a single collection that includes a lot of faces or, in the logging situation, a single collection for a set amount of time, like a day. 
Facial verification: You would really build one collection per individual in situations where a person claims to be of a given identity and you are utilising facial recognition to verify the identification (for example, for access control or authentication). To increase the match rate, you would keep a range of face samples for each individual. This allows you to add samples of other looks to the identification model, such as instances when a person has grown a beard. 
Social tagging: You would use one collection for each application user if you wanted to automatically tag friends in a social network. 
->Create a s3 bucket and add objects.
->Create a lambda function and trigger.
->Depolye the code in function
Implemention:
![image](https://user-images.githubusercontent.com/87887762/232320178-dc3b521e-a1cf-4be8-93d8-5c9b5222aab4.png)
![image](https://user-images.githubusercontent.com/87887762/232320193-13b81f49-ce9d-4036-ad59-5598839f2bfd.png)
![image](https://user-images.githubusercontent.com/87887762/232320203-c5b8c0ad-6f5f-4f95-9bde-ea905193a21d.png)
![image](https://user-images.githubusercontent.com/87887762/232320216-2ad394b9-8139-440c-940e-c993280d9ee8.png)
![image](https://user-images.githubusercontent.com/87887762/232320221-ec8a2e72-b317-4ffc-bec3-e5af5a2b576e.png)
![image](https://user-images.githubusercontent.com/87887762/232320228-b6ca0dde-5ce1-4e1d-b9b6-680ec913174e.png)
![image](https://user-images.githubusercontent.com/87887762/232320236-984a9a17-71f4-4d21-808d-75ae2c1d153d.png)
![image](https://user-images.githubusercontent.com/87887762/232320241-8b9a478e-31c0-4587-8e40-f6edc5417bbd.png)
![image](https://user-images.githubusercontent.com/87887762/232320253-b2ce473f-5352-4b89-b097-f20245749ca4.png)
![image](https://user-images.githubusercontent.com/87887762/232320259-8c352d09-afb6-4164-a208-8ae011493c26.png)
![image](https://user-images.githubusercontent.com/87887762/232320265-fed737ed-abad-42ee-8b44-dd26c30cacc3.png)
