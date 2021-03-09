# Export / import a bunch of vm definitions

```
for i in $(virsh list --all | awk '{print $2}'|grep -v Name);
  do
    virsh dumpxml $i > $i.xml
  done
  
 for f in *.xml; do virsh define $f; done
 ```
