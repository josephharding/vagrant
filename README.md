
## THIS REPO IS ABANDONED - MAYBE USFUL FOR PACKER, BUT PROBABLY NOT

clear old vagrant dirs.. major source of bugs!

```
rm -rf ~/.vagrant.d
rm -rf vagrant_files/ps-dev-0/.vagrant
```

build vagrant image:
```
packer build ubuntu1604.json
```

up vagrant instance:
```
cd vagrant_files/ps-dev-0
vagrant up
```

destroy vagrant after user:
```
vagrant destroy -f
```
