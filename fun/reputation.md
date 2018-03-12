# +rep / -rep

## Trigger Type:
Starts with

## Trigger:
+rep / +rep

## Response:
+rep: ```{{if gt (len .Args) 1}}{{exec "giverep" (index .Args 1)}}{{else}}Please specify a user{{end}}```
-rep: ```{{if gt (len .Args) 1}}{{exec "takerep" (index .Args 1)}}{{else}}Please specify a user{{end}}```
