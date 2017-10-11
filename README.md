# FaceMail
This script sends an email when a new post is posted on the Facebook page of MetaKGP to the email specified in `CONFIG` file containg all the details of the post.

## How to use 
* Firstly clone the repository. <br>
`git clone https://github.com/metakgp/facemail`

* Now go inside the cloned directory. <br>
`cd facemail`

* Move the `CONFIG.template` file to `CONFIG`. <br>
`mv CONFIG.template CONFIG`

* Now open the `CONFIG` file and fill in the necessary details.  <br>

* Get you facebook access token by following the instructions from <a href="https://smashballoon.com/custom-facebook-feed/access-token/">here</a> and save it to file named `FB_ACCESS_TOKEN`. 

<br><br>
For the script to work properly please ensure that access to less secure apps is enabled for FROM_EMAIL 
The instructions to do so can be found <a href="https://www.google.com/settings/security/lesssecureapps">here</a>. 
<br><br>

### Modules Required : facepy , pygmail
   
