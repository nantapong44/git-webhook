# git-webhook

## On Server
1.Create git bare Folder on Server to get web-hook from deploy. (eg. /var/repo/nantapong44.git/)  
2.Use git init --bare in that folder.  
3.nano ./hooks/post-receive  
4.copy Bash script from above into it.  
5.Add execute to post-receive file (chmod +x)  

## On Local
1.Add remote url to destination folder on server. (eg. "ssh://root@xxx.xxx.xxx/var/repo/nantapong44.git)