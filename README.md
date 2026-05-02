# My Solutions to OTW's Bandit games. 

These are not writeups. Only direct solutions are here.

### Level 24 -> 25
<details>
	<summary>Solution?</summary>

1. `cd $(mktemp -d)`

2. `for i in {1000..9999}; do echo "{password for bandit24} $i" >> f; done`

3. `nc -v localhost 30002 < f`

<details><summary>Password</summary>iCi86ttT4KSNe1armKiwbQNmB3YJP3q4</details>
</details>
