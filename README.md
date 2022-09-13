# known_hosts.d

This is a collection of public ssh keys for which I am pretty confident that
they are correct. The keys belong to services I use a lot on different
machines. Since I don't want to check these keys again and again whenever I
work on a new computer, I set up this repository. The idea is to clone it into
/etc/ssh/known_host.d and than link to the ssh_know_hosts file from
/etc/ssh/ssh_known_hosts. This makes the keys in this repository available
system wide. Additionally I can have further user specific known hosts in
~/.ssh/known_hosts.

So far there are keys for:

- github
- gitlab

If you trust me, feel free to use the keys in this repo. But if I was you, I
would check the keys myself. You can read about how and why you should do that
for example
[here](https://www.jamieweb.net/blog/managing-your-ssh-known_hosts-using-git/)
or [here](https://www.qubes-os.org/security/verifying-signatures/).

