# Am I local?

The goal of this exercise is to figure out whether a domain name
is being resolved locally, through your `/etc/host` file.

Create a simple bash file, called `am-i-local.sh` that you can
execute by passing a domain name to it, ie. `./am-i-local.sh google.com`:
the script should be able to tell you if the domain name is being
resolved locally or not. If so, output the IP address it resolves to,
something like:

```
./am-i-local.sh google.com
google.com resolves to 127.0.0.1 through your hostfile

./am-i-local.sh non-local.com
definitely not
```
