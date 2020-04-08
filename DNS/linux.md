# Ubuntu

- [dns resolvconf](https://askubuntu.com/a/51286)

  - sudo apt install resolvconf
  - sudo nano /etc/resolvconf/resolv.conf.d/head

  ```
  nameserver 1.1.1.1
  nameserver 1.0.0.1
  nameserver 2606:4700:4700::1111
  nameserver 2606:4700:4700::1001
  ```

  - sudo resolvconf -u
