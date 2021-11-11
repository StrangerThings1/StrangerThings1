Hello Everyone. 

My main background is business administration. I love coding, project management/development, snickers bars and chex mix.

I am here because of a specific issue right now. I have found it very hard to find good information on cron job interaction and osclass functioning.
I have been searching forums for days and am a bit stuck on this topic right now.

I currently have a website called towncrierclassifieds.com and I am not being successful with the cron job code. 
The cron code is supposed to pull data and send emails to users whos listings are about to expire. 
 

Here is where I am at:
The cron is running successfuly at the server level. 
I receive an email successfully
I then receive an error message at line 64 of the current code telling me the class for cron doesn't exist.

I have two questions at this point. 
1) is it a requirement to use some sort of ABS path for this or can I just comment it out (If I'm calling the script from the server and it's working
do i need more? is this a security issue or just a path issue?).
2) Why is this class 'Cron' an issue here when crons is part of the osclass environment ? 

I have noticed in searching for answers that there a great many others who have been struggling with this topic for some time now.
I am surprised at this and hope we can put most of it to rest with some solid solutions for everybody. 

Thanks much
