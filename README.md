# elastic-mtrupdate

by Thomas Tong ([thomastong.me](http://thomastong.me/))

Following a [workshop](https://github.com/elastic/hkoscon16) of ELK stack (Elastic search, Logstash, Kibana) in [HKOS Conf 2016](http://2016.opensource.hk/), I decided to try this on twitter [@mtrupdate](https://twitter.com/mtrupdate).

MTR Service Update ([@mtrupdate](https://twitter.com/mtrupdate)) is a voluntary service driven by Hong Kong MTR staffs, to report up-to-date railway disruptions information to its everyday users. Although Hong Kong MTR has official channels to broadcast these incidents, its speed and information completeness have made non-official channels widely popular.

After collecting the tweets, statistics regarding service disruptions can be computed and visualized.

This project is currently hosted on Azure:

- Kibana: (http://mtr.eastasia.cloudapp.azure.com:5601/)
- Elastic Search (http://mtr.eastasia.cloudapp.azure.com/twitter_elk_mtrupdate/_search/) (GET only)

Below are some data extractions done after running the stack for 3 days. Screenshots will be uploaded from time to time.

# Tweets about Delays

![Delay](https://raw.githubusercontent.com/thomasmktong/elastic-mtrupdate/master/screenshot/screencapture-0-0-0-0-5601-app-kibana-1467985548483.png)

# All tweets

![All](https://raw.githubusercontent.com/thomasmktong/elastic-mtrupdate/master/screenshot/screencapture-0-0-0-0-5601-app-kibana-1467985520669.png)
