# C++とJupyterを用いて音声を取得・再生する

## 起動方法

```bash
# AudioFileを使う場合
git clone https://github.com/adamstark/AudioFile.git 

# Dockerをビルド
docker build . -t cpprun
docker run --rm -p 8888:8888 -v $(pwd):/notebooks -w /notebooks -it cpprun  jupyter notebook --allow-root --ip 0.0.0.0
```

## 出力結果を見る

[こちら](https://suzukidaishi.github.io/CppJupyterSound/)

## メモ
- PyScriptと併用すればmatplotlibの力も借りられそう

## 参考文献
- https://github.com/jupyter-xeus/xeus-cling
- https://github.com/adamstark/AudioFile