# C++とJupyterを用いて音声を取得・再生する

## 起動方法

```bash
docker build . -t cpprun
docker run --rm -p 8888:8888 -v $(pwd):/notebooks -w /notebooks -it cpprun  jupyter notebook --allow-root --ip 0.0.0.0
```

## C++を