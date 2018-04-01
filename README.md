# MMM-FMI 

A MagicMirror module that beeps your iPhone and tells you its location

## Examples

You are presented with an iPhone image

![](iphone.png)

When clicked, it gives you an alert window. Read the alert and click OK.

Then you are present with the location of your iPhone and the distance, while beeping the iPhone itself.

![](iphone2.jpg)

Click "Reset this module" and only the iPhone icon remains, ready for the next time you need to find your iPhone.

* Uses very little of your precious mirror real estate. Fits anywhere!

## Installation

* `git clone https://github.com/mykle1/MMM-FMI.git` into the `~/MagicMirror/modules` directory.

* `cd MMM-FMI`

* `npm install`

## Add to Config.js

    {
            disabled: false,
            module: 'MMM-FMI',
            header: "",
            position: 'bottom_center',
			config: {
                email: "Your iCloud email address",
                pass: "Your iCloud password",
                lat: "40.111111", 
                lon: "-74.111111",
                maxWidth: "400px",
			}
        },

## Mad props!

This was originally cowboysdude's module/idea. For whatever reason, he lost interest in developing it.
With his permission and generosity, I completed the module and am passing it off as my own. :-)