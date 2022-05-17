# DNA Maintenance

## 重點整理

- 所有細胞都有 DNA 修復機制
  - Mismatch Repair 專屬於 Mismatch 修復
  - Base Excision Repair 通常適合小範圍修復
  - Nucleotide Excision Repair 適合大範圍修復
  - Direct Repair 較少見
- DNA Recombination 利用另外一股 DNA 修復大片段的錯誤
  - Homologous recombination
    - Strand invasion、**Holliday junction**、Branch migration
  - Site-specific recombination
  - Transpositional recombination
- Error-prone translesion synthesis (TLS)、非同源性重組參與大規模 DNA 損傷的修復
- DNA 複製的過程中的常常出錯而須修復
  - DNA 複製過程中，單股會分離，容易發生突變
  - Lesion 可由同源性重組、TLS 兩種機制修復
  - 雙股斷裂由同源性重組、NHEJ 兩種機制修復
- 轉錄類似 DNA 複製，也可能出錯，需要 Transcription-coupled repair 修復
  - 修復模板股本身，而非修復 mRNA



## 2. DNA Repair

### 2-1. Mismatch repair

- 整理
  - 定義 : 在 DNA 複製後，檢查新股是否與原股完全一致。不一致的地方稱作 Mismatch
  - 機制 : 將新的一股在特定處切斷，並重新啟動聚合反應
  - 重點 : 原核生物透過「**甲基化**」原股，分辨新股與舊股的差異。真核生物分辨機制未明
- 催化過程
  - Dam 在細胞完成分裂之後，才會在 5'-GATC-3' 上的 A 加上甲基
  - Mismatched DNA 會啟動 Repair 路徑，吸引 **MutL 和 MutS**
  - **MutL-MutS Complex** 會在雙股上開始滑動，並在碰到甲基化的 GATC 後停止滑動
  - **MutH 蛋白**進入系統與 MutL-MutS Complex
  - MutH 與整個 Complex 作用，將 DNA 圍繞形成 loop
  - **MutH 進行內切**
    - 位置在 3'-CTAG-5' 中的 5' 端 G
    - 目標為沒有被甲基化的 daughter strand
  - Exonucleases 由 **3' 往 5' 方向分解**，SSB 穩定單股
  - DNA 開始重新合成
    - **Helicase 2 (UvrD helicase)**
    - **DNA polymerase III**、DNA ligase

### 2-2. Base-excision repair (BER)

- 摘要
  - 先使用 Glycosylase 催化將鹼基切除，接著才切除 Backbone
  - 有多種 DNA Glycosylase，對於不同類型的核苷酸受損具有專一性
- 過程
  - 利用特定的 **DNA glycosylase** 辨別受損核苷酸 (具專一性)
    - 切斷核苷酸中鹼基和核醣間的 **N-glycosyl bond 以形成 AP site**
    - AP site = apurinic 去嘌呤 / apyrimidinic 去嘧啶 site
  - 接著 **AP endonuclease** 會切掉 AP site 剩下的部分
    - 有時附近的核苷酸也會被移除
  - DNA Polymerase I 和 DNA ligase 補完移除的部分
- 應用
  - 此修復機制非常適合用於修復脫氨的 Lesion
    - 尤其是 C 脫氨變成 U

### 2-3. Nucleotide-excision repair (NER)

- 摘要
  - 與 Base-excision repair 比較，NER 會直接切除整個受損的核苷酸
  - 由 **Excinuclease** 辨別 DNA lesion 位置並切除
  - 原核約移除 **12~13 mer**，真核約移除 **27~29 mer**
- 過程
  - 利用 Excinuclease 辨別 DNA lesion 位置並內切
  - 小缺口會被 Excinuclease 切的更大，此步驟由 DNA Helicase 協助
  3. **DNA Polymerase I** 和 DNA ligase 補完移除的部分
  3. <img src="images\maintenance/image-20210615171556311.png" alt="image-20210615171556311" style="zoom:40%;" />
- 原核生物與真核生物比較
  - 原核生物
    - 切斷 5’ 上游第 8 個 nucleotide 和 3’ 下游第 5 個 nucleotide
      - 約移除 12–13 mer
    - 使用 DNA Polymerase I
  - 真核生物
    - 切斷 5’ 上游第 22 個 nucleotide 和 3’ 下游第 6 個 nucleotide
      - 約移除 27–29 mer
    - 使用 **DNA Polymerase ε**

### 2-4. Direct repair

- 摘要
  - 利用 **Photolyase** 修復，過程中利用光子激發 FADH* 使其產生 Free Radical
    - 最常見的例子為 Pyrimidine dimer 修復
    - **胎盤動物沒有 Photolyase**
  - 甲基化的修復
    - O6-methylguanine-DNA methyltransferase 可修復 methylated guanine
    - AlkB 可將 1-methyladenine 和 3-methylcytosine 去甲基
