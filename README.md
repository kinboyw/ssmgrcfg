# ssmgrcfg

## this is the `docker run ` command of the shadowsocks-libev
```shell
docker run \
    --name ssmgr \
    -idt \
    --restart always \
    -v ~/.ssmgr:/root/.ssmgr \
    --net=host \
    gyteng/ssmgr \
    ssmgr -r libev:aes-256-cfb -c default.yml
    ```
