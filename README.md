# openstack-rally-templates
Rally Templates for OpenStack Performance Testing

# Steps for executing

```
git clone https://github.com/alokjani/openstack-rally-templates.git
cd openstack-rally-templates/
```

Ensure that "net-id" and "floating_network" are correctly setup for Nova tests `nova-all.json`

```
rally task start ~/openstack-rally-templates/nova-all.json
```
