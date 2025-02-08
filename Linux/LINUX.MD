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