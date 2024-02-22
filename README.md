```bash
 docker build -t ckn_daemon . && docker container rm --force ckn_daemon && docker run --name ckn_daemon --network icicle -v icicle:/app/logs ckn_daemon
```