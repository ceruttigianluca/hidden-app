# Hidden App

![Hidden App icon](http://www.laboratoriociliegia.it/github/hidden-app-icon-small.png)<br>
Hidden App is a very simple app for **developers** that allows you to **show and hide macOS hidden files** in just **one click**.<br>
Hidden App is an Automator app that run this shell script:<br>
```sh
STATUS=`defaults read com.apple.finder AppleShowAllFiles`
if [ $STATUS == 1 ]
then defaults write com.apple.finder AppleShowAllFiles -boolean FALSE
else defaults write com.apple.finder AppleShowAllFiles -boolean TRUE
fi
killall Finder
```

[Hidden App](https://github.com/ceruttigianluca/hidden-app/archive/master.zip) - Download Hidden App

## Do you need something more?
[Space App](https://github.com/ceruttigianluca/space-app) - Space App, add spaces to your Mac's Dock in just one click<br>
[Rocket App](https://github.com/ceruttigianluca/rocket-app) - Rocket App, reset your Mac's Launchpad in just one click<br>
[Spot App](https://github.com/ceruttigianluca/spot-app) - Spot App, reset, fix and re-index your Mac's Spotlight in just one click<br>

## Buy me a coffee
[Paypal.me](https://www.paypal.me/gianlucacherry/2gbp) - Thank you! :raised_hands:
