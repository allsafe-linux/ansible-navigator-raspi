# ansible-navigator-raspi  
RHCA-DO374-ansible-navigator-raspi  
  
controller in VM, rhel-8.9-x86_64-dvd.iso  
raspi use four raspberrypi 4B, RockyLinuxRpi_8-latest.img.xz  
  
ansible-navigator run ping-all.yml  

Result Host                     Number Changed Task                            Task action          Duration  
 0│Ok     controller.allsafe.local      0 False   Gathering Facts                 gather_facts               3s  
 1│Ok     raspi01.allsafe.local         1 False   Gathering Facts                 gather_facts               4s  
 2│Ok     raspi02.allsafe.local         2 False   Gathering Facts                 gather_facts               4s  
 3│Ok     raspi03.allsafe.local         3 False   Gathering Facts                 gather_facts               4s  
 4│Ok     raspi04.allsafe.local         4 False   Gathering Facts                 gather_facts               4s  
 5│Ok     controller.allsafe.local      5 False   Test the connectivity to each seansible.builtin.ping       1s  
 6│Ok     raspi01.allsafe.local         6 False   Test the connectivity to each seansible.builtin.ping       2s  
 7│Ok     raspi02.allsafe.local         7 False   Test the connectivity to each seansible.builtin.ping       2s  
 8│Ok     raspi03.allsafe.local         8 False   Test the connectivity to each seansible.builtin.ping       1s  
 9│Ok     raspi04.allsafe.local         9 False   Test the connectivity to each seansible.builtin.ping       1s  
