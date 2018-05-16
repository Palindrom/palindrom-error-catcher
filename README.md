# &lt;palindrom-error-catcher&gt; [![Build Status](https://travis-ci.org/Palindrom/palindrom-error-catcher.svg?branch=gh-pages)](https://travis-ci.org/Palindrom/palindrom-error-catcher)

---

> Handles palindrom-client disconnection events and creates the needed UI to give the user control over them

Custom Element that binds with [palindrom-client](https://github.com/Palindrom/palindrom-client) connection events and shows a simple UI that allows the user to interact with the events. It is can be used as an example of designing your own error-preseting UI.

Please check the code at `palindrom-error-catcher.html` file to see how events are handled. 

# Creating your own

If you want to gain control over the appearance of your errors UI. You can fork this element, put it in the `wwwroot/sys/` folder of your app. And edit it as desired. Once you have an element in this folder with the same name, it will supersede the default one and your UI will be shows. 