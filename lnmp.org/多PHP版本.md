## ./install.sh mphp 按提示选择要另外安装的PHP版本，一次安装一个

## lnmp vhost add  添加虚拟主机时，选择对应PHP版本

```
/usr/localinx/confhost/域名.conf

将里面的include enable-php.conf; 替换为 include enable-php7.1.conf;

重启nginx
```
