# whatislinux.github.io

```
git clone https://github.com/alibabaih/whatislinux.github.io.git
cd whatislinux.github.io
docker run --rm -it -v $(pwd):/src -p 0.0.0.0:1313:1313  klakegg/hugo:0.92.1-exta-alpine shell
# inside the container
hugo server
```

Browse http://localhost:1313/
