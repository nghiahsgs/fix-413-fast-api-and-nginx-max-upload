# fix-413-fast-api-and-nginx
fix 413 fast api and nginx


```
vi /etc/nginx/nginx.conf
```


```
http {
 client_max_body_size 100M;
}
```


```
systemctl restart nginx
```
