---
term: 魔法网络

---
比特币协议中用于识别节点间信息交换的特定网络（主网、测试网、regtest......）的常数。这些值刻在每条信息的开头，以便于在数据流中识别。Magic Networks 的设计初衷是在普通通信数据中很少出现。事实上，这 4 个字节在 ASCII 中并不常见，在 UTF-8 中也无效，而且无论数据存储格式如何，都会生成一个非常大的 32 位整数。Magic Networks（魔术网络）是（小双序格式）：


- 主网：

```text
f9beb4d9
```


- 测试网：

```text
0b110907
```


- Regtest：

```text
fabfb5da
```

> ► *这 4 个字节有时也被称为 "魔法数字"、"魔法字节 "或 "起始字符串 "*。