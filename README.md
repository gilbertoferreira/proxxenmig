# proxxenmig
Proxmox Xen Mig

How to use? Read the file xva-conv.sh
<br>
Sample usage:
<br>
wget --http-user=x --http-password=y http://your.xen.server.host/export?uuid=<VM_UUID> -O - | tar --to-command=./xva-conv.sh -xf -
