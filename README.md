# jamesmiddleton-www
My personal website showcasing my portfolio and services.

## Issues
If you come across any issues with the website or you feel it's missing some key information, please [send me an email](mailto:James%20Middleton<hi@jamesmiddleton.me>?subject=j.me%20Issue). Alternatively, you can add an issue on this [GitHub repository](https://github.com/james2mid/jamesmiddleton-www) if you already have an account.

## Technicals
In case you're wondering how this was created and deployed, here are the details:

* Created with [Vue.js](https://vuejs.org) for the front-end framework
* Uses [Bulma](https://bulma.io) as a basis for styling
* With Vue using [Webpack](https://webpack.js.org), it provides a fantastic live local server for development
* The minified build is stored on an [Amazon S3](https://aws.amazon.com/s3/) bucket as a static website
* [Amazon CloudFront](https://aws.amazon.com/cloudfront/) manages distribution and delivery
* CloudFront uses the SSL certificates stored with Amazon to provide access to the website over HTTPS
