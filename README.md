SSH Local
=========
SSH Local is a tool that lets you SSH on your local network without having to
restate the full network address every time. It is configured through a file
called `'.sshl.json'` in home directory of the running user.

Example using regular ssh:
```bash
ssh remote-user@192.168.0.123
```

Achieving the same thing using **sshl** with network address configured to
`"192.168.0"`:
```bash
sshl remote-user@123
```
