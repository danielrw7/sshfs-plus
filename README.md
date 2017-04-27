# sshfs-plus

A profile based helper script for sshfs

### Setup:
1. Install [sshfs](https://github.com/libfuse/sshfs).
2. Run `git clone https://github.com/danielrw7/sshfs-plus.git`
3. If you want to add `sshfs-plus` to your PATH, add this to your bashrc:
```
export PATH=$PATH:/path/to/sshfs-plus
```

### Usage:

```
help			sshfs-plus (h|help)
mount			sshfs-plus (m|mount) [profile_key]
unmount			sshfs-plus (u|unmount) [profile_key]
list mounted dirs	sshfs-plus (l|list)
list profiles		sshfs-plus (p|profiles)
add profile		sshfs-plus (a|add) [profile_key] [remote_path]
get mounted dir		sshfs-plus (d|dir|directory) [profile_key]
```
