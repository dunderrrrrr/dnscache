# dnscache
Based on [askubuntu.com/questions/906476/how-can-i-flush-the-dns-on-ubuntu](https://askubuntu.com/questions/906476/how-can-i-flush-the-dns-on-ubuntu-17-04-solved). 
This is a very simple bash script that will clear your DNS cache.

### Installation
```sh
$ git clone git@github.com:dunderrrrrr/dnscache.git
$ cd dnscache/
$ sudo cp dnscache /usr/local/bin/
$ sudo chmod +x /usr/local/bin/dnscache
```
### Usage
There are two arguments that can be passed to the script, `clear` or `stats`. Both of them should be self explanatory. 
```sh
$ sudo dnscache stats
[...]
Cache
  Current Cache Size: 22
[...]
```
```sh
$ sudo dnscache clear
DNS cache has been cleared!
[...]
Cache
  Current Cache Size: 0
[...]
```


