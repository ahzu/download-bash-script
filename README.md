# download-bash-script
Using this package to archive the scripts needed to download multiple files at once. 

## Installation
Deploy an Unbuntu instance and upload the source files into the root of the root you would like to import the video files.
Run the Git command below to import the files into the root folder of your video archive. Eg. Horror.
``` 
git clone https://github.com/ahzu/download-bash-script.git ./
```
The Git command will install the files in the root folder which is the target for your downloads. The trailing `./` will inform Git to install all the files in the root folder. If you would like to simply clone the script, exclude the following `./` argument.
## Usage
You wiol be able to use a simple list of video urls (must be direct link ex. ```https://video.mp4```) to download multiple videos at once. After compiling a list of urls, all you have to do is run the following command:

```
./download.sh
```


