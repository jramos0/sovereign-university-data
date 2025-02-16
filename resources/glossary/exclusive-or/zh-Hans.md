---
term: 专属或

---
布尔逻辑的一个基本功能。Exclusive Or "或 XOR（"*Exclusive or*"）接受两个布尔操作数，每个操作数均为真或假，只有当两个操作数不同时才产生真输出。换句话说，如果操作数中有一个（而不是两个）为真，"XOR "操作的输出就为真。例如，在 `1` 和 `0` 之间进行 `XOR` 操作的结果是 `1`。我们注意到：1 \oplus 0 = 1$。同样，"XOR "操作也可以在更长的比特序列上进行。例如，$10110 \oplus 01110 = 11000$。序列中的每个比特都要与其对应的比特进行比较，然后应用 `XOR` 运算。下面是 `XOR` 运算的真值表：

<div align="center">

| $A$ | $B$ | $A \oplus B$ | $A \oplus B$

|:---:|:---:|:------------:|

| $0$ | $0$ | $0$ |

| $0$ | $1$ | $1$ |

| $1$ | $0$ | $1$ |

| $1$ | $1$ | $0$ |

</div>

XOR "运算因其有趣的特性而被用于计算机科学的许多领域，尤其是密码学：


- 其交换性：操作数的顺序不影响结果。对于两个给定的变量 $D$ 和 $E$: $D \oplus E = E \oplus D$；
- 其关联性：操作数的分组不影响结果。对于三个给定变量 $A$、$B$ 和 $C$：$(A \oplus B) \oplus C = A \oplus (B \oplus C)$；
- 它有一个中性元素 `0`：与 0 分叉的操作数总是等于操作数。对于给定的变量 $A$：$A \oplus 0 = A$；
- 每个元素都是自己的倒数。对于给定变量 $A$：$A \oplus A = 0$。

在比特币中，"XOR "操作显然被用在很多地方。例如，比特币协议中广泛使用的 "SHA256 "函数就大量使用了 "XOR"。一些协议，如 Coldcard 的 *SeedXOR* 也在其他应用中使用了这个基元。在 BIP47 中也可以找到它，用于在传输过程中对可重复使用的支付代码进行加密。

在更广泛的密码学领域，"XOR "可用作对称加密算法。这种算法被称为 "一次性垫 "或 "弗纳姆密码"，以其发明者的名字命名。虽然由于密钥的长度而不切实际，但这种算法是唯一被公认为无条件安全的加密算法之一。