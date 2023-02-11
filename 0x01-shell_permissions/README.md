Commands used for this project.
- su to switch user
- whoami
- chown
- touch
- chmod +x
- chmod u+rwx,o+x,g+x ./filename
- chmod --reference=some_file another file
- set permission to dir only: chmod -R a+X ./
- create dir and set permission: mkdir -m 751 -p ./dir
- change group: chgrp
- change owner and group of all file: chown owner:group *
- change owner if only: chown --from=current user new user filename
- change ownership of symbolic link: chown -h 

