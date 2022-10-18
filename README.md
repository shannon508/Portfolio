## portfolio
This is my small project using html/css/bootstrap. I will be using this to showcase my projects.
[Live Replit Deployment]()
## Technologies Used
* HTML
* CSS
## Installation
No need to install any software, just open up index.html and run it
## How To Use ?
Use this template to build your own portfolio
11:42
echo $_SERVER[‘REMOTE_ADDR’];
// Set default server timezone
date_default_timezone_set(‘Asia/Bangkok’);
$timestamp = strtotime(‘now’);
echo ‘SERVER TIMEZONE: ‘. date_default_timezone_get() .‘<br/>’;
echo ‘SERVER DATETIME: ’. date(‘Y/m/d H:i:s’, $timestamp);
echo ‘<hr/>’;
// Set server timezone with client timezone
$client_timezone = new client_ip_data();
date_default_timezone_set($client_timezone->get_timezone());
echo ‘CLIENT TIMEZONE: ‘. date_default_timezone_get() .‘<br/>’;
echo ‘CLIENT DATETIME: ’. date(‘Y/m/d H:i:s’, $t