- Photolyase 催化機制
  - Photolyase 的 cofactor MTHFpolyGlu 吸收藍光附近的波長
    - 激發成 Free radical
  - 電子被轉移到 FADH^-^，形成 Free Radical *FADH^-^
  - 電子轉移到 DNA Dimer 上面，使中間的 Cyclonutane 結構解開
- 甲基化的修復
  - Methyltransferase
    - <img src="images\maintenance/image-20210615171741683.png" alt="image-20210615171741683" style="zoom:25%;" />
  - AlkB 修復 N 被接上甲基 (形成四級胺) 的情況
    - 過程中會產生 **formaldehyde**，可用來判斷 AlkB 的抑制程度
    - <img src="images\maintenance/image-20210615171850483.png" alt="image-20210615171850483" style="zoom:30%;" />

### 2-5. The Ames Test

 測試化學物質導致突變的檢測

- 利用一種無法合成 Histidine 的 Salmonella strain 
- 加入 His-free medium 內培養
- 如果加入物質會致突變，有機會使細菌存活，形成菌落 colonies（+）



## 3. DNA Recombination

### 3-1. Homologous Recombination

- 目的
  -  Reconstruct replication forks
- 摘要
  - **RecBCD** 首先與雙股斷點接合，並解旋、水解核苷酸
  - **RecA** 與 ssDNA 接合，形成 filament，並**協助 Strand invasion**
  - **RuvAB** 穩定 **Holliday junction** 並進行 **Branch migration**
  - **RuvC** 將 Holliday junction 切開
  - DNA ligase 黏合修復好的部分
- RecBCD 具有 nuclease 和 helicase 活性
  - 重點在於，使 exposed 5' 端的股較短，另一股較長
    - <img src="images\maintenance/image-20210615175720688.png" alt="image-20210615175720688" style="zoom:80%;" />
  - **RecB, D 均具有 Helicase 活性**
  - **只有 RecB 具有 Nuclease 活性**，會等速水解兩股核苷酸
  - **RecC** 辨認 exposed 3' end 股的 **chi seq.**，並結合，阻止此股繼續被水解
    - exposed 5' 端的股繼續被水解，因此會變短 
    - chi sequence GCTGGTGG
- 其他
  - 特別的地方，在複製叉崩壞前，圖中的兩股會黏在一起，老師說原因不需要知道
    - <img src="images\maintenance/image-20210615180323696.png" alt="image-20210615180323696" style="zoom:50%;" />

### 3-2. Site-specific recombination

- 酵素特性
  - 具有 Conserved 的 Tyr, Ser 反應中心
  - 四個 subunit
- 反應大致分成四階段
  - Cleavage, Rejoining-Isomerization, Cleavage, Rejoining
- 舉例
  - bacteria lambda phage 的感染

### 3-3. Transpositional recombination

懶的補了



## 4. Error-prone translesion synthesis (TLS)

- DNA 複製的過程中的 DNA 修復
  - Lesion 可由同源性重組、TLS 修復
  - 雙股斷裂只能由同源性重組修復
- TLS 修復是一種 low-fidelity 的 DNA 聚合反應
  - 模板股的 Lesion 過多的時候，此機制就會啟動
    - 不管模板多糟糕，都可以合成出核苷酸
    - 代表模板與新股的配對是不妥當的
  - 此為 DNA Replication 的 SOS response
    - 細菌的 SOS response 由以下蛋白質參與
      - **UvrA, UvrB + UmuC**
      - UmuD 是最重要的訊號，被 Cleaved 後會啟動 TLS 機制
      - ==**RecA** 結合到 ssDNA==
        - RecA 也在 DNA Recombination 扮演重要角色
      - **DNA Polymerase V** 是特殊的 low-fidelity 聚合酶
        - 由 Cleaved UmuD’ + UmuC 結合到 RecA 組成
    - 真核生物的 SOS response 沒有上到



## 5. 非同源性重組

除了同源重組外，NHEJ 也是修補雙股斷裂的方法
- **Ku70, Ku80** 蛋白會先結合在斷裂的 DNA 末端
- 接著再結合上 DNA-PKcs (kinase) 和 **Artemis (nuclease)** 蛋白。
- DNA-PKcs 會在很多個位置 autophosphorylate，並 phosphorylate Artemis。
- Artemis 會修正和去除 3’ 端和 5’端的單鏈核苷酸或是已形成的 hairpin，使 gap 變大，helicase 則將末端分離。
- 最後剩餘的缺口會被 XRCC4、XLF、DNA ligase IV 所形成的複合物密封。
