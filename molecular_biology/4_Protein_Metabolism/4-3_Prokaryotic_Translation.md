# 原核生物的轉譯

## 重要的知識

- 細菌的轉譯分成「起始」、「延長」、「終止」
- 細菌的 rRNA, tRNA 與真核生物不同
- 細菌需要 fMet-tRNA^fMet^ 起始多肽的轉譯
- 核糖體中的 Peptidyl Transferase 催化胺基酸的轉移到 Peptide
- 三個 Stop Codon : UAA, UGA, UGG，無法被任何 tRNA 辨識
  - 於是 RF-3 進入核糖體，催化多肽鏈與 tRNA 之間的水解



## 1. Initiation

1. 細菌的轉錄與轉譯 Coupled 在一起
   - 由轉錄因子 NusG 連結 RNA Pol 和核糖體
2. IF-1, IF-3 結合在 30S 次單元，促使大小次單元分離，並引導 mRNA 進入 30S 次單元
3. **IF-2** 接上 **GTP** 並攜帶 fMet-tRNA^fMet^ 進入 30S 次單元的 **P** 位
   - fMet-tRNA^fMet^ 的合成，消耗 N10-formyl-THF
   - fMet 的 N 端已經形成 amide，故胺基酸只會從 C 端加入
   - 有少數機制不使用 fMet 起始，此部分機制較少研究
4. 核糖體中的 16S rRNA 識別 Shine-Dalgarno sequence，使 P 位對準 AUG
   - Shine-Dalgarno sequence : Purine-rich
5. 大次單元與小次單元開始結合。**IF-2 水解 GTP**。IF-1, IF-2, IF-3 脫離核糖體
6. 剩下的部分組合成穩定的 70S Initiation Complex
   - 50S + 30S + mRNA + fMet-tRNA^fMet^

## 2. Elongation

- **EF-Tu-GTP** 攜帶 aminoacyl-tRNA 到 A 位
  - EF-Tu 隨後水解 GTP，脫離 complex
  - EF-Tu-GTP 的再生
    - **EF-Ts** 與 EF-Tu 結合，協助催化 GTP 與 GDP 交換的反應
- **Peptidyl Transferase** 作用
  - Peptidyl Transferase 催化中心在 23S rRNA (而不是蛋白質)
    - A2451 是催化最重要的核苷酸
    - 23S rRNA 在 50S 次單元中
  - 催化 A 位胺基酸 Amino group 攻擊 P 位多肽的 Carboxyl group
  - 催化後，產生 P/A hybrid state, E/P hybrid state
    - 此時 P 位的多肽已經被轉移到 A 位的 tRNA 上
    - 原本 P 位的 Anticodon 仍在 P 位上，但是 A 位的多肽鏈卻在 P 位上
- **EF-G-GTP** 催化 Translocation，將 A 點重新空出
  - EF-G-GTP 進入 A 位，於是原本 strained hybrid state 被解除
  - EF-G-GTP 主要與小次單元交互作用
  - EF-G 水解 GTP，脫離 A 位。A 位空出，重新開始下個循環

## 3. Termination

- 三個 Stop Codon : UAA, UGA, UGG，無法被任何 tRNA 辨識
- 與 tRNA 結構類似的 Release factors 進入 A 位
  - RF-1 認 UAG, UAA，RF-2 認 UGA, UAA
- RF-3 透過**水解 GTP**，打斷 P 位的 tRNA 與多肽的連結
- RF-3 隨後與其他的蛋白質作用，將整個 70S Complex 瓦解，核糖體被回收
