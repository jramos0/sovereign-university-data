---
term: 索引

---
在高清钱包中，它是指分配给由父密钥生成的子密钥的序列号。该索引与父密钥和父链代码结合使用，可确定地生成唯一的子密钥。它允许进行结构化组织，并可从同一父键重复生成多个同级子键对。它是一个 32 位整数，用于 "HMAC-SHA512 "派生函数。因此，该数字可区分高清钱包中的同胞子密钥。