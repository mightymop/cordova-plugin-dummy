# Android:

### 1. Add plugin
cordova plugin add https://github.com/mightymop/cordova-plugin-dummy.git
### 2. For Typescript add following code to main ts file: 
/// &lt;reference types="cordova-plugin-dummy" /&gt;<br/>
### 3. Usage:
```
window.dummy.hello_world(params,succescallback,errorcallback);

