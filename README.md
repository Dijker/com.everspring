### Everspring

This app adds support for Everspring devices.

Supported devices:

- Everspring AD146 (In-wall dimmer)
- Everspring AD147 ( Dimmer plug )
- Everspring AD142(2) ( Dimmer plug )
- Everspring AN157 ( On/Off plug )
- Everspring AN158 ( On/Off plug with power metering)
- Everspring AN179 ( On/Off In-wall plug) [ BETA ]
- Everspring AN180 ( On/Off plug )
- Everspring AN181 ( On/Off plug with power metering)
- Everpsring HSM02-1 ( Door/window detector )
- Everspring HSP02 ( PIR motion sensor )
- Everspring SF812 ( Smoke detector )
- Everpsring SM103 ( Door/window detector )
- Everspring SP103 ( PIR motion sensor )
- Everspring / Nexa SP816 ( PIR motion sensor [ BETA] )
- Everspring ST812 ( Water alarm detector ) [ BETA ]
- Everspring ST814 ( Temperature & Humidity sensor )

Central discussion/support/request topic: https://forum.athom.com/discussion/2418/

### Donate

If you like the app, consider a donation to support development  
[![Paypal donate][pp-donate-image]][pp-donate-link]

### ToDo

- Add more Everspring devices -- support from community needed!

### Known bugs/limitations

- [Removed in 0.1.6] SP103 : Tamper alarm will not work
- ST814 sensor doesn't always work as expected. Debugging ongoing to get it more reliable

### Unknown bugs

Yes ;-)

### Changelog

- V0.2.4 2018-03-05 : HSM02-1 added (*by Ilya Gitlin*)
- V0.2.3 2017-12-01 : AD146 added (*by Jonas L, thanks to John L for testing*)
- V0.2.1 2017-04-06 : SM103 added (code by Rebtor )
- V0.2.0 2017-04-23 : SF812 added (code by Rebtor)
- V0.1.9 2017-03-26 : SP103 bugfix to report motion again
- V0.1.8 2017-03-22 : Bugfixes mainly for AD1422 & SP103 crashes
- V0.1.7 2017-03-12 : Add AN157, inclusion of updated zwave driver
- V0.1.6 2017-01-13 : Add HSP02 battery level (repair needed)
- V0.1.6 2017-01-08 : Various fixes and cleanup.
- V0.1.5 2017-01-07 : AD147 dimmer settings in flow now working
- V0.1.4 2016-12-14 : AD1422 configuration settings removed ( not available ), bugfixes
- V0.1.3 2016-12-13 : Add support for SP814 ; ( SP814 on loan provided by Robbshop )
- V0.1.2 2016-12-13 : Add support for SP103 ; ( SP103 on loan provided by Robbshop )
- V0.1.1 2016-12-12 : Add support for AN158 ; update Zwave driver ( AN158 on loan provided by Robbshop )
- V0.1.0 2016-10-21 : Add support for AD1422 ; ( AD1422 on loan provided by Rozz )
- V0.0.3 2016-10-04 : Add support for various powerplugs (Alexander)
- V0.0.2 2016-08-12 : Add support for HSP02 motion sensor (Robin van Kekem)
- V0.0.1 2016-08-02 : First test release on Github

[pp-donate-link]: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=ralf%40iae%2enl&lc=GB&item_name=homey%2deverspring&item_number=homey%2devohome&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted
[pp-donate-image]: https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif
