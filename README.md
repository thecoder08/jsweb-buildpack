# Jsweb buildpack

A fork of [Pyweb buildpack](https://github.com/thecoder08/pyweb-buildpack).

This allows developers to deploy their Jsweb apps to Heroku. To use it, go into the app settings and enter `https://github.com/thecoder08/jsweb-buildpack` as your buildpack.

To let the buildpack know that you are using it, ensure that you have a `package.json` in the root of your project. This will allow heroku to detect that you are using Jsweb and load the Jsweb buildpack.

