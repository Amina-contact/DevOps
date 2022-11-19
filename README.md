# DevOps
This lab consists in the first part of Creating and configuring a Jenkins Job of the free style type and Configuring this Job in order to generate an image (docker build) and publish a
docker image of the project on docker hub (Tag latest).<br>
In the second part we advance Create another freestyle job containing the same instructions of the previous job of the first part while adding a Shell script which
deploys the image under a new container on docker engine.<br>
And in the third part we created a job of the pipeline type (which takes up the same tasks of the job
previous freestyle but in another way), add without changing anything in the job parameters, a script in the script part of the pipeline ensuring the three
internships (Cloning Git, Building image, Publish Image).<br>
And finally we move on to Create a pipeline type job too. But the latter will contain four Stages
(Cloning Git, Building image, Test image, Publish Image) in a 'jenkinsfile' file which defines the script ensuring the four stages and subsequently we specified the path of the 'jenkinsfile' file on the job.
