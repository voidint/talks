# talks

### 在线渲染

- [《Hello Golang》](https://go-talks.appspot.com/github.com/voidint/talks/hello-golang/hello-golang.slide)
- [《Hello Ansible》](https://go-talks.appspot.com/github.com/voidint/talks/hello-ansible/hello-ansible.slide)
- [《Docker Registry》](https://go-talks.appspot.com/github.com/voidint/talks/docker-registry/registry.slide)

### 本地渲染
- 下载本工程至本地
```shell
$ cd ${YOUR_WORKSPACE} && git clone https://github.com/voidint/talks.git
```
- 安装present
```shell
$ go get -u -v golang.org/x/tools/cmd/present
```
- 运行present
```shell
$ cd ${YOUR_WORKSPACE}/talks && present
```

- 浏览http://127.0.0.1:3999
