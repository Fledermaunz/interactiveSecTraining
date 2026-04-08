## Dancing
SMB - Server Message Block  
Port 445
shares: smbclient -L //<IP> -N
enter share: smbclient //<IP>/<SHARE> -N  
ls -> cd -> get  

## Redeemer
redis-cli -h <IP>  -> info -> keys * -> GET flag (wrongly typed select 2 after keys, to solve this just exit by select 0)
