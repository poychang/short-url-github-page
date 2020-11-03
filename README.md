# Short URL App

A Short URL App base on GitHub Pages.

If you want to add a short URL, please modify the `routes.json` file directly, and set it up in the way of `"key": "value"`, `key` is the name of the short URL, and `value` is the destination URL.

## Local Test

Use [live-server](https://www.npmjs.com/package/live-server) for testing.

In order to simulate when GitHub Page cannot find the webpage, it will automatically use `404.html` to open the page. When starting the live-server, please add the `--entry-file=404.html` parameter.

```bash
# install live-server micro http server
npm install -g live-server
# launch live-server and set --entry-file to redirect to 404.html when page missing
live-server --entry-file=404.html
```
