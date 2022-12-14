# Cryogen-website-installer
 Cryogen is a 5 step installation processor that helps to install website that build in core php or support any php frameworks. 
 
 # Youtube Demo
 <img src="https://user-images.githubusercontent.com/110724391/187073188-8deaefc3-75ba-4df9-b2bf-423253f8321d.png" width="700" height="400">
  https://youtu.be/1LMv-aBUDM0
  
# Installation
We can add or remove any server extentions in <code>$requiredServerExtensions</code> according to website requirement in <code>install/index.php</code>
```PHP
$requiredServerExtensions = [
 'BCMath', 'Ctype', 'Fileinfo', 'JSON', 'Mbstring', 'OpenSSL', 'PDO','pdo_mysql', 'Tokenizer', 'XML', 'cURL',  'GD','gmp'
];
```
Set folder permissions here <code>install/index.php</code>
```PHP
$folderPermissions = [
 'test/','test-2/','config/'
];
```
Path to change the <code>.env</code> file
```PHP
$envpath = dirname(__DIR__, 1) . '/install/config/.env';
 ```
 Path to change the website landing and admin login after installation on <code>line no 225 & 225</code>
 ```HTML
 <a href="'.getWebURL().'" class="theme-button choto">Go to website</a>
 <a href="'.getWebURL().'/admin" class="theme-button choto">Go to Admin Panel</a>
```
Replace database.sql with your corresponding sql in <code>install/database.sql</code> without changing the name of database.
  
  
# Step 1: Accept the Term&Conditon agreement

<img src="https://user-images.githubusercontent.com/110724391/186402108-e2a4c6b8-62fe-4c2b-8a08-4ea48d6c2d62.png" width="400" height="400">

# Step 2: Set the server extention requirements
<img src="https://user-images.githubusercontent.com/110724391/186402125-7960b2d1-9b09-4ab1-adbc-af3835304bcb.png" width="400" height="400">

# Step 3:  Set the Folder permissions
<img src="https://user-images.githubusercontent.com/110724391/186402135-b799c7f6-d412-44d0-b43b-9177495cda49.png" width="400" height="400">

# Step 4: Enter purchase code, Database details & Admin login details
<img src="https://user-images.githubusercontent.com/110724391/186402141-8be043b1-11d1-4c61-b2d2-8f769440c46e.png" width="400" height="400">

# Step 5: Installation successful!
<img src="https://user-images.githubusercontent.com/110724391/186402152-075dbbcc-5eb7-4d2f-97ce-07b1b00e84a9.png" width="400" height="400">

