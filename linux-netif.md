### Show network hardware
```
lshw -c network –businfo
```

### Enable SR-IOV
```
echo <num_vfs> > /sys/class/net/<device name>/device/sriov_numvfs
```
