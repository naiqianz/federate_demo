# federate_demo

## 环境规范
### 方法1:使用conda虚拟环境，每个仓库需要有自己的environment.yaml声明所有的依赖，可参考[HarmoFL](https://github.com/med-air/HarmoFL)
### 方法2:使用dockerfile，每个仓库需要有Dockerfile文件用于部署环境，有entrypoint.sh文件用于启动，可参考[gin-vue-admin](https://github.com/flipped-aurora/gin-vue-admin/tree/main/deploy/docker)

## 算法规范
### 根目录的train.py用于开始参与训练，需要数据路径可配
### 根目录需要有check.py来验证数据是否合法
