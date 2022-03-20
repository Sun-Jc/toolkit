#### Password-free Sudo

```shell
sudo visudo
```

Add this at the end

```shell
username     ALL=(ALL) NOPASSWD:ALL
```

[ref](https://phpraxis.wordpress.com/2016/09/27/enable-sudo-without-password-in-ubuntudebian/)
