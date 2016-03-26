gaeutilities is a collection of classes to aid in development on Google Appengine.

The stable version includes the following classes.

Session: An http session class to preserve identity across http requests. It uses both BigTable and Memcache for performance and reliability. It also includes middleware to plug in with django.

Cache: A BigTable and Memcache caching class. Any object that can be pickled can be stored in cache.

Event: A subscribe/fire event system that gives developers the ability to set callback functions.

Flash: A cookie based messaging library. Using json, data structures can be stored as a cookie in the browser and retrieved on the next request. Useful for messages such as "Thank you for logging in."

[![](https://www.paypal.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=E5MG75QK4DNPQ&lc=US&item_name=gaeutilities&item_number=gaeutilities&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

[Follow me on Twitter](http://twitter.com/joerussbowman)

&lt;wiki:gadget url="http://www.ohloh.net/p/25762/widgets/project\_cocomo.xml" height="240"  border="0" /&gt; &lt;wiki:gadget url="http://www.ohloh.net/p/25762/widgets/project\_basic\_stats.xml" height="220"  border="1" /&gt;