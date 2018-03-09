# Nuke

## Trigger Type:
Command

## Trigger:
nuke

## Response:
```{{if hasRoleName "*"}} {{exec "clean" "100"}} {{exec "clean" "100"}} {{exec "clean" "100"}} {{exec "clean" "100"}} **Channel Nuked By: <@{{.User.ID}}>** {{else}} You don’t have permission! {{end}}```

NOTE: You will need to give the people you want to use this command a role named `*`.
