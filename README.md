# RipRobot (with abcde)
Python script for ripping audio cds to USB storage on raspberry pi

My changes in this fork:

I had problems with the tool ripit: In my case ripit did the job of ripping my disc, but it took ~1h compared to 10 minutes when using abcde. 
Also the drive made a lot of noise in case of ripit, seems like the reading head did a lot more jumps.

If you want to replicate this, make sure to have abcde and everything you need properly installed.
E.g. you need lame and eyed3 for mp3 encoding.
It is best to try ripping a cd with abcde alone first, before using the tool in RipRobot.

Here is a great guide on building a headless raspberry pi for cd ripping: https://www.connect.de/ratgeber/rip-robot-cd-ripper-3200946-8831.html
After installing their image you can swap the ripRobot.py, if you want to use abcde.

I included the config file as reference for my default settings.
It usually goes into /etc/abcde.conf

RipRobot is free software under creative common license

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
