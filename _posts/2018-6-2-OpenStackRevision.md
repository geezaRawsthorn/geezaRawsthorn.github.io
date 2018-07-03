---
layout: post
title: OpenStack Training
---

Commands

- openstack stack list (deployed stacks in your tennancy)
- openstack flavor list -- show potential flavours.
- openstack image list -- show list of images.

References / Tutorials

https://www.stratoscale.com/blog/openstack/best-practices-openstack-heat-templates/

OS::Neutron::SecurityGroup

A resource for managing Neutron security groups. Security groups are sets of IP filter rules that are applied to an instance’s networking. They are project specific, and project members can edit the default rules for their group and add new rules sets. All projects have a “default” security group, which is applied to instances that have no other security group defined.

![_config.yml]({{ site.baseurl }}/images/Screen Shot 2018-07-03 at 16.00.13.png)

OS::Neutron::Subnet¶
A resource for managing Neutron subnets.

A subnet represents an IP address block that can be used for assigning IP addresses to virtual instances. Each subnet must have a CIDR and must be associated with a network. IPs can be either selected from the whole subnet CIDR, or from “allocation pools” that can be specified by the user.
