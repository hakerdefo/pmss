# pmss

**pmss** (Poor Man's Screenshooter) is a simple bash front-end to screen capture utility Scrot. **pmss** lets you easily capture screenshots without having to remember various options and flags of Scrot. **pmss** also utilizes power of xdotool to make the task of taking screenshots in variety of ways not only possible but enjoyable. After taking that perfect screenshot **pmss** can optionaly upload the screenshot to imgur and give you image sharing links for GitHub, Reddit, Forums, Message boards, Websites, Blogs. Of course **pmss** will also give you direct image link and a link to delete the uploaded image. What's more, **pmss** will also keep a log of all the uploaded images so you can reuse the image link(s) whenever you need them or delete the image using the delete link if need be. **pmss** also helps you manage the saved screenshots. You'll be able to clean the whole screenshots directory with a single key press.


## Features :

 - Take the screenshot of the entire screen
  - Clean mode
  - Dirty mode
 - Take the screenshot of window in focus
  - Window below the current window
  - Window under the mouse cursor
  - Window selected by the user
 - Take the screenshot of area selected by mouse
 - Upload the screenshot to imgur
 - Image sharing links in multiple formats
 - Image upload log
 - Manage saved screenshots


## Dependencies :

### Required :

- Scrot - Scrot is a minimalistic command line screen capturing application. [Scrot] is available in repositories of almost every linux distribution out there. Use your distribution's package manager to install Scrot.
- xdotool - xdotool lets you simulate keyboard input and mouse activity. [xdotool] is available in repositories of almost every linux distribution. You can easily install it from your package manager.

### Optional :

- curl - curl is a tool to transfer data from or to a server, using one of the supported protocols (DICT, FILE, FTP, FTPS, GOPHER, HTTP, HTTPS, IMAP, IMAPS, LDAP, LDAPS, POP3, POP3S, RTMP, RTSP, SCP, SFTP, SMB, SMBS, SMTP, SMTPS, TELNET and TFTP).
[curl] is available in repositories of almost every linux distribution. You can easily install it from your package manager.
- Less - Less is a free, open-source file pager. It can be found on most versions of Linux, Unix and Mac OS, as well as on many other operating systems. [Less] is available in repositories of almost every linux distribution. You can easily install it from your package manager.


## Installation :

Download [pmss-master] zip, extract its contents and copy **pmss** to **/usr/local/bin/** directory,
```sh
sudo cp pmss /usr/local/bin/
```
Next make it executable,
```sh
sudo chmod 755 /usr/local/bin/pmss
```


## Usage :

Open terminal, run pmss, say CHEESE!!!

What is a screenshot utility without a screenshot?!?

![alt text](http://i.imgur.com/FeQb80D.png "pmss")


## My WM hates xdotool or how I loved the original pmss :

No problemo! In the [pmss-master] zip, You'll find a file named **pmss-legacy** and all you'll have to do is,
```sh
sudo cp pmss-legacy /usr/local/bin/
```
```sh
sudo chmod 755 /usr/local/bin/pmss-legacy
```
Please say CHEESE now!!!


## License :

[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">pmss</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/pmss)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.
[Scrot]:http://freecode.com/projects/scrot
[xdotool]:http://semicomplete.com/projects/xdotool
[curl]:https://curl.haxx.se/
[less]:http://www.greenwoodsoftware.com/less/
[pmss-master]:https://github.com/hakerdefo/pmss/archive/master.zip
