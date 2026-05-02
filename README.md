# My Solutions to OTW's Bandit games. 

These are not writeups. Only direct solutions are here.

### Level 24 -> 25
<details>
	<summary>Solution?</summary>

```bash
$ cd $(mktemp -d)
$ for i in {1000..9999}; do echo "{password for bandit24} $i" >> f; done
$ nc -v localhost 30002 < f
```
<details>
    <summary>Password</summary>

`iCi86ttT4KSNe1armKiwbQNmB3YJP3q4`
</details>
</details>

### Level 25 -> 26
<details>
	<summary>Solution?</summary>

1. Decrease terminal height to only 3~4 lines

2. Connect to bandit26. Since `more` is basically your shell right now, it'd pause because of the small window height.

3. Press `v` to open vi

4. Enter `:set shell=/bin/bash`

Congrats. You have now accessed the shell for level 26. 

NOTE: 
To ssh into bandit26, you can either use the password or copy the bandit26.sshkey file to your system and use the `-i` flag with ssh while logging in. 

<details>
    <summary>Password</summary>

`s0773xxkk0MXfdqOfPRVr9L3jJBUOgCZ`
</details>
</details>