# AWS-Deeplens
Note:
I have created this readme file for reference during the amazon interview the day before.Please apologize if unable to understand :)
Platform: Amazon Deeplens
Language: Python
Services used:
AWS greengrass for deployment across fleet of devices
AWS Lambda(which is used to interact to write code which interact with aws services when required)
AWS EC2(We used small severs for our applications)
(Forgot to turn off the instances and was billed huge :) )

Other AWS services:
AWS Rekognition: We used it to create collection,store faces,compare faces in collection,object detection etc.
AWS polly: Text to speech
AWS S3: To store images,documents in case of Document AI
AWS transcribe: Didnt use yet.but good speech to text api which we planned to use later.
AWS tranlate: To translate between different languages with different voices.

AWS deeplens is a edge device of amazon just like google AIY kit.
Except that,it can be used for both vision and voice in a single project.
We also combined google voice and vision kit in a single project but,hardware wise it will be troublesome.
We trained a mobilent model for helmet detection using google **teachable machine** and few other models using instructions for training model using google AIY vision kit.
We ran that model here.

I shall update this readme later.Thanks
