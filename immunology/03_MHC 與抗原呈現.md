# 抗原呈現

- T 細胞具有 MHC-restriction，故需要進行抗原呈現才有辦法有效活化細胞免疫。
  - TCR 必須同時辨識 MHC 和 antigen
  - 只辨識一種無法被活化。
- APCs 呈現抗原與 costimulator 滿足 Two signal model 的兩個 signals



## 1. 抗原捕捉

- 樹突細胞
  - 分布位置與命名差異 (在上皮細胞皮膜下方的稱為 Langerhans cell)
  - Conventional / Plasmacytoid type (抗病毒)
  - Migration : Capturing → Presentation
    - immature DC 又稱為 resting DCs 在黏膜組織中
      - 有 migration 的功能，負責抗原捕捉。
    - mature DC 表現 CCR7，會被 trap 在淋巴結，負責抗原呈現。
- 其他 APCs 與樹突細胞的差異
  - 樹突細胞 : 起始 T 細胞抗原反應
    - IFN-γ 促進呈現 MHC II，原本就有表現一些 MHC II
    - IFN-γ, CD40-CD40L interaction, TLR ligand 均可刺激 costimulator 表達
  - 巨噬細胞 : 促進 Effector T cell 進行 cell-mediated immune response
    - IFN-γ 促進呈現 MHC II，原本幾乎沒有表現
    - IFN-γ, CD40-CD40L interaction, TLR ligand 均可刺激 costimulator 表達
  - B 細胞 : 促進 cognate T cell-B cell interaction
    - IL-4 促進呈現 MHC II，原本就有表現一些 MHC II
    - Antigen receptor cross-linking 增加 costimulator 表達
- 三種 APCs 功能不一樣
  - DC 是專門呈現抗原給 T 細胞。
  - Macrophage 呈現抗原給 Effector Phase 的 T 細胞，其抗原呈現的目的是強化 Effector Functions。
  - B 細胞抗原呈現用於活化自己。



## 2. MHC 分子的結構與功能

- MHC I 由兩個 peptide 組成
  - 兩個 peptide 必須要 carrying peptide 才能穩定結合，不被泛素化修飾。
  - 其中 alpha chain 有三個 domain
    - alpha 1, alpha 2 具有多型性，用於與 peptide 結合
    - 但 alpha 3 是 conserved，用於與 CD8 結合。
  - 另外 beta2-microglobulin gene 並不是在 MHC 基因座上，此基因並沒有多型性。
  - <img src="03_MHC%20%E8%88%87%E6%8A%97%E5%8E%9F%E5%91%88%E7%8F%BE.assets/image-20210914151842400.png" alt="image-20210914151842400" style="zoom:50%;" />
- MHC 2 由兩個 peptide 組成。兩個 peptide 都在 MHC locus 上。
  - alpha1, beta1 具有多型性
  - alpha2, beta2 都是 conserved。
  - <img src="03_MHC%20%E8%88%87%E6%8A%97%E5%8E%9F%E5%91%88%E7%8F%BE.assets/image-20210914151912945.png" alt="image-20210914151912945" style="zoom:50%;" />
- MHC bind 多肽的特性
  - 線性 peptides
  - 一次只能結合一個。但是對很多種類的 peptide 均有親和力。
  - 自體抗原也會被呈現，這樣細胞表面才會有 MHC I，NK cell 才不會錯殺自己
    - 腫瘤也可以透過 MHC I 呈現腫瘤抗原。
  - MHC 畢竟還是蛋白質，所以對不同 peptide 片段親和力會有所不同
    - 另外，通常是某個位置的胺基酸決定其與 MHC 的親和力。
  - MHC 的表現是共顯性
  - polygeny
    - 針對個人 : 一個人會同時表現很多種 MHC gene
    - T 細胞可以識別所有自己表現的基因
  - polymorphism
    - 確保至少整個族群裡面，在新興疾病出現的時候，最慘也至少有少數人可以呈現 peptide。
  - Immunodominant peptides
    - 一個病原當然有很多 epitope 可以給 T 細胞、B 細胞辨識。但可惜的是，要刺激強的免疫反應，MHC 的結合親合度也很重要。很可能其實你只能呈現很多 epitopes 中的其中一個。
- CD1 用於呈現 lipid antigens。功能很類似 MHC 1
- MHC I vs. MHC II
  - MHC I : 8~11 個胺基酸
  - MHC II : 10~30 個胺基酸
  - HLA-A, B, C 是 Class I
  - HLA-D 是 Class II



## 3. Antigen Processing

### 3-1. MHC 1 Pathway

- TAP 運輸蛋白
- Tapasin 穩定 alpha chain

### 3-2. MHC 2 Pathway

- 在複合體形成前，Ii Invariant chain 擋住 class II MHC 的 peptide-binding cleft 避免過程中與其他不相關的 peptide 結合
- 接個這個 Ii Invariant chain 斷掉，留下 CLIP 片段，繼續擋住 MHC II 與抗原接合。
- HLA-DM 可以把 CLIP 換成 antigen。

### 3-3. Cross-Presentation

- 問題來自於 : MHC I Complex 的 peptide 來源必須是 cytsolic，但是這就代表樹突細胞必須被病毒感染，才有辦法呈現有 cytosolic antigen 的 MHC I Complex。沒有樹突細胞呈現有 cytosolic antigen 的 MHC I Complex，naive CD8<sup>+</sup> cells 沒有辦法分化成 Effector cells 進行胞殺。
- 課本提到抗原來源是 dead-cell-associated antigens，目前有證據顯示人類也有此機制，DCs (樹突細胞) 會吞噬被感染的細胞以進行 Cross-Presentation
- 另外，抗原來源也可以不是 dead-cell-associated antigens。有特殊的機制可以 transport MHC II Pathway processing antigen 到 MHC I Pathway (但是考量到 empty MHC I loading 的問題，因此這部分 poorly understood)



## 5. 抗原呈現 for B 細胞

- Naive B cells 通常直接辨識整個病原體，並不需要 Antigen processing 或抗原呈現
  - 但是可能需要 T 細胞的訊號以進行更強的免疫反應
- 在濾泡的 B 細胞，通常會有 FDCs 呈現「完整的病原體」給濾泡中的 B 細胞
  - Follicular dendritic cells (FDCs) 上有一系列受體，可以 bind to coated pathogen
    - 例如 antibody coated, or complement protein coated
    - FDCs 上的 receptors bind to antibodies or complement proteins