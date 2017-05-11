`FT_01_ProtocolSwitching`
=========================

List URLs loaded with fixed protocol
------------------------------------

> Category: Fault Tolerance

***

### Preconditions
 - Factive is available to load through the Internet
 - WidgetApp is able to load Factive

***

### Actions
 - Start WidgetApp configured to use Factive with default configuration using `http` protocol
 - Count `https` URLs requested by Factive
 - Start WidgetApp configured to use Factive with default configuration using `https` protocol
 - Count `http` URLs requested by Factive

***

### Postconditions
 - Expect both `http` and `https` requests to be equal to **0**