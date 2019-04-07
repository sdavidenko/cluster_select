# k8s cluster select 

1) `chmod +x profilek8s`

2) copy profilek8s.sh to folder in $PATH  
   ``
3) make folder in you home directory '.profilek8s' 
   ` mkdir ~/.profilek8s && cp config.conf`

4) edit file config.conf with adding profiles 
   ` nano ~/.profilek8s/config.conf `

5) make alias in you bashrc ` echo "alias k8s_select='.  profilek8s' " >> ~/.bashrc`

reopen bash or invoke new bash with 'bash' in terminal

usage:  `k8s_select profile_name`  
