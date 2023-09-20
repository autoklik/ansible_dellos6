* The Ansible modules here has been tested on the following Dell Switch models: N1000, N2000, N3000, N4000, PowerConnect

* Follow the guide below on how to install Dell collections on RHEL based OS.

* Install Dell collections (do not use sudo)
    * ansible-galaxy collection install dellemc.os6
    * ansible-galaxy install dell-networking.dellos-copy-config (optional)
    * ansible-galaxy install dell-networking.dellos-image-upgrade (optional)
  
