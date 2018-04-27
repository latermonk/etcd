# etcd

官网：
https://github.com/coreos/etcd



##  Install  


##  Hello World

### 起一个终端：
```
$ etcd
```


### 另外一个终端：

```
etcdctl member list
```

### Test:

#### PUT
```
 etcdctl put testkey "hello world"
 
```

#### GET

```

etcdctl get testkey

```

#### 常见问题:

```
etcd No help topic for 'put'
```


Just do :
```
export ETCDCTL_API=3
```


#####  Reference



中文版：
https://yeasy.gitbooks.io/docker_practice/content/etcd/install.html



入门教程：
https://www.jianshu.com/p/2966b6ef5d10   




