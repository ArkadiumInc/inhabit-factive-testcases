`FT_B_02_BrokenURLs`
=========================

List broken URLs requested by Factive
-------------------------------------

> Category: Base

***

### Preconditions
 - Factive is available to load through the Internet
 - WidgetApp is able to load Factive

***

### Actions
 - Start WidgetApp configured to use Factive with default configuration
 - Intercept failed requests executed by Factive

***

### Postconditions
 - Expect Failed Requests Count are equal to **0**