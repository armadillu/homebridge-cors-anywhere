# Homebridge Cors anywhere

This plugin provides an instance of the cors-anywhere proxy, hosted on homebridge. This means, that through it, every response has the `access-control-allow-origin: *` header.

You have a local web application which needs access to url with non-matching CORS? Then this is the plugin for you.

It is built entirely on top of the `cors-anywhere` npm package. Use their docs to find out how to use this plugin properly:

https://www.npmjs.com/package/cors-anywhere

The proxy is listening at `(your-homebridge-ip):5654`