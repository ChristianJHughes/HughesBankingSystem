# HughesBankingSystem
<b>A banking simulation emulating a distributed, multi-threaded network. Created in C#.</b>

This program implements the architecture necessary for a distributed banking platform. It allows for multiple instances of a "Teller" interface, and multiple instances of an "ATM" interface. Each ATM/Teller instance occupies a seperate thread, with software locks preventing any potential race conditions. 

Class structure embodies MVC architecture, with a database model that supports quick look-ups and large data sets.

<b>Use</b>
The teller can create and delete customer accounts. ATM's can easily request account information or perfrom withdrawls.

![Banking Screenshot](http://i.imgur.com/xbq8FVt.png "Banking Screenshot")
