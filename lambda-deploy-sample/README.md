# 使い方

```shell
docker run --rm -v "$PWD":/var/task lambci/lambda:nodejs12.x index.handler $(printf '%s' $(cat event.json))
```

### コンテナイメージ
https://hub.docker.com/r/lambci/lambda/
