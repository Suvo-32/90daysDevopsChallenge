# Project: DevOps Linux Server Monitoring & Automation

## Tasks 1 - User & Group Management

i have created four users using - 
                                  sudo useradd -m babitaji -s /bin/bash
                 
                                  sudo useradd -m tappu -s /bin/bash

                                  sudo useradd -m jetha -s /bin/bash

                                  sudo useradd -m aiyer -s /bin/bash

create a new group using - 
                           sudo group add devops 

Then i add users in the group like - 

                          sudo gpasswd -M tappu,babitaji devops

Then i add another user in the same group like - 

                         sudo usermod -aG devops aiyer          

## Task 2 - File & Directory Permissions

### we can edit  any file-folder access permission  using "chmod"
                                    ex - chmod 777 text.txt 

### we can edit  any file-folder ownership permission  using chown
                                    ex - chwon aiyer demo.txt 

### we can edit  any file-folder group  ownership permission  using chown
                                    ex - chgrp devops demo.txt                                                             