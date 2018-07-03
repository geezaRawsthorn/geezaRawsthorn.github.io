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
