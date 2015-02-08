---
layout: post
title:  Organizing DNS and Datanaut
summary: Buying a domain, registering IPs
date:   2015-01-29 00:07:00
category: site
tags: [dns, aws, route-53, IP]
thumbnail: https://s3-us-west-1.amazonaws.com/chrisrzhou/datanaut/posts/2015-01-29-organizing-dns-and-datanaut/thumbnail.png
---

Today, I spent a good 6+ hours working on learning how to register a domain and subdomains to other IP addresses.  I 
ended up deciding to organize my future sites with the `datanaut.io` domain.

I bought this domain on [AWS Route 53][] and researched about DNS and IPs, as well as rerouting your domains and 
sub-domains to other IPs and CNAMEs.

This will allow me to organize future subdomains in possibly this fashion:

```bash
# main domain
datanaut.io

# R shiny, D3 Visualization sub-domain
shiny.vis.datanaut.io
d3.vis.datanaut.io

# Jekyll blog sub-domain
chrisrzhou.datanaut.io
```

I also managed to get the Github pages registered to the `chrisrzhou.datanaut.io` subdomain by adding a `CNAME` file 
containing the desired domain name, and making sure that AWS Route 53 contains the registered `CNAME` entry pointing
to `chrisrzhou.github.io`.

I successfully learned and created AWS EC2 `Elastic IPs`, which allows for a  more permanent allocation of IP to the 
EC2 instance.  I wasn't aware that Public IPs in EC2s could be potentially reset if the server restarts, so this was 
helpful in organizing the site.

You can view the "re-routed" R Shiny Visualizations on EC2 [here][shiny ec2]

I might do a writeup on a guide for AWS Route 53 and AWS VPC sometime in the future :)

**BUT ALAS!** There is still a **LOT** of stuff left to do on this site.  I had to delegate some time to learning and
 organizing my other Github projects, and there's still work to be done with GRADE.


<!-- links -->
[aws route 53]: http://aws.amazon.com/route53/
[shiny ec2]: http://shiny.vis.datanaut.io/
