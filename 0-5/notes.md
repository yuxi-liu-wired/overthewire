# Notes for Levels 0--5

## 0

```ssh
Host bandit
    HostName bandit.labs.overthewire.org
    Port 2220
    ForwardAgent yes
```

Then run `ssh bandit0@bandit` would get it working. You can't put the password into the config file so you have to input it manually. Look up on `ssh config` to figure out what the settings mean.

Get the file by secure remote copy.

```bash
> scp -P 2220 bandit0@bandit.labs.overthewire.org:/home/bandit0/readme .
> cat readme
```

## 1--4

Weird filename but okay. It's a dashed filename so it must be referred to like `./-`.

bandit5@bandit lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR


