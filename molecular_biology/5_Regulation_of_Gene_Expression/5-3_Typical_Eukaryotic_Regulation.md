## 真核生物的基因表現調控

### 1. Overview

真核生物的基因表現，有 7 個階段可以受到調控

1. 轉錄起始
   - 染色體結構調控 (在下一份筆記中)
   - DNA-Binding Protein 與轉錄因子調控
     - 多個 Protein 可以作用在同一個 Gene，稱為 Combinational Controls
   - Transcription attenuation
2. RNA Processing
   - **Alternative RNA splicing**
   - Termination Cleavage : 切除並加入 Poly-A tail 的地方不同，會造成蛋白質 C 端不同
   - RNA Editing
3. RNA Stability and Distribution
   - **3'-poly-A shortening**
   - 部分 ncRNAs 會參與 mRNA 的降解
   - mRNA Transport from the Nucleus 可以被調控
   - mRNA 分布在 Cytosol 的位置也可以調控
4. 轉譯調控
   - Leaky scanning : 造成蛋白質 N 端不同
   - 5' / 3' Untranslated Region (UTR) 可以控制轉譯
   - Riboswitches 也可以控制轉譯
5. 蛋白質修飾
6. 蛋白質的運輸
7. 蛋白質的降解
   - 泛素 - 蛋白酶體系統
   - P-bodies 和 Stress granule

### 2. DNA-Binding Proteins 與轉錄因子

#### 2-1. DNA Binding Protein

- DNA-Binding Protein 普遍特性
  - 結合在 DNA Major Groove
  - 通常是 in *cis* 調控
    - 同一條同源染色體轉錄出來的調控蛋白控制同一條染色體的基因
- 真核生物 DNA Binding Protein 常見的 motifs
  - Zinc-finger motifs
    - 約 30 個胺基酸形成一個 motif
    - 需要鋅離子才能夠作用
    - 其作用力弱，因此一個 Protein 通常有多個此 motifs
  - Leucine-zipper motifs
    - 由兩個兩性的 alpha helix 組成，形成 coiled coil 結構
    - 此 motifs 事實上不參與 DNA 結合，而是參與蛋白質間的交互作用
    - 另有一個 DNA-Binding Domain，富有 Lys, Arg
      - 可通過正電與帶負電的 DNA 結合
  - Homeodomain
    - 結構較大，約 60 個胺基酸形成一個 motif
    - 只有 *Hox* 基因的 DNA-Binding Protein 才有的區域
- 名詞介紹
  - Control Elements 為 DNA seq，提供 Activators 或 Repressors 辨識並接合
    - Control Elements 可分為 Proximal / Distal
    - Distal Control Elements 可分為 **Enhancer, Silencer**
      - Enhancers 與 Binding Proteins 結合，透過調控 Mediator 改變轉錄速度
    - 許多蛋白質會同時作用在一個基因的調控區域，稱為 Combinational Controls
  - Enhancer 與 **Activators** (蛋白質) 接合，以下為 Activator 常見的作用機制
    - 促使 RNA Pol 結合在正確位置
    - 對 Histone 做修飾，以改變 Chromatin 的結構
    - 促進 RNA Pol 離開 Promoters
    - Transcriptional Activators 會協同作用 (1+1 > 2)
  - Silencer 與 **Repressors** (蛋白質) 接合，以下為 Repressor 常見的作用機制
    - 辨識同一個 Control Element
      - 與 Activator 競爭 binding
    - 辨識不同 Control Elements
      - Masking the Activation site of the Activator
      - 直接影響 General Transcription Factors
    - 促進染色體結構改變
      - 促使染色體重新被 packaged，回到 resting 的狀態
      - 甲基化 / 去乙醯化通常有助於降低基因表現

#### 2-2. Transcription Factors 相關調控

- 在此只討論 TATA-dependent 的 mRNA 合成
  - 因為 TATA-less 的合成多半是 Housekeeping genes
  - 這類基因的合成不需受到調控
- 磷酸化 eIFs 可以抑制轉譯起始
  - 舉例 eIF2 + GDP 必須要由 eIF2B 催化，將其 GDP 置換成 GTP，才有轉譯起始活性
  - 但是當 eIF2 被某些調控或傳訊路徑下游的 kinase 磷酸化，則 eIF2B 將無法置換 eIF2 上面的 GDP，因此轉錄無法起始

### 3. 轉錄後調控與 RNA Processing 調控

- Transcription attenuation 可使啟動的轉錄動作被迫中止
  - 其中一種機制涉及到 nascent RNA
    - nascent RNA 干擾 RNA Pol 合成 mRNA，強迫終止 mRNA 合成
  - 例如 HIV 感染時，nascent RNA 干擾 RNA Pol 合成病毒 RNA
    - 但是當環境合適時 HIV 的 Tat 蛋白會表現
    - 結合 nascent RNA 的 "bulged base"，使得此干擾機制失效
- Alternative RNA splicing
  - 由於 Alternative RNA splicing，因此 one gene, one polypeptide 的說法必須更正
- End Singal Cleavage 的位置，會影響到蛋白質的 C-terminus
  - 真核生物在 RNA Pol 合成結束後，需要尋找內切位
    - 在此內切位切除部分 RNA 並加入 Poly-A 以完成 3'-End
  - 舉例 : 分泌型抗體與膜上抗體的差異
    - encode 抗體的基因有兩個切位可以提供 RNA 合成結束的 Cleavage，其中一個較弱，另一個下游的切位較強
    - 在沒有 CstF 的情況下，上游較弱的切位通常會被跳過。CstF 可以增強 Cleavage 活性，使得上游的切位被切除
    - 尚未活化的 B 細胞 (非漿細胞)，CstF 濃度較低，切到下游的切位，C-terminus 較長，可以 bound 在細胞膜上
    - 漿細胞 CstF 濃度較高，會切到上游切位，C-terminus 較短，無法 bound 在細胞膜上
- RNA-Editing 可以改變 mRNA 上面的核苷酸序列
  - 常見的是 A→inosine，較不常見的是 C→U
  - 例如人類的 apolipoprotein B 基因在肝臟、腸道表現的蛋白質是不同的
    - 腸道表現 apoB-48、肝臟表現 apoB-100
    - 這是因為在腸道中，接近基因中間的位置，CAA 被修改為 UAA，使轉譯提前終止

### 4. RNA Stability & Distribution 調控

- Eukaryotic mRNA 3'-poly-A shortening
  - 當 poly-A tail 縮短到一定的長度 (約損失 25 bp)，會啟動兩種機制使 mRNA 完全降解
    - 從 3' 外切到 5'
    - 移除 5'-cap，使得 exposed mRNA 被 mRNA 降解酶快速降解
  - mRNA Decay 和 Translation 競爭，並決定蛋白質表現量
  - Eukaryotic mRNA 通常不會穩定的在 cytosol 待超過半小時
- ncRNAs 的調控
  - miRNAs 與 siRNAs 可用於 RNA Interference
    - 使用幾乎完全相同組合的蛋白質組成 Dicer、RISC
    - 兩者主要差異在 Prior precursor 不同
      - miRNA precursor 是 Hairpin 結構
      - siRNA precursor 是完全互補的雙股 RNA
        - 通常來自於病毒或 Transposon
    - 另外，專一性、控制力道也不同
      - siRNA 遇到完全互補的 mRNA 才會 silencing，且會直接內切 mRNA
      - miRNA 只要部分互補，就會抑制基因表現，可能有上百種 mRNA 同時被控制
    - 可透過人工合成雙股 RNA 送進細胞，達到干擾效果
  - Single-strand RNA 的 RNA 干擾
    - 只要 mRNA 發生 base-pairing，形成 dsRNA，就容易被降解
    - 一般而言，dsRNA 在細胞不穩定，不易用作 RNA 干擾
      - 可將 RNA 的 Ribose 換成 Morpholino，就會比較穩定
      - 此干擾方式目前主要用於斑馬魚研究
- RNA Transport from the Nucleus 可以被調控
- mRNA 分布在 Cytosol 的位置也可以調控

### 5. 轉譯調控

- 起始 AUG codon 附近的序列，會影響蛋白質轉譯的起點
  - 詳細機制請看「轉譯 > 起始合成的機制 」
  - 此機制看的是第一個 AUG 附近的序列和 consensus recognition seq. 的差異
  - 如果差異太大，第一個 AUG 有較高機率被跳過，創造出 N-terminus 不同的 polypeptide
    - 但是透過調控 eIFs 濃度，可以調控第一個 AUG 被跳過的機率
    - 此現象稱作 Leaky scanning
- 5' / 3' Untranslated Region (UTR) 可以控制轉譯
  - 特定的 repressor 可以辨識 UTR 上面的 seq 並干擾轉譯

### 6. 蛋白質修飾

### 7. 蛋白質的運輸

### 8. 蛋白質的降解

- 一些 mRNA 並未被降解，而是和一些蛋白質形成 P-bodies 和 Stress granule
  - P-bodies 和 Stress granule 是蛋白質和 RNA aggregate 形成的特殊球狀結構，但不含雙層膜
    - P-bodies 的 RNA bind 到特殊的蛋白質
  - 這些 mRNA 和其他功能的 RNA有機會被重新使用，或者是面臨最後被降解的命運
  - P-bodies mRNA 攜帶 P-Bodies 裡面的蛋白質，移動至 Stress granule，將蛋白質置換成 Stress granule 裡面的蛋白質，離開 Stress granule 後，即形成 "translation-ready mRNA"
  - P-bodies 和 Stress granule 的平衡
    - 在外界條件惡劣時，例如飢餓、藥物治療等，P-bodies 和 Stress granule 會變大
    - 細胞透過細胞自噬機制摧毀 P-bodies 和 Stress granule