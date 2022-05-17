## ncRNAs 功能整理
- Noncoding RNAs = ncRNAs 
- 其他與調控無關的 ncRNAs
  - tRNA, rRNA
  - snRNA = small nuclear RNA (在 the splicing of pre-mRNA 扮演重要角色)
  - snoRNA = Small nucleolar RNAs (協助修飾 rRNA)
- 三種 **RNA Interference** 系統: siRNA, miRNA, piRNA



### 1. miRNAs 與 siRNAs
- **miRNAs (microRNAs)**
  - miRNA 的合成與組裝成 RISC
    - miRNA 編碼完成後，會有 Hairpin 的結構穿出核孔
    - 經過 cytosolic 酵素催化後，Hairpin 其中一個互補序列會被切除並降解，此階段稱作 "dicing"
    - Diced 後的 miRNA 沒有 Hairpin 結構，和 Argonaute 等蛋白形成 RISC
      - RISC = RNA-induced silencing complex
    - RISC 在細胞質尋找和內部 miRNA 互補的 mRNA
      - 若互補作用強，則 RISC 直接催化內切反應，將 mRNA 切斷，稱作 "slicing"
        - 此過程需要兩個 Mg^2+^ 協助催化
      - 若互補作用弱，則 RISC 會 recruit 其他 repressors 並讓其 bind to mRNA
        - 通常此作用也會使 mRNA 往 P-bodies 輸送
        - 通常這種比較常見，有機會讓更多 regulator 調控基因表現
  - miRNA 的重要性
    - miRNA 參與約 1/3 的人類基因調控
    - 許多 mRNA 的 UTR 都有類似序列，使 miRNA 可以同時調控很多種基因表現
- **siRNAs (small interfering RNAs)**
  - siRNA 的 precursor 來自於雙股 DNA (RNA?)，因此通常是 transposons or viruses
  - 經歷和 miRNA dicing 一樣的過程，雙股變成單股，形成 RISC
  - siRNA 通常用於防禦病毒基因攻擊
  - siRNA 亦發現與 Heterochromatin 形成有關 (p. 432)
    - 此過程稱作 RITS (RNA-induced Transcriptional silencing)
    - RITS complex 透過單股 siRNA 作為 guide，和互補 DNA 配對
    - 當 RNA Pol 轉錄時，RITS Complex 接上 RNA Pol tail，接上 exposed DNA，並吸引 Histone-modifying enzymes，形成 Heterochromatin，以使此段基因沉默。
- miRNAs 與 siRNAs 的比較 (https://doi.org/10.1038/mtna.2015.23)
  - 使用幾乎完全相同組合的蛋白質
  - 主要差異在 Prior precursor 不同
    - miRNA precursor 是 Hairpin 結構
    - siRNA precursor 是完全互補的雙股 RNA
      - 通常來自於病毒或 Transposon
  - 另外，控制的精確程度也不同
    - siRNA 遇到完全互補的 mRNA 才會 silencing → 只有一種 mRNA 被控制
    - miRNA 只要部分互補，就會抑制基因表現 → 可能有上百種 mRNA 同時被控制
  - 最後，控制的力道也不同
    - siRNA 找到互補 mRNA 後會直接內切
    - miRNA 找到部分互補的 mRNA 後，只會抑制基因表現
      - 只有在互補作用強的時候，才會啟動內切反應
  - 由此可見，siRNA 比較適合作為治療的 agent



### 2. piRNAs (piwi-interacting RNAs)

- piRNA precursor 包含 transposon seq 的 fragment
- piRNA coding seq 位於 germline，轉錄後不會受到 dicer 處理
- piRNA 和 Piwi Protein 形成 Complex，而不是和 Argonaute
- piRNA 防禦 transposon 移動造成的突變
  - 有證據顯示 piRNA 在精子形成當中扮演重要角色
  - 有證據顯示 piRNA 似乎也會透過 Chromatin Condensation，去 silence 一段 seq 的表現。 (from Campbell Biology 12e)



### 3. **lncRNAs (long noncoding RNAs)**

- 定義為超過 200 NDP 的 noncoding RNAs
- 目前認為，大部分為 noise，只有少部分有功能
- 目前被確知有功能的 lncRNAs，舉例如下
  - telomerase RNA (請看端粒功能區段)
  - Xist RNA (請看 X inactivation 區段)
  - 有些 lncRNA 涉及到 Genomic imprinting (請看 *Kcnq1* imprinting)
- lncRNA 的功能包羅萬象，但有幾個功能是統一的
  - 作為 scaffold RNA，此種 lncRNA 可以 bring together associated proteins
    - 例如 telomerase RNA，作為 scaffold，將多個蛋白質 bind 在自己身上
  - 作為 guide RNA，利用互補的鹼基配對執行生理功能
    - 例如 antisense RNAs，可和 mRNA 發生互補作用而使 mRNA 功能失效
      -  antisense RNAs = 從錯誤方向轉錄的 RNA
      -  從正確方向轉錄 protein-coding gene 的 RNA 才叫做 mRNA
    - 某些 lncRNA 則透過鹼基配對，削弱 miRNA, siRNA 的功能，降低 RNAi 對於 mRNA 轉錄的影響

### 4. **crRNAs (CRISPR RNAs)**

- CRISPR = Clustered Regularly Interspaced Short Palindromic Repeats
  - 在細菌染色體中，等間距、回文，很多有上述特徵的類似序列形成叢集
- 形成過程
  1. 初次感染噬菌體
     - 若細菌得以抵禦，會留下噬菌體雙股 DNA fragments
     - 此碎片會被處理，並整合進入細菌本身的染色體
  2. 二次感染噬菌體，細菌從 CRISPR locus 轉錄出 CRISPR RNA
     - 單股 RNA
  3. CRISPR RNA 和 Cas Protein 結合形成 Complex，造成二次感染的 DNA 發生雙股斷裂
     - Cas (CRISPR-associated) Protein
     - CRISPR RNA 作為 guide RNA，辨識外來 DNA