## [Ruby Linux Install](https://www.brightbox.com/blog/2018/02/05/ruby-2-5-ubuntu-packages/)
The first stable release of Ruby 2.5 arrived on schedule on December 25th. As usual, it brings loads of new features, bug fixes and quite a few performance improvements.

And now it’s included in our Ruby Ubuntu package repository, so getting it running on Ubuntu is now super easy.

Just add our repository, if you haven’t already:
```sh
sudo apt-add-repository ppa:brightbox/ruby-ng
sudo apt-get update
```
Install the packages:
```sh
sudo apt-get install ruby2.5 ruby2.5-dev
```
And you’re up and running:
```sh
ruby2.5 -v
```

ruby 2.5.0p0 (2017-12-25 revision 61468) [x86_64-linux-gnu]
```sh
gem2.5 -v [2.7.3]
```

It’s available for Ubuntu 14.04 (Trusty), 16.04 (Xenial) and 17.10 (Artful).

As always, the same repository provides updated Ruby packages for 1.8, 1.9, 2.0, 2.1, 2.2, 2.3 and 2.4 for Trusty through to the latest supported Ubuntu release. We’ve recently published updates for all these versions of Ruby fixing all major outstanding security issues (yes, backported all the way to 1.8!).

