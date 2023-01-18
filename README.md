# ssh-keep-alive
How to keep Your ssh session online

## How to:
1. Put file config inside of `~/.ssh/` dir

## How it works:
Ssh sends keep-alive packets to server every 4 minutes. This way we keep saing server "hey im still using this connection, don't kill me"
