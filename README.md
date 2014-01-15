VMWare Template
===============

Random stuffs to build a custom Ubuntu iso inside a vagrant box.

```bash
# Setup the env (downloads iso and runs vagrant up)
./setup_env.sh

vagrant ssh
sudo su
./iso/build_iso.sh
```

Currently only has seed file for installing Ubuntu with Chef 11.8.

TODO
----
* Would be nice if you could pass parameters to drop in bootstrap files
* Add support for a network install
