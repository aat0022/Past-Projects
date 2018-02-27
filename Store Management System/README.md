# Store Management System

This was a system I worked on creating in my Software Modeling class in 
Fall 2017. It uses a Model-View-Controller architecture, and includes use of the
Proxy and Builder patterns, as well as a server-client structure set up for use
together on a local system. The server side makes calls to a local MySQL 
database, using the "StoreManagement" schema, and sets up that schema and 
relevant tables if none exists. It is possible for this system to run on two
separate computers with modification of the properties files and with the
proper files present on each computer.
