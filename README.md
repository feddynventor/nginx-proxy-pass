# nginx-proxy-pass
Nginx instance on Alpine based Docker container. It *remakes* http requests.

This HTTP Proxy makes the request specified in the query via the `q` query parameter

```
http://<HOST>?q=<URL>
```

The specified external URL is visited with HTTP Schema