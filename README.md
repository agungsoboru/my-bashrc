# my-bashrc
```
export PROMPT_COMMAND='RETRN_VAL=$?;logger -p local6.debug "$(whoami) [$$]: $(history 1 | sed "s/^[ ]*[0-9]\+[ ]*//" ) - from $(echo $SSH_CONNECTION | awk "{print \$1}")"'
```
[https://docs.agungsurya.my.id/log%20all%20executed%20command%20by%20user/](https://docs.agungsurya.my.id/log%20all%20executed%20command%20by%20user/)

```
Apr 24 08:57:00 hexadecimal agungsurya: agungsurya [170618]: sudo nano /etc/ssh/sshd_config - from 223.255.228.101
Apr 24 08:57:06 hexadecimal agungsurya: agungsurya [170618]: sudo systemctl restart sshd - from 223.255.228.101
Apr 24 08:57:09 hexadecimal agungsurya: agungsurya [170618]: sudo systemctl restart ssh - from 223.255.228.101
Apr 24 08:57:57 hexadecimal agungsurya: agungsurya [175573]: tmux attach-session -t 1 - from 142.202.243.83
Apr 24 08:58:00 hexadecimal agungsurya: agungsurya [175573]: pwd - from 142.202.243.83
Apr 24 08:58:03 hexadecimal agungsurya: agungsurya [175573]: ls - from 142.202.243.83
Apr 24 08:58:07 hexadecimal agungsurya: agungsurya [170618]: whomai - from 223.255.228.101
Apr 24 08:58:13 hexadecimal agungsurya: agungsurya [170618]: whoami - from 223.255.228.101
Apr 24 08:58:25 hexadecimal agungsurya: agungsurya [175573]: ping 8.8.8.8 - from 142.202.243.83
Apr 24 08:58:30 hexadecimal agungsurya: agungsurya [170618]: curl google.com - from 223.255.228.101
```

my-bashrc
