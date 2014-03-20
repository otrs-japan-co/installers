installers
==========

Install command ( 1 liner ) for Redhat / CentOS 6 from source.

```bash
# cd /usr/local/src/
# curl -L https://raw.github.com/otrs-japan-co/installers/master/otrs-installer.sh | bash
```

or

```bash
# cd /usr/local/src/ && curl -L https://raw.github.com/otrs-japan-co/installers/master/otrs-installer.sh | bash
```

## Quick Install

```bash
cd /usr/local/src/
wget http://ftp.otrs.org/pub/otrs/RPMS/rhel/6/otrs-3.3.5-02.noarch.rpm
yum localinstall otrs-3.3.5-02.noarch.rpm
```

## Quick Install One Liner

これ1行を貼り付けるだけでOTRSがインストールできちゃいます！
Just copy and paste this one liner, we can install OTRS !!

```bash
cd /usr/local/src/; wget http://ftp.otrs.org/pub/otrs/RPMS/rhel/6/otrs-3.3.5-02.noarch.rpm; yum localinstall otrs-3.3.5-02.noarch.rpm
```
