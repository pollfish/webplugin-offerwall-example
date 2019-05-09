# webplugin-offerwall-example
An example of how a publisher can integrate the webplugin integration to their website using an offerwall approach.

![HowItLooks](https://user-images.githubusercontent.com/4293389/57443362-87a4f700-7256-11e9-9465-fff80e206e6b.png)

## What this example does
- It will not allow the webplugin integration to autostart
- It will change the number of lives provided based on each survey completed revenue
- It will handle the case where a survey is not available

More information can be found [on the webplugin documentation](https://www.pollfish.com/docs/webplugin).

## See it working

The only thing you need to do to see this demo working is to just open or serve the index.html,
or you can just open a dev-server immediately after installing the `live-server` npm package.

First install it
```shell

npm install live-server
```

then just run it and voila, you should be able to visit http://localhost:8080 to see the demo
```shell
live-server
```

(live-server might open the development server in a different port if the port 8080 is already occupied).
