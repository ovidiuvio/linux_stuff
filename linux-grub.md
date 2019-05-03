https://www.thegeekdiary.com/centos-rhel-7-change-default-kernel-boot-with-old-kernel/

### Default config
```
vi /etc/default/grub
```

### Updated boot config
```
grub2-mkconfig -o /boot/grub2/grub.cfg
```

### Update UEFI boot config (Centos)
```
grub2-mkconfig -o /boot/efi/EFI/centos/grub.cfg
```

### Check boot params
```
cat /proc/cmdline
```
