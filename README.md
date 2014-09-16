Neworking info
==============

Cross-platform WIFI information for Cordova / PhoneGap.

Follows the [Cordova Plugin spec](http://cordova.apache.org/docs/en/3.0.0/plugin_ref_spec.md), so that it works with [Plugman](https://github.com/apache/cordova-plugman).

### 1. Supported Platforms

- Android
- WP8
 

### 2. Usage

    networkinfo.wifistatus(function(result) {
            console.log("result = " + result);
        }, function() {
            console.log("error");
        });

