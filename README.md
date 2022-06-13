
# CSI-Drive-KVM
demo csi-drive 项目

编译项目
```shell
CGO_ENABLED=0 GOOS=linux go build -o ./bin/kvm-csi-driver ./cmd
```
打包镜像
```shell
docker build -t xnile/kvm-csi-driver:v0.1 ./
docker push xnile/kvm-csi-driver:v0.1
```

参考文档：
https://blog.dianduidian.com/post/%E5%BC%80%E5%8F%91%E8%87%AA%E5%B7%B1%E7%9A%84csi%E5%AD%98%E5%82%A8%E6%8F%92%E4%BB%B6