```
{{if hasRoleName "MOD ROLE HERE"}}{{$args := .Args}}
{{range $i, $v := $args}}{{if ne $i 0}} :mute: **User: {{$v}}** {{exec "mute" $v "MUTE TIME" "REASON"}}
{{end}}{{end}}

**:warning:Role Detected: MOD ROLE HERE :heavy_check_mark:**

{{else}}**:warning:Missing Role: MOD ROLE HERE :x:**{{end}}
```

**__Personalize:__**
Replace **MOD ROLE HERE** with the role that will be allowed to use the command, replace **MUTE TIME** with the mute duration in minutes,
replace **REASON** with the reason why the user will always be mute by this command. **(DONT REMOVE THE quoutes! {""})**

**__Dependancies:__**
Requires that the mute command is turned on, requires the correct mute role setup and requires the mod role to be setup within the command
above.
