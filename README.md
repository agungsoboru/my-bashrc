# my-bashrc
```
export PROMPT_COMMAND='RETRN_VAL=$?;logger -p local6.debug "$(whoami) [$$]: $(history 1 | sed "s/^[ ]*[0-9]\+[ ]*//" ) - from $(echo $SSH_CONNECTION | awk "{print \$1}")"'
```
my-bashrc
