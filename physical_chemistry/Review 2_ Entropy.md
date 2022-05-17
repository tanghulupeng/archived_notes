Review 2: Entropy

Entropy 是用來預測反應自發性的物理量，透過熱力學第二定律，將其與自發性、亂度連結。
但是這一點在藥學的物化一點也不重要。你只要知道他怎麼算，怎麼用在 G 的計算就好。

* * *

**# Entropy 計算**

- ![](R2/0ccd2b121a40a21cf4eb25a8a410ba83.png)
- 定溫下
    - ![](R2/6e9629d5197a17e1de0e2d02e0982de5.png)
- 只能用 reversible 算
    - 但 entropy 只和起始狀態還有結束狀態有關
    - 因此 rrreverisble process 的 entropy 計算:
        - 找起始狀態、結束狀態。算 reverisble 的熱
    - 如果你用 irreversible process 的 q_irrev 去算
        - ![](R2/70147e82b5f7b36768381f3136a09e5c.png)

* * *

**# Entropy 會隨著溫度、體積、壓力而改變**

- 定體積的話，Entropy 分子的 q 可換成 Delta H
    - ![](R2/e4391e77d5cd9915111385d9f1e105df.png)
- T 的變化
    - 由定義，我們可以用積分的方式算出來
    - ![](R2/38947aeea8a15e50edc68e647f37759f.png)
- 體積、壓力的變化
    - 體積變化
        - 液體、固體
            - ![](R2/bb78240711cfb0bb6c891fd7294c535d.png)
        - 氣體
            - ![](R2/c828c42dfc0cba056ab2da8592ae644f.png)
            - at constant temp.
                - ![](R2/6785c0408e71df57856a9aae1fd469d2.png)
                - Because pV = nRT is a constant at constant temperature,
                - ![](R2/be6ed451331559042069e3c643aa1397.png)
                - ![](R2/c23e962113efaf313eb4da1a61b47c6c.png)
                - ![](R2/ae1833d1453567aff6872363afac5d83.png)
- 相變
    - ![](R2/4efc1a8810328f164d80f0cbcb798ec8.png)
    - 必須要是溫度不變的情況下才是 reversible
        - 不能算蒸發 entropy，只能算沸騰的
    - P 通常不變
        - 因此又可寫成
            - ![](R2/d58dec87f5fc75fec1cc5373a478aba2.png)

* * *

**# 熱力學第二定律**

- for any process
    - ![](R2/792e8ee7cb242467b62d5ce998d3e56d.png)
        - > 0 : irreversible
        - = 0 : reversible