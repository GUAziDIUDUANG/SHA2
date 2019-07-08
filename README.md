# 单向散列函数(Hash函数)

1. 定义:

   - 只有一个输入和一个输出,输入称为消息,输出称为散列值.

2. 作用:

   - 检验消息完整性

3. 特点:

   - 压缩性:任意长度的数据,都能算出固定20字节长度的散列值
   - 容易计算:能在一定时间内计算完成
   - 抗修改性:只要数据修改任何一字节,都会产生不同的结果
   - 强抗碰撞性:想找到散列值相同的数据非常困难
   - 单向性:只能加密,不能解密

4. 常用哈希函数

   - MD4,MD5

   - SHA-1,SHA-256,SHA-384,SHA-512

     - | 哈希函数 | 散列值长度(bit) | 备注                               |
       | -------- | --------------- | ---------------------------------- |
       | MD4      | 128             |                                    |
       | MD5      | 128             |                                    |
       | SHA-1    | 160             |                                    |
       | SHA-256  | 256             | SHA-256,SHA-384,SHA-512统称为SHA-2 |
       | SHA-384  | 384             |                                    |
       | SHA-512  | 512             |                                    |
       | SHA-224  | 224             |                                    |

     