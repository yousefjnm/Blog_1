# Blog_1

What is AWS Rekognition service and how can it be used?

Aws Rekognition service is a service that recongnizes the faces in the video and compares them to the picture you have in the collection of images that you make and tells you who is in that video. It also has a celebrity recognition service and what it does is basically it scans the video and gives you a result of all celebrities that showed in the video.


AWS Rekognition service could be used in different ways, one is directly from the console and second is frin a programming interface that's connected to your AWS account.

Today, I will be explaining how ot use it from the console and next week, I will explain deeply how to use it from a programming interafce like Lambda using Python as your programming language. I will also explain some automating features and other great things that you could utilize if you use the service using a programming interface instead of using it directly from the console.

So the steps are pretty straightforward:
1- you login to your AWS acount

2- using the searching section, look for the Rekognition service and go to it

3- you need to store the video that you want to process in an S# bucket

4- you can create a collection of images in the Rekognition if you wish

5- now you can start a celebrity detection job which detects any celebrity that shows in the video or you can just start a face detection job that compares people in video with the images you have in the collection you made.

depends on how long the video is, the longer the video is the longer it takes for the service to fetch it.
