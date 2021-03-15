# script 


with this script you can ssh into many esxi hosts. 

Place hosts into server.txt.

To get all esxi host from all cluster on vcenter you can use this powercli commands.
```
Get-Cluster | Get-VMHost | Select-Object Name 
```


Place command you want to send between '' after ssh -t $USER@mgmt.basefarm.net@$server ''

```
 sshpass -e ssh -t $USER@mgmt.basefarm.net@$server 'hostname && esxcli software vib list | grep qlnativefc && echo "---" ' >> rapport_esxi #
```

links:

https://www.redhat.com/sysadmin/ssh-automation-sshpass
