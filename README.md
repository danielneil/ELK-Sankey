# ELK-Sankey

<p align="center">
  <img src="https://github.com/danielneil/ELK-Sankey/blob/main/sankey-demo.JPG?raw=true">
</p>

Demo of a Sankey diagram (using the vega plugin) as Kibana dashboard, using data generated from makelogs. 

These [Instructions](https://www.elastic.co/blog/sankey-visualization-with-vega-in-kibana) to configure the dashboard were loosely followed.

Vega [configuration file](https://github.com/danielneil/ELK-Sankey/blob/main/vega-code.json) for kibana dashboard configuration.

# Setup

1. Prepare a vanilla Rocky Server (or a RHEL) with VirtualBox ([help](https://kifarunix.com/install-rocky-linux-8-on-virtualbox/)).

2. Install ansible ([help](https://www.how2shout.com/linux/how-to-install-ansible-on-rocky-linux-8-or-almalinux/)).

3. Install Git ([help](https://tastethelinux.com/2021/08/06/how-to-install-git-on-rocky-linux-8-ec2-aws/)).

4. Open a terminal, and run:
```
git clone https://github.com/danielneil/ELK-Sankey.git && cd ELK-Sankey && ./build.sh
```
5. Navigate to http://kibana-server-ip:5601 (web credentials are sankey/sankey).
