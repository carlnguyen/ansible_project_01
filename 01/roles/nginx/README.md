# Transport traffice from 80 to 3000 #
## Adding nginx config template ##

 - template path: nginx/templates/nginx.conf.j2

### Config ansible roles to copy template from ansible to current nginx config on server ###

 - main config: nginx/tasks/main.yml
 - handlers config: nginx/handlers/main.yml