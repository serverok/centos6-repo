# CentOS 6 yum repository

Replace files in your /etc/yum.repos.d folder on CentOS 6 server.

```
mv /etc/yum.repos.d /etc/yum.repos.d-old
cd /etc
git clone https://github.com/serverok/centos6-repo.git yum.repos.d
```

Now you can run


```
yum update
```
