# puppet-slurm

Puppet module for SLURM client and server

## TODO

* master - require NFS or somehow ensure NFS present before applying mount resource
* slurmdbd - unit test config file
* Slurmdbd - manage MySQL and other supported 'StorageType' values
* Add acceptance tests using beaker
* Notify Service resources when corresponding config changes
