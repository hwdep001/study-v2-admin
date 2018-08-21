## [Status Bar](https://ionicframework.com/docs/native/status-bar)

```
$ ionic cordova plugin add cordova-plugin-statusbar
$ npm install --save @ionic-native/status-bar
```

## app.component.ts
```
initializeApp() {
	...
	// this.statusBar.styleDefault(); 삭제
	this.statusBar.backgroundColorByHexString("#323435");
	...
}
```

## [Splash Screen](https://ionicframework.com/docs/native/splash-screen/)
```
$ ionic cordova plugin add cordova-plugin-splashscreen
$ npm install --save @ionic-native/splash-screen
```