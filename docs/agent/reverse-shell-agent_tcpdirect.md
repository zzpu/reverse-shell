## reverse-shell-agent tcpdirect

Agent that listens for commands on a local port

### Synopsis

Agent that listens for commands on a local port

```
reverse-shell-agent tcpdirect [flags]
```

### Examples

```
You can connect to it using netcat:
# On the agent (1.2.3.4)
$ reverse-shell-agent tcpdirect --port 7777

# On the client
$ nc 1.2.3.4 7777

```

### Options

```
  -h, --help          help for tcpdirect
      --host string   local address to listen to (default "0.0.0.0")
      --port int32    local port to listen to (default 8080)
```

### Options inherited from parent commands

```
  -v, --verbose int   Be verbose on log output
```

### SEE ALSO

* [reverse-shell-agent](reverse-shell-agent.md)	 - A Go agents listening for remote commands

