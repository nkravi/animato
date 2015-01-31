# Animato

##fully scalable framework to make videos out of photos

>In this project we have developed an application to convert photos to video.
>we have used flask framework to create our webserver. ec2 instances to launch web-server
>and worker. size of SQS queue to scale up and down the workers. dynamoDB to avoid duplicate
>message from sqs. S3 to store photos

###Architecture diagram
![drawing](https://github.com/nravi89/animato/blob/master/architecture.JPG)

###Files

* config	give your configration here
* setup  	run do_setup.ipynb to setup Animato on ec2
* watcher	to scale workers up and down depending SQS system
* webserver	contains webserver code
* worker        contains worker code




