# Repeat

## Trigger Type:
Command

## Trigger:
repeat

## Response:
No case-sensitivity: ```{{.StrippedMsg}}```
Case-sensitivity: ```{{range $k, $v := .Args}}{{if ne $k 0}}{{.}} {{end}}{{end}}```
