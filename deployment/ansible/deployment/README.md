# Manual steps to deploy newsletter
----
- ```git clone https://github.com/voidlabs/mosaico.git```
- ```npm install```
- get the template and patch file from ```https://github.com/media-centre/NewsLetterGeneration.git```
- copy media center template in templates folder
- apply the patch for index.html ```git patch file_name.patch```
- ```grunt build```
- ```pm2 start grunt --name newsletter -- server```