# silent-shaper-cli

Observability · Networking

留着备查的示例

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

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 安装

```bash
git clone https://github.com/USER/silent-shaper-cli.git
cd silent-shaper-cli
cargo build --release
```

## 备注

就是给自己省点事，没做太多抽象。

## License

MIT
