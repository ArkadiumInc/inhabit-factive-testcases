`FT_B_01_DefaultConfig`
=========================

Start with default configuration
--------------------------------

> Category: Base

***

### Preconditions
 - Factive is available to load through the Internet
 - WidgetApp is able to load Factive

***

### Actions
 - Start WidgetApp configured to use Factive with default configuration
 - Subscribe to `presenter.content` event

***

### Postconditions
 - Expect `presenter.content` event to fire within 10 seconds