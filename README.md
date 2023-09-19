# teslafi-grafana
This project builds upon a tutorial written by Matt Stewart from Grafana Labs.  Matt wrote an excellent tutorial that shows how to use a local Prometheus instance along with Teslafi to capture metrics and send them to a remote instance of Prometheus via remote-write to Prometheus instance hosted in GrafanCloud.  The tutorial can be found here: https://grafana.com/blog/2022/06/02/how-to-monitor-a-tesla-with-grafana-cloud/

Once setup, you'll need to build your own Grafana dashboard or you can use the JSON file found in this Github repository.  The JSON file leverages the geomap panel with Route (beta) to plot you're Tesla's position every 20 seconds.  Be sure to modify your prometheus.yml file from 120 seconds to 20 seconds.  Doing so will generate a better route map which especially useful on shorter drives.

Enjoy!

Shameless Plug: Sign up for access to Teslafi using this link: https://www.teslafi.com/signup.php?referred=bogdan
