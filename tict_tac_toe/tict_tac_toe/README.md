# Firefox and Google Chrome extension

## Displays a large (customizable) clock in default new tab and can set alarms (with sound, if you want) that is fired **inclusive when this tab is closed**. In addition, it allows to open a url in a new tab when the alarm is fired.

* View default:

![Default view](res/img/example1.png)

* Configuration view:

![Configuration view](res/img/example2.png)

* Sound configuration view:

![Sound configuration view](res/img/example3.png)

* Alarm fired view (imagine with sound, if you set 'yes' in configuration):

![Red color. Alarm fired view](res/img/example4.png)
![Yellow color. Alarm fired view](res/img/example5.png)

* The red and yellow colors is alternate each second, during five seconds.
* The alarm sound is heard for five seconds.
* The notification is seen for five seconds. If you click on it, it will hide.

## How to try this extension

### Firefox

You can install this add-on in ["Alarms & Clock"](https://addons.mozilla.org/en-US/firefox/addon/alarms-clock/)

### Google Chrome

This extension is not in the Chrome Web Store, but you can try it.

* [Download package](https://github.com/lmfresneda/clock-alarm-extension/archive/master.zip) and decompress it.
* In Google Chrome, go to `chrome://extensions/` page and check `Developer mode`:

![Developer mode check](res/img/install1.png)

* Press button `Load unpacked extension` and select uncompressed folder extension.
* The extension is now visible in list:

![List extensions](res/img/install2.png)

* And the icon is visible in toolbar:

![Icon toolbar](res/img/install3.png)


### Google Chrome security

For our security, Chrome asks us if we want to use this extension, because it's loaded by developer mode:

![Question for the first time](res/img/install4.png)

Press `Keep changes` button, if we want to try this extension, obviously.


NOTE: This extension does not require special permissions (only notifications, but no is absolutely necessary).