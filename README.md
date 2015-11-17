This repository contains various HTML/CSS testing and sampling I have done to try out different things. Feel free to use and abuse as you see fit.

Since I do all of my development on Linux machine but work from a Windows desktop, I need to a way to easily see the results of my files. I use 'SimpleHTTPServer' to do this.

Just run the following command in the directory of the files:
```
$ python -m SimpleHTTPServer
Serving HTTP on 0.0.0.0 port 8000 ...
```
Then point your browser to `http://<Server IP Address>:8000` and you should see something like:

![Hosting Example](/screenshoots/host_example.png?raw=true "Page Display of hosted files via SimpleHTTPServer")

