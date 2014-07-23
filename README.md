## What's this
This is an addon starter template for the [Ionic Framework](http://ionicframework.com/).
I'm trying to make SideMenu and Tabs working together the best way.

There's an article about what I'm doing [here](http://codepen.io/mircobabini/developer/ionic-sidemenu-tabs) and the working pen [here](http://codepen.io/mircobabini/pen/gLkli).


## How to use this template

*This template does not work on its own*. It is missing the Ionic library, and AngularJS.

To use this, either create a new ionic project using the ionic node.js utility, or copy and paste this into an existing Cordova project and download a release of Ionic separately.

### With the Ionic tool:

Take the name after `ionic-starter-`, and that is the name of the template to be used when using the `ionic start` command below:

```bash
$ sudo npm install -g ionic cordova
$ ionic start myApp sidemenu
```

Then, to run it, cd into `myApp` and run:

```bash
$ ionic platform add ios
$ ionic build ios
$ ionic emulate ios
```

Substitute ios for android if not on a Mac, but if you can, the ios development toolchain is a lot easier to work with until you need to do anything custom to Android.

## Demo
[http://codepen.io/mircobabini/pen/gLkli](http://codepen.io/mircobabini/pen/gLkli)

## Contrib & Issues
Feel free to fork this repo, the pen or anything else. Feel also free to submit any issues or requests.
