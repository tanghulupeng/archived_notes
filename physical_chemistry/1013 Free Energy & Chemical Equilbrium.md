1013 Free Energy & Chemical Equilbrium

**# 學習策略**

- 複習
    - ![](1013_Review/e1bebb770efc3f16ad238a0f440d14ed.png) (formula 3.35)

* * *

**# Chemical Potential : Partial molar Gibbs Energy**

- Chemical Potential ≡ molar Gibbs Energy (exactly, 這是定義)
    - ![](1013_Review/9cdc16029e690efce285873fad60f082.png)
    - 除了 A 物質以外，其他物質莫耳數維持恆定
    - 在平衡當中，我們只在乎比例，不在乎多寡
- **Fundamental equation of chemical thermodynamics**
    - ![](1013_Review/492c28ce8a28c112d8e840e30b6f0767.png)
    - 特例，定溫定壓下:
        - ![](1013_Review/890a5511f89e54464271f9302dd6d3bb.png)
- **Standard Chemical Potential**
    - Gibbs Energy is Pressure dependent.
        - ![](1013_Review/3d96a4bd45f40cacdeb558ca1bd49967.png)
    - We would like to see if the reaction is spontaneous, which is not related to the amount.
        - ![](1013_Review/4d7d72ce7db42a00cd69d7ce85e24955.png)

* * *

**# Chemical Potential & Equilibrium**

- 一個化學反應用了多少量的物質，該怎麼跟另一個化學反應比較呢？
    - 這是化學計量問題，但是其實反應物消耗多少莫耳、生成物生成多少莫耳，只要除以反應係數，得到的莫耳數都是一樣的
    - 我們就可以用這個量去比較不同化學反應之間，莫耳數用量的多寡。
    - 定義 Xi
        - ![](1013_Review/78439a87137b0ddc2696e675e0472818.png)
        - 概念釐清
            - dξ 是一個數字，不是什麼可以微分，然後又可以積分的那種函數啦
            - 反應物 A 之莫耳數 = dξ * 反應係數
- 判斷反應方向的公式 (Reaction Gibbs energy [definition])
    - ![](1013_Review/8c7f22d38520411100c6ace6850362cf.png)
    - =   ![](1013_Review/0146e98a0c6883abb7d623daddd89a02.png)
        - 狀態 B 的 Chemical Potential Summation - 狀態 A 的 Chemical Potential Summation

* * *

**#**  **Activity**

- **## Activity 是什麼？**
    - Activity 探討的是「非理想狀況下」，我們要如何修正我們的 G、H、S，讓他們更能夠預測反應進行
        - 我們可以大概理解成 Activity 就是反應的有效濃度、分壓。
        - 理想氣體：道耳頓分壓定律；理想溶劑：拉午耳定律；理想溶質：亨利定律；
    - 由於 Activity 跟濃度、溫度那些有很大的影響，所以我們會定義 Standard State 做為參考
        - 當達到 Standard State 的時候 Activity = 1 (定義)
    - 科學家希望定義在 Standard State 下，理想情況 Activity → 1
        - 這樣 Activity 可以方便的跟那些理想的定律做比較。
        - 所以針對不同的環境，就會有很多不一樣的 Standard State。
- **## Activity of Ideal Gases**
    - 定義 Standard State 為理想氣體分壓在 1 bar 下。(1 bar ≈ 1 atm)
        - 在 Standard State 下，Activity = 1
    - **### Activity of Ideal Gases**
        - 完美的情況，就是可以直接用分壓算。而理想氣體就是完美的情況。
        - ![](1013_Review/067ec254221ab9a9d29aa86d26a1cadd.png)
    - **### Activity of Real Gases**
        - 不完美的情況，我們可以乘以常數去修正，反正可以查表。
        - ![](1013_Review/e9f6a9b8e2685f237ba7fcccd3e12877.png)
- **## Activity of Pure Solid, Liquid**
    - 定義 Standard State 為純物質在總壓 1 bar 下。(1 bar ≈ 1 atm)
    - 沒理由純的東西，Activity 不是 1 吧？
    - ![](1013_Review/3672bad3b3b6da3903ae38bba250275f.png)
