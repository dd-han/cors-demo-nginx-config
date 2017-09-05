# cors-demo-nginx-config

這裡存放 nginx 的設定檔，包括 API Server 與反向代理。

如果使用 ubuntu 或 debian 提供的 nginx ，僅需將這些檔案放入 `/etc/nginx/site-enables` 即可使用。使用 ArchLinux 或原始碼編譯的 nginx 請將檔案內容加入 `/etc/nginx/nginx.conf` 的 `http` 區段內。

## 檔案說明

- `api-harekaze-moe.site` 設定拒絕跨域存取的網站
- `api-天津風-moe.site` 設定允許跨域存取的網站
- `api-reverse.site` 反向代理並允許跨域存取