---
term: op_pushdata4 (0x4e)

---
非常に大きなデータをスタックにプッシュできる。その後に、プッシュするデータの長さ（最大約4.3GB）を示す4バイト（リトルエンディアン）が続く。このオペコードは、非常に大きなデータをスクリプトに挿入するために使用されるが、トランザクションサイズに実用的な制限があるため、使用されることは極めて稀である。