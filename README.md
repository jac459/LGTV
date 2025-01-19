# LGTV

If your remote can't display the pics by default in the remote:
1 - use the alternate LGTV.json (you can rename it as LGTV.json).
2 - if your meta is not running in the same server than the node-red, modify the line 36 and replace in "URLConverter":"http://$MetaIP:1880/LGPics?url=", the $MetaIP by the actual IP of your node-red.
3 - import the node-red script (using palette button in node-red) in your node-red server. This will create a very small web server that will query your LG TV, ignore the certificate errors and forward the result to your remote. The "alternate JSON" is just there to use this mini-server.

Have fun.
            
