# Ahzu Direct Download Script
If you have the task of downloading large music and video files and moving them to another server, this process will help make it easy for you. Ahzu Direct Download Script is a simple, lightweight and effective script written in `SHELL`. All you have to do is compie a list of files you would like to download. Simply run the script and watch the magic.

## Installation
Deploy an Ubuntu instance and upload the source files into the root of the root you would like to import the video files.
Run the Git command below to import the files into the root folder of your video archive. Eg. Horror.
``` 
git clone https://github.com/ahzu/download-bash-script.git ./
chmod +x download.sh
```
or:
``` 
git clone https://github.com/ahzu/download-bash-script.git ./ && chmod +x download.sh
```
The Git command will install the files in the root folder which is the target for your downloads. The trailing `./` will inform Git to install all the files in the root folder. If you would like to simply clone the script, exclude the following `./` argument.

Run this command `chmod +x download.sh` to give the script permission to write data to your server. 

## Usage
You wiol be able to use a simple list of video urls (must be direct link ex. ```https://video.mp4```) to download multiple videos at once. After compiling a list of urls, all you have to do is run the following command:

```
./download.sh
```

Now you should see the download process taking place. When complete, you will be able to either store the files long term or you can move the files to object storage.

## Use Cases
Launching a OTT channel can be stressful. Transferring files from place to place can takes hours and even days if you have to continue to download and upload files to your storage. The script can be used to easily download large video or music files and route them to their final destination. No stress on your local data connection. Let the cloud provide you will enough speed and bandwith to transfer your files at a rapid rate.

For more about this project, follow our GitHub account: <br> 
Ahzu Direct Tech, LLC <br>
www.ahzudirecttech.com
<br> 
