# ELK-Sankey

Demo of a Sankey diagram within a Kibana dashboard - shows carbon emissions per country 

# Environment - Setup

1. Prepare a vanilla Rocky Server (or a RHEL) with VirtualBox ([help](https://kifarunix.com/install-rocky-linux-8-on-virtualbox/)).

2. Install ansible ([help](https://www.how2shout.com/linux/how-to-install-ansible-on-rocky-linux-8-or-almalinux/)).

3. Install Git ([help](https://tastethelinux.com/2021/08/06/how-to-install-git-on-rocky-linux-8-ec2-aws/)).

4. Open a terminal, and run:
```
git clone https://github.com/danielneil/ELK-Sankey.git && cd ELK-Sankey && ./build.sh
```
5. Navigate to http://kibana-server-ip:5601 (web credentials are sankey/sankey).

# Sankey Configuration
 
## Configuration Instructions  
https://www.elastic.co/blog/sankey-visualization-with-vega-in-kibana
  
## Data Ingest 
