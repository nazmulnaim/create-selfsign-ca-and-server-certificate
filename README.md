# create-selfsign-ca-and-server-certificate

Step 01: 

$ ./generate-root-ca

Step 02:

$ ./generate-server-ca

To change Root CA name line no. 36-43 of `root.conf`

To change domain conf for the tls certificate change line no. 8 of `ext.conf` and line no. 40-46 of `server.conf`
