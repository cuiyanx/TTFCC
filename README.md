# TTFCC
Test tool for check chromium code.

## Install

```sh
$ npm install
```

if `npm install chromedriver` is fail, you can install `chromedriver` by manual.

```sh
$ npm install chromedriver --chromedriver_cdnurl=http://cdn.npm.taobao.org/dist/chromedriver
```

## Start

```sh
$ npm start
```

if testing on android device, need `adb` tool.

## Set TTFCC.config.json file

* `andriod`: As *false*, no testing `andriod`, As *true*, testing `andriod`.
* `chromiumPath`: Path of chromium browser on run platform (mac or linux).

## Support platform

| Run Platform  | Ubuntu 16.04 |    Mac    |  android  |
|     :---:     |     :---:    |   :---:   |   :---:   |
| Ubuntu 16.04  |     pass     |     N/A   |    pass   |
|      Mac      |      N/A     |    pass   |    pass   |

## Result html

![result-html](./baseline/result-html.jpg)
