### Show network hardware
```
lshw -c network –businfo
```

### Enable SR-IOV
```
echo <num_vfs> > /sys/class/net/<device name>/device/sriov_numvfs
```

### Intel SR-IOV article
[SR-IOV](https://software.intel.com/en-us/articles/sr-iov-and-dpdk-hands-on-labs)
