## react-desktop-notification

Compatible with React v16.

## install
```
	npm install --save react-desktop-notification
	OR
	yarn add react-desktop-notification

```

## usage
```
import Notifier from "react-desktop-notification"

gotNewNotification(){
  ...
  //Here will pop a notifier and always open in a new window when clicked.
  Notifier.start("Title","Here is context","www.google.com","validated image url");

	//Here will pop notifier and open in a specified name window "popwin1" when clicked.
	Notifier.start("Title","Here is context","www.google.com","validated image url","popwin1");

	//Here will pop notifier and focus parent window only when clicked.
	Notifier.focus("Title","Here is context","www.google.com","validated image url");
	...
}

```
## API
`Notifier.start(notifier_title, notifier_context, opening_url, icon_url, window_name)`

`Notifier.focus(notifier_title, notifier_context, opening_url, icon_url)`

## git

https://github.com/applebaum/React-Desktop-Notification.git
