nginx config
=====

```shell
# kkyung.com
sudo ln -sf "$PWD/nginx.conf" /etc/nginx/nginx.conf

# Test
sudo nginx -t -c /etc/nginx/nginx.conf
```

##### References
- <http://nginx.org/en/docs/>
