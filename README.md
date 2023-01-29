# blog-hugo

Useful commands

to remote machin: scp -i /path/to/private_key /path/to/local/file username@server:/path/to/remote/file
to local machine: scp -r -i /path/to/private_key username@server:/path/to/remote/file /path/to/local/file


https://stackoverflow.com/questions/62326988/cant-access-oracle-cloud-always-free-compute-http-port

hugo server --bind=0.0.0.0 --baseUrl=http://your-ip-address -D -F

https://github.com/gohugoio/hugo/issues/1240

## changing branches
```
git branch gh-pages
git checkout gh-pages
git add .
git commit -m "Initial gh-pages commit"
git push origin gh-pages
git checkout main

```
