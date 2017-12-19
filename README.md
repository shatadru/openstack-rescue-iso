### openstack-rescue-iso

- This script can be used to rescue a nova instance using iso file.
- Usage :
~~~
rescue-boot <instance's domain name> <iso/file/path>
rescue-boot -r <instance's domain name> <backed up xml file>
~~~
- Options :
~~~
 -r / --revert : Revert changes
 -h / --help   : Show help
~~~

### In case of any issue use "nova reboot --hard UUID" to re-generate the instance's xml defination.
