## (xfce) icons & themes

* [FairyWren-Icon-Set](https://www.pling.com/p/1684521)

* [Capitaine Cursors](https://www.pling.com/p/1148692)

* [One Color](https://www.xfce-look.org/p/1148918)

* [Orchis theme](https://www.xfce-look.org/p/1357889)

## faster compiling
1. use the command >>nproc<< to check your number of cpu threads
2. to be on the safe side use like 2-4 threads less for compiling
3. sudo nano /etc/makepkg.conf
4. put in the desired # of threads e.g.
        MAKEFLAGS="-j10(nproc)"

## manually import a specific recv key
        gpg --recv-keys 893e8e9432898e

## [chaotix-aur for prebuilt packages](https://aur.chaotic.cx/)
What it is

Most packages available in this repo are automatically built from their respective AUR source package. However, there are a few exceptions, check out the packages repo to find out which ones.
The primary building cluster is a node in UFSCar's datacenter which is hosted in São Carlos, São Paulo, Brazil.

to install, follow the instructions on the website

## run programs as root without prompt

        myusername ALL = (root) NOPASSWD: /path/to/my/program
