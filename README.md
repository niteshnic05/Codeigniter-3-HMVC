# Codeigniter-3-HMVC
###### Modular Extension for Codeigniter 3

This is fork from bitbucket of 'Wiredesignz' 
You can find the main repo here:
*https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc*

Just doanload & upload these files to your existing Codeigniter 3 installation directory and it's ready to write a code in modular format.

You have to create **modules** folder under application folder.
Under modules folder you should create your desired module folder such as users, so basically folder structure for your module will be

```
 -application
  -modules
   -users
     -controllers
       -Users.php
     -models
       -UserModal.php
     -views
       -login.php
```
 
And all controller should extends **MX_Controller**
```
<?php
class Users extends MX_Controller
{
	function __construct(){
		parent::__construct();
	}
    public function index(){
      
    }
 }
  
```
