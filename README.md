# http-server-indexed
Wrapper for http-server node module that creates an index page for all running http-servers

To use:
Must install node http-server module as global.
Run startIndexServer to start the index server on port 8080.
Call http-server-indexed instead of http-server to start http-servers.
For http-server-indexed, the -p or --port option is mandatory.
Visit <address>:8080 to see the current list of http-server instances running
  as well as the path name they are running in.
