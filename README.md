Starting Point for Hype usage with Cordova.

More to come.

-RM


![](https://github.com/RandyMcMillan/CordovaHypeTemplate/raw/master/CordovaHypeScreenShot.png)



Backup your copy of indexTemplate.html located in your Hype.app/Contents/Resources/ folder


![image](https://github.com/RandyMcMillan/CordovaHypeTemplate/raw/master/indexTemplate.png)

and replace with this one.


Use the /www folder in your Cordova app.

![image](https://github.com/RandyMcMillan/CordovaHypeTemplate/raw/master/www.png)

For a Cordova (iOS) app 

change
<code> 
		
		self.viewController.startPage = @"index/index.html";

in your AppDelegate.m 

<br><br>
The MIT License

Copyright © Randy McMillan 2012

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.