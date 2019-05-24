https://elinux.org/Debugging_by_printing

### Show log levels
```
cat /proc/sys/kernel/printk
```

### Change log levels
```
echo 8 > /proc/sys/kernel/printk
```

```
# set console_loglevel to print KERN_WARNING (4) or more severe messages
dmesg -n 5
```

