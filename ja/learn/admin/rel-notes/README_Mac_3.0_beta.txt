Couchbase Server 3.0.0 BETA, Mac OSX

Couchbase Server is a distributed NoSQL document database for interactive applications. 
Its scale-out architecture runs in the cloud or on commodity hardware and provides a 
flexible data model, consistent high-performance, easy scalability and always-on 
24x365 availability. 

This release contains major enhancements and bug fixes. 
For more information, see the Couchbase Server Release Notes.

REQUIREMENTS

- If you have a previous installation of Membase/Couchbase, 
  see the 2.5 documentation for removing the Couchbase Server: 
  http://docs.couchbase.com/couchbase-manual-2.5/cb-install/#mac-os-x-installation

INSTALL

Instructions: 

- By default, Couchbase Server is installed at: 
  "/Applications/Couchbase Server.app/Contents/Resources/couchbase-core/bin/"

- After installation, a Couchbase Server icon appears in the menu bar on the 
  right-hand side. 

- The server automatically starts after install and is available on 
  port 8091 (default).


Note: 

For Mac OSX 10.8+, if your security level is set to Anywhere. you can run the server. 
If your security level is higher, you will not be able to open Couchbase Server 
due to lack of a valid developer certificate. If this occurs:

1. Hold down the Control key and click the application icon. 
   From the contextual menu, choose Open.

2. A popup appears asking you to confirm this action. 
   Click the Open button.
 

ADDITIONAL

- For a full list of network ports for Couchbase Server, see the 2.5 documentation: 
  http://docs.couchbase.com/couchbase-manual-2.5/cb-install/#network-ports

- To read more about Couchbase Server best practices, see the 2.5 documentation: 
  http://docs.couchbase.com/couchbase-manual-2.5/cb-admin/#best-practices
