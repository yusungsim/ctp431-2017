# Homework 1: Beatbox

![Beatbox](./beatbox.jpg)
The first homework is implementing a simple beatbox with which you can play music beats. The start-up code is provided so that you can easily work on it. Checking out the following links will help you to get more understanding on it.  


[Wikipedia: Beatboxing](https://en.wikipedia.org/wiki/Beatboxing)
[Beatbox community: www.humanbeatbox.com](https://www.humanbeatbox.com/)
[How to make basic beatbox sounds](https://www.youtube.com/watch?v=B6-45rswo0o)

## Step #1 
Practice the beatboxing and record your voice. You can modify the recorded samples using audio effects in [Audacity](http://www.audacityteam.org/) or [Adobe Audition](http://www.adobe.com/kr/products/audition.html) (freely available on campus). 

## Step #2
Download the start-up code and fill out the empty part. 
- Load the recorded audio samples and make sure if they are played correctly.  
- Add gain nodes for each sample in the web audio path. Control the gain parameter such that it adjusts the volume in dB scale with the range from -24 to 0 dB. 

## Step #3
Extend the start-up code by 
- Adding more (different types of) beat samples and corresponding pad buttons on the GUI
- (Optional) Decorating the GUI with text or visual components 


### Tips for coding

#### Http-server: simulating web servers on a local computer

Preloading sound samples from the server side (e.g. using XMLHttpRequest()) requires the client-server communication setting. This cannot be run by opening the html file in the local folder. Instead, we can simulate the server on local using a command-line tool called "http-server". For installation, refer to https://www.npmjs.com/package/http-server. Once you successfully install it, you can emulate the http server from your local path by typing this in command line:
```sh
$ http-server [path]
```
and this in the URL of web browser.
```sh
http://127.0.0.1:8080/ 
```
#### Javascript playgrounds 
Another option to run your code in a server is using Javascript playgrounds where you can edit and run the code in the web browser:
- http://jsbin.com/
- https://jsfiddle.net/
- http://codepen.io/
- http://liveweave.com/
