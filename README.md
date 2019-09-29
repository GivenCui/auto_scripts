# auto_scripts
## `.bashrc_docker`

```sh
# 下载.bashrc_docker并编辑.bashrc引用并重载.bashrc
wget -P ~ https://raw.githubusercontent.com/GivenCui/auto_scripts/master/.bashrc_docker &&  echo "[ -f ~/.bashrc_docker ] && . ~/.bashrc_docker" >> ~/.bashrc; source ~/.bashrc

# 使用举例
docker-pid <container>
docker-enter <container> # 用nsenter进入容器
docker-enter <container> ls # 用nsenter进入容器并运行ls
```
