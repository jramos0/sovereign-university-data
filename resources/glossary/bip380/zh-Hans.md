---
term: BIP380

---
一项改进建议，引入一种标准语言来描述高清比特币钱包的输出脚本集合。这种语言被称为 "输出脚本描述符"。其目的是将表示和管理输出脚本的方式标准化，以方便备份、导出和导入钱包。除了恢复短语等私人数据外，描述符还提供了检索高清钱包中使用的密钥对的所有必要信息。BIP380 描述了描述符的一般操作，而 BIP381、BIP382、BIP383、BIP384、BIP385 和 BIP386 则指定了所使用的表达式。BIP380 和所有其他与描述符相关的 BIP（BIP386 除外）已在 Bitcoin Core 0.17 版本中实现。