- **## Activity of Solution**
    - Activity for Solution 就不好查表了，溫度、壓力、濃度不同，常數就不一樣，所以我們分成溶劑、溶質討論。
        - 如果你真的查的到溶液的 activity，你也可以這樣直接用 (紅框處代表會隨環境變因改變而變化)
            - ![](1013_Review/a7502b29f121bbd5059d415cee691c1b.png)
    - **### Activity of Solvent**
        - 定義 Standard State 為 1 bar 下純的溶劑 (Pure liquid)。(1 bar ≈ 1 atm)
        - 最靠近 Standard State 的狀態，要不是純的溶劑，要不然就是超級稀薄溶液 (very dilute solution)。
            - ![](1013_Review/d9f83d18f2a855884e6f8a095dc9e2f0.png)
        - 理想溶液的溶質 activity 就是莫耳分率。稀薄溶液 (Dilute solution) 也可用此估算
            - ![](1013_Review/819c2a341e2009efd6fc0c41cfac2110.png)
        - 越靠近理想狀態，我們越可以用莫耳分率去估算 Activity
            - ![](1013_Review/b974521e2d3c60d6185e19d38609ec2c.png)
            - 這告訴我們說，當我們溶劑的莫耳分率越接近 1 (越接近 Standard State)
            - 我們就越能夠用莫耳分率去估算 Activity
            - 例如: x = 0.8，就會比 x = 0.2 更適合用這個方式估計
        - 很不理想的狀態，就只能查表了
            - ![](1013_Review/a79a0c6233b56723c6fa92062f1af9c2.png)
    - **### Activity of Solute (記得要用重量莫耳濃度)**
        - 定義 Standard State 為溶質重量莫耳濃度  molality = 1 M，但是表現卻像稀薄溶液的時候。這個狀態不可能存在。
            - mola**R**ity  = 體積莫耳濃度；mola**L**ity  = 重量莫耳濃度
            - 這個定義是為了要同時滿足單位換算、亨利定律 (稀薄溶液) 而做出的奇怪定義。
                - 亨利定律是用重量莫耳濃度定義的
        - 當我們越接近理想狀態的時候 (越稀薄)，我們可以用重量莫耳濃度去估算 activity
            - ![](1013_Review/54b6ee58375ff2099b1d80517e60e79e.png)
            - 越稀薄，就越能夠成立
                - ![](1013_Review/fff45896436970ae51ada40db4d8db41.png)
            - 但是當溶液太稀薄 (1/1000 的差距)，其實重量莫耳濃度、體積莫耳濃度也不會差太多，我們可以亂帶體積莫耳濃度去估算。
                - ![](1013_Review/2059056a34f746d8677a4ab813c4bd3d.png)
        - 很不理想的狀態，就只能查表了
            - ![](1013_Review/2499147f8b7516eb3383363bb4fb6e43.png)

* * *

Biochemical Standard State

- H+ 的 Actvity 代 1

* * *

小故事: 為何液體的 activity 定義這麼詭異

- 因為科學家很討厭液體，液體很複雜，相對來說氣體就簡單很多
- 所以科學家一直在想辦法用液體的蒸氣去分析液體
    - 所以就有了針對溶劑的拉午耳定律、針對溶質的亨利定律。
    - 這兩個定律完美的讓科學家用蒸氣去分析液體，
    - 因此科學家把 activity 定義成這兩個定律的理想情況

* * *

* * *

沒用的東西了

# Equilibrium

- 判斷反應方向、是否達到平衡
    - ![](1013_Review/25ef6167f406a88f9d5b4eeb9c2a7880.png)
    - 代反應商得到 Gibbs 的值 ≠ Standard Gibbis
    - 代平衡常數得到 Gibbs 的值＝ Standard Gibbis
        - 意思是指平衡常數到任意微小改變的新狀態
            - delta Gibbs = Gibbs - Standard Gibbs = 0
            - 熱力學 unfavorable
        - 可用此條件解平衡常數，或反過來解自由能
            - ![Image.png]1013_Review/2997ee85a331dfcb4542b3c5fcd2bf8f.png)
- 反應商可判斷反應方向，平衡常數永遠是定值。
    - 也許你加了什麼，溶液平衡時色彩變了，但平衡常數不變。
    - ![](1013_Review/e5db023fba66976b0ce497559d78c86d.png)
        - >1 : 向左
            - (注意，這和 K > 1 的概念是完全不一樣
                - Q >1 是探討反應方向
                - K>1 是探討熱力學上是否 favorable)

* * *

# Activity 公式證明

- for Ideal Gases
    - proof
        - ![](1013_Review/404b4ac8c407f5d15d5ac14d32358c3e.png)
        - ![](1013_Review/5ca2a16d5f06a10ac557e0096f1ce284.png)
        - ![](1013_Review/a61fac3d0d6358e82de86ba01d9583af.png)

* * *