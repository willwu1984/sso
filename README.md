|![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/Warning.svg/156px-Warning.svg.png) | This project is no longer supported.
|---|---|

# sso
cas单点登录，后端数据使用AD

使用修改application.properties
```
cas.authn.ldap[0].ldapUrl=ldap://192.1.0.1:389/ #更改为ad服务器的地址
# 更改为ad账户信息
cas.authn.ldap[0].baseDn=DC=dc,DC=local
cas.authn.ldap[0].bindDn=user
cas.authn.ldap[0].bindCredential=password
```
