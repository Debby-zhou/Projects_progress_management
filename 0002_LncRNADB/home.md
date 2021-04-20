# lncRNA Database首頁
## 功能全覽圖
### ▪️ 網站功能架構
![](./picture/DB.png)
1. **Gene Search**: BLAST, associated gene in the genome(network-like), <font color=#0000ff>experiments varification</font>
2. **Expression Search**: Tissue-specific, Stage-specific
3. **Genomic Browsing**: TF-binding sites, Epigenetic(Histone modification)
   > TAIR-like layout: 
   > - genome with exon, intron
   > - marker of modification 
4. **Functional Network**: miRNA regulation, co-expression
   
   > miRNA regulation指lncRNA會和Ago結合，但其序列和Ago active site的序列mismatch，故會影響其他miRNA作用。
5. **SNP Browse**
6. **QTL Browse**: 數量基因座代表在genome上和此lncRNA相關的其他基因表現量。
<pre>SNP Browse and QTL Browse will be added in the future.</pre>

### ▪️ 全覽圖設計
Version I
<font color=#FF0000>Deadline: 2021.04.20</font>

- 設計風格：
  
  ![ ](picture/function_%20overview.png)

- Logo底圖：
  - 淺灰為主，深灰為輔
  
  - 底圖大小：300*300px
  
  - Demo：
  
    ![深灰底圖](picture/DarkBG.png)
    ![淺灰底圖](picture/LightBG.png)



- Gene search

  ![gene search](picture/gene_search.png)

- Expression search

  ![expression search](picture/expression_search.png)

- Functional search

  ![functional search](picture/functional_search.png)

- Genomic search

  ![genomic search](picture/genomic_search.png)

- SNP browse

  ![SNP browse](picture/SNP_browse.png)

- QTL browse

  ![QTL browse](picture/QTL_browse.png)

整體：

![home overview](picture/home_overview.png)