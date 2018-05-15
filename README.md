# FreeNAS Custom Exporter

I am trying to create a custom exporter for use in FreeNAS as the node_exporter does not send the correct CPU temperature (currently).  You may find my troubleshooting in these, and a few other, links:
https://groups.google.com/forum/#!topic/prometheus-users/MjA77maIz5o
https://github.com/prometheus/node_exporter/issues/945

This will be the base code.  Once I get this working I hope to add in temp metrics for the drives, then anything else I or the FreeNAS community wishes.  I have a working shell script for the temperatures and know the FreeNAS community has quite a few more scripts that can be translated over to Go or to otherwise work with Prometheus for a more sophisticated/fun monitoring system.  Any guidance, advice, etc you have is welcome.  All questions welcome too!

Status: Compiles, I believe with dependencies, but does not run as descriped in the google groups thread.  Not sure what is missing, but I will keep playing around with it.