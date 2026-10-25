# light-binder



处理日常小任务的工具

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 安装

```bash
git clone https://github.com/USER/light-binder.git
cd light-binder
cargo build --release
```

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## License

MIT
