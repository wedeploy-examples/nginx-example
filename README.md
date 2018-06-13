[![Deploy](https://cdn.wedeploy.com/images/deploy.svg)](https://console.wedeploy.com/deploy?repo=https://github.com/wedeploy-examples/nginx-example)

# Node.JS

An example of [NGINX](https://www.nginx.com/) on [WeDeploy](https://wedeploy.com/).

## Instructions

1. Install the [WeDeploy CLI](https://wedeploy.com/docs/intro/using-the-command-line/).
2. Clone this repository.
3. Open the project with your command line and run `we deploy -p yourproject`.

## Note

This example shows the NGINX default page. If you try to access the path `/wedeploy`, you will be redirected to `http://wedeploy.com` since we defined this redirect 
inside the `custom/.conf` file.

## License

[BSD-3-Clause](./LICENSE.md), © Liferay, Inc.
