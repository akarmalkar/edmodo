# edmodo
This module allow user to login/register to our drupal website using edmodo credentials.
Step I : 
	Go to url : https://docs.google.com/forms/d/1hp-rMXXJbE4v-1TnDxL7_LE-MneR6-W8VO_dV2cL_HY/viewform
	Fill all the details (select all scopes) and submit the form.
	Callback url should be : $base_url/edmodo for e.g. (http://www.example.com/edmodo)
	Drop a mail to support@edmodo.com if you won't receive a key and secret

Step II : 
	Update key and secret in our drupal website. (For every site i.e. development, staging and prodcution site you have to do the steps)
	Enable required module : colorbox and libraries
	Add colorbox libraries in sites/all/libraries folder
	Finally enable this module.

Step III : 
	Go to url : /admin/config/media/colorbox and check both boxes inside "Extra features" and save.
	Go to url : /admin/config/people/edmodo-configuration
	
You will find the on registration/login/login box edmodo icon is visible.

I have done profile2 module integration too with this but right now I am not adding that feature in this module.
Any comments/help needed about module integration please send me an email to "avk029@gmail.com"

Thanksss
