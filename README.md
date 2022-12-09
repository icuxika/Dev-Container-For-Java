Dev Container For Vue3 & TS & Yarn & yrm & JAVA
==========

> 如果只需要`Vue3`的环境，请查看[Dev-Container-For-Vue3](https://github.com/icuxika/Dev-Container-For-Vue3)

> 此项目各项前置配置可参考[Dev-Container-For-Vue3](https://github.com/icuxika/Dev-Container-For-Vue3)

### 开发
- 为了保证 projects 目录下的文件性能（相比自动挂载的workspaces），需要先创建如下 volume
  > `docker volume create dev_java_data`

- 对于`projects`目录需要更新权限 `sudo chown -R vscode projects`