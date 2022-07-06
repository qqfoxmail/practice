

## 实习

### YOCTO

### 采用的代码版本号

[manifest文件](./manifest.xml)

### docker

`docker`上传下载文件

`yocto-meta-openeuler`要上传或下载的文件

上传

    docker cp yocto-meta-openeuler 2a50f249ceec:/home/openeuler

下载

    docker cp 2a50f249ceec:/home/openeuler/yocto-meta-openeuler /home/lm
