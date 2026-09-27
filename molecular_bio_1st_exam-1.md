---
title: molecular_bio_1st_exam-1

---

# molecular biology 1st-1
## chapter 1 and 2
### before we start the class...
> 大家還記得嗎? 😏
#### Mendel 🫛
- **Mendel並不知道gene的存在**，只是認為父母會給後代一些他也不知道的... 東西
- genotype = 基因型，phenotype = 表現型
- dominant = 顯性，recessive = 隱性，由於Mendel運氣好選到了完全顯性的物種性狀，因此才能夠提出分配律和獨立分離律
- 子代之所以用 $F$ 是因為拉丁文的*filius*是兒子，*filia*是女兒
- 他認為個體身上有兩個東西，每一次會各傳一個給自己的 $F$ ，homozygotes = 同型合子，heterozygotes = 異型合子
- 性狀會呈現出dominant allele的表現型，而且這些allele並不會消失，而是傳給下一代

#### Morgan 🪰
- chromosome theory of inheritance: 染色體是基因的載體
- 他把白眼 (recessive) 和紅眼 (dominant) 果蠅雜交，發現大部分 (但不是全部) 的第一子代是紅眼
- 然後第一代雄果蠅和第二代雌果蠅 (都是紅眼) 雜交，產生四分之一的白眼雄果蠅，沒有雌果蠅是白眼

> [!Tip]
> 這叫做sex-linked (性聯遺傳)，也是這時才把染色體分成autosome (體染色體) 和 sex chromosome (性染色體) 🐱

- wild type = standard type = 一般種，mutant = 突變種
- 白眼和短翅 (miniature) 都是mutant，也是X染色體性聯遺傳

##### 互換率
- 在雙雜合測交 (test cross) 或雜交實驗中，後代會分成親本型 (parental type) 和重組型 (recombinant type)
  - 親本型: 基因組合與親代相同
  - 重組型: 因為互換而出現的新組合

$$
\text{互換率} = \frac{\text{重組型個體數}}{\text{總個體數}} \times 100\%
$$

- 在基因圖譜中，常用分摩根 (centimorgan, cM)，**1% 的互換率 ≈ 1 cM**
- **互換率最高只能到 50%**，因為當基因座距離太遠時，互換幾乎隨機，和獨立分配無法區分
- **互換率與基因座距離大致成正比**，但在長距離上會低估 (因為可能有多次交叉互相抵消)

#### RNA類型


| RNA 種類 | 功能 | 負責的 RNA pol | 備註 |
| --- | --- | --- | --- |
| **mRNA** | 攜帶基因資訊，作為蛋白質合成模板 | **RNA pol II** | 轉錄大部分的 snRNA、miRNA 等 |
| **tRNA** | 將胺基酸帶到核糖體，對應 mRNA 密碼子 | **RNA pol III** | 同時也轉錄 5S rRNA 與一些小 RNA |
| **rRNA** | 構成核糖體的主要結構與催化成分 | **RNA pol I** | 專門轉錄 28S、18S、5.8S rRNA |


### 分子遺傳學
#### Griffith's experiment
- 發現了轉化原理，**transformation particle**
- 他使用 *Streptococcus pneumoniae*，分為有多醣莢膜的致病型 (S 型，smooth) 和無莢膜的非致病型 (R 型，Rough，很快就被白血球吞掉)

> [!Note]
> - **virulent**: 致命
> - **avirulent**: 不致命

```mermaid
timeline

title Griffith's experiment
  注射活的S型菌: 導致小鼠死亡: 有夾膜為致病關鍵
  注射活的R型菌: 小鼠依然存活: 無夾膜並不致病
  注射加熱殺死的<br>R型菌: 小鼠存活: 死菌並不致病
  活的R菌 +<br>死的S菌: 小鼠死亡: 死鼠內可以<br>分離出活的<br>S型菌: R菌被轉化
```
![image alt](https://microbenotes.com/wp-content/uploads/2022/08/Griffiths-Transformation-Experiment.jpg)

#### Avery's experiment
- 雖然Griffith已經知道有一種東西可以把無害的細菌變成有害，但他不知道是啥物質
- 他一樣使用 *Streptococcus pneumoniae*，然後從S型細菌中提取未知的轉化物質
- 這些雜物分別用蛋白酶、RNA酶、DNA酶處理後，給R型菌

||觀察到|
|---|---|
|蛋白酶|R 型被轉化成 S 型|
|RNA酶|R 型被轉化成 S 型|
|DNA酶|R 型無法被轉化|

- 由於**唯有破壞 DNA 時，轉化作用消失**，這證明 DNA 就是遺傳物質，而不是蛋白質或 RNA

![image alt](https://s3.amazonaws.com/s3.timetoast.com/public/uploads/photos/13323392/Avery_.jpg)

- 至於如何分離並確定是DNA，有一些方式...
  - 超快速離心 (Ultracentrifugation，很中二的名字)，因為DNA分子量很大
  - 電泳 (Electrophoresis)，因為他有很大的**charge-to-mass ratio**，跑很遠
  - 紫外光 (Ultraviolet)，在**260nm**有最大吸收峰 (不同於蛋白質的280nm)
  - 氮磷比 (N-to-P ratio)，通常DNA的磷很多，**如果高於1.67，代表可能還不夠純**

#### Beadle's experiment
- 他和Edward Tatum，例用麵包黴 (*Neurospora crassa*) 做實驗
- 一般來說麵包黴能在簡單培養基（只含糖、鹽、維生素）中生長，這代表它能自己合成所有必需胺基酸與維生素
- Beadle 與 Tatum 用 X 光 (mutagents) 照射孢子，製造隨機突變，然後讓他們在這些培養基中生長

> [!Tip]
> 若某突變株無法在最小培養基生長，但在加入特定胺基酸或維生素後能恢復生長，表示該突變破壞了合成該分子的基因 ! 😗

- 因此他們認為，每個基因控制一個特定酵素的合成，也就是**一基因一酵素假說**
- 但後來發現...
  - 一個酵素可以由多個基因形成
  - 很多基因並不編碼酵素，例如遺傳因子的基因
  - 有些基因甚至編碼RNA，而非蛋白質
  - 原核生物通常是一基因一多肽，但是真核生物有些可以做 "可變基因剪切"

> [!Important]
> ##### 必記 😏
> - 現在已經基本有共識，**即使你編碼的是IncRNA，你也會被認為是 "gene"**，即使你不會產生蛋白質 🐱

#### Hershey–Chase experiment
- 利用phage T2，蛋白質外殼 + DNA核心
- 用 $^{35}S$ 標記蛋白質 (Cys and Met有S)， $^{32}P$ 標記DNA (磷酸基團)
- phage感染大腸桿菌後，把嗜菌體外殼甩掉
  - 如果是phage外殼被S標記，在離心後會在懸浮液裡面發現放射標記
  - 如果是phage DNA被P標記，在離心後會在沉澱pellet中發現放射標記 
- 因為pellet裡面是大腸桿菌，而在標記P的時候，才在pellet裡面發現標記，因此注入E.coli的東西，就是含有P的DNA
![image alt](https://ib.bioninja.com.au/img/hershey%20chase.jpg)

#### Meselson–Stahl experiment
- 他們用氮同位素 $^{15}N$ 培養E.coli，使其DNA全部含有重氮
- 然後轉移到只含 $^{14}N$ 的培養基，讓他們一代一代分裂
- 每一次複製後取出DNA，利用 $CsCl$ 做密度梯度離心 

|generation|result|
|---|---|
|第0代|只有重帶DNA|
|第1代|出現中間帶DNA|
|第2代|出現中間帶DNA和輕帶DNA|

- 這證明了半保留複製 **(semiconservative replication)**

![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/the_Meselson_Stahl_experiment_0613.jpg)

### 聚核甘酸
- DNA的組成 = **含氮鹼基 + 磷酸基 + 去氧核醣**
- purine兩環，pyrimidine一環
- **核糖在2C上有OH**，去氧核糖沒有
- nucleosides為**核甘酸 - 磷酸基**
- 含氮鹼基連在1C，2C看是OH還是H，3C接磷酸二酯鍵 (phosphodiester bonds)，5C接磷酸基
- 起頭為5'-phosphate group，尾巴為3'-hydroxyl group

> [!Tip]
> 因為中間的鍵結是中間一個P，兩邊接O，所以叫做phospho + di + ester，如下: 
> ```
> Sugar₁ — O — P(=O)(O⁻) — O — Sugar₂
>          ↑               ↑
>        ester           ester
> ```

![image](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/nucleotide_structure_0301.png)

#### 反應機構
##### 定位
- DNA 聚合酶將 dNTP $\alpha$ -磷酸靠近引子 3'-OH
- $Mg^{2+}$ 雙金屬離子協助穩定負電荷

##### 親核攻擊
- 3'-OH 的氧原子進攻 $\alpha$ -磷酸的磷原子 (路易士鹼攻擊P)
- 形成一個五配位過渡態 (pentavalent transition state)

##### 鍵形成
- 新的磷酸二酯鍵在 3'-O 與 $\alpha$ -磷酸之間形成
- DNA 鏈延長一個核苷酸

![image alt](https://image2.slideserve.com/3693475/slide4-l.jpg)

#### Chargaff's rules and double helix
- 嘌呤的數量大致和嘧啶差不多，$N_A = N_T,\ N_C = N_G$
- 富蘭克林等人製備一種濃度很高的DNA溶液，並且用針頭拉出一根纖維
- X射線繞射圖之所以很重要，就是因為呈現出來的圖型很簡單: 一系列呈現X型排列的斑點
- 如果是一般的蛋白質做繞射，這些斑點會像是亂槍掃射一樣隨便
> [!Important] 
> DNA如果分子量和蛋白質一樣很大，那唯一的解釋就是: 這個大分子有規則的重複結構 !! 🧐

- 唯一的悖論就是: 你說DNA是重複的規則，但是如果他有編碼蛋白質，那他的序列應該是不規則的啊
- 因此華克兩人提出一個解決矛盾的方法: 兩條DNA並排，並且嘌呤一定會和嘧啶配對 (寬度固定)
- 因此DNA的結構特色就是: 
   - 一圈大約十個鹼基對，一圈往上升高 $3.32nm$
   - 反平行，3'到5'，另一股就是5'到3'
   - 嘌呤和嘧啶之間氫鍵配對

### 核酸的特性
#### helix
- DNA有不同構相: A、B、Z
- B form是多數DNA的標準型，而**A form很常出現在雙股RNA或是DNA-RNA的雜合核酸**

|DNA型態|B-form|A-form|z-form|
|------|----|---|---|
|旋性|右手螺旋|右手螺旋|左手螺旋|
|一圈多少鹼基對|10.4 bp/turn|11 bp/turn|12 bp/turn|
|一圈有多高|3.4 nm/turn|2.4nm nm/form|4.5 nm/form|
|groove|明顯的 major and minor|有major and minor，但不明顯|只有一個groove|
|直徑|1.9 nm|2.3 nm (較寬)|1.8 nm (較扁)|
|屬於|標準型，predominant form，相對溼度約92%，鹼基和中心軸幾乎垂直|脫水型，鹼基相對於中心軸傾斜20度，結構較緊湊，相對溼度下降到75%|形成zig-zag的型態，通常出現在GCGCGC等重複序列裡面|

![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/DNA_form_0301.png)

#### denature
- 雖然說嘌呤和嘧啶的量相似，但是**GC content**在各個生物中不一定一樣，從22%到73%都有，而這些差異會影響DNA的物理性質
- DNA加熱時會使中間氫鍵斷裂，形成兩條單股DNA，這又稱為denaturation
> [!Important]
> $T_m$ = DNA在denature一半時的環境溫度 🐱


- 在雙股 DNA 中，嘌呤與嘧啶鹼基彼此平行排列，形成 $\pi - \pi$ 堆疊。這種堆疊會限制電子的激發，降低紫外光 (最高吸收峰在 $260 nm$ ) 的吸收，產生 **"減色效應"**
- 當DNA加熱分開，H-bond消失，堆疊消失，吸收光的能力增加

![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/hyperchromic_effect_0519.webp)

- 偕同轉換: DNA denaturing並不是一個一個氫鍵斷裂，而是 "區塊脫落" (因為某一區域的氫鍵斷裂，會使鄰近區域更容易斷裂)
- 因此， $260nm$ 吸光度曲線會 "急遽上升"，呈現S型
- Tm值會隨著 $\frac{G+C}{A+T}$ 的比值升高而升高。所以越多GC，也就是GC content越高，DNA越穩定， $T_m$ 越高，因為氫鍵比較多，DNA比較難分開

#### 補充
- 加熱並非打開雙股的唯一方法，用dimethyl sulfoxide或是formamide (有機溶劑)，以及鹼性環境，都可以破壞氫鍵
- 降低環境鹽分也可以，因為沒有多餘的帶電粒子，兩條鏈上的負電荷就不太會被屏蔽，使DNA不用加熱太高溫就能夠分開
- DNA2的GC content也會影響DNA的密度，通常來說，GC content越高，密度越大，在用 $CsCl$ 做梯度的離心時就可以看出來

#### renature
- renature，或是annealing，就是DNA降溫後重新排列的情況
- 通常來說，會比 $T_m$ 低25度當renature的溫度，如果太高溫，那很有可能繼續分開，但是如果太低溫，單股分子移動速度變慢，又找不到彼此
> [!Tip]
> **quenching** = 把熱的DNA溶液插到碎冰裡面讓他們維持單股狀態 😗

- 除此之外，DNA溶液濃度越高，以及配對時間越長，renature的比例也會越高

#### hybrid
- 如果是ssDNA + ssRNA的結合，那不叫做renature，而是叫做**hybridization**

#### 大小測量
- DNA的大約分子量可以用長度轉換成鹼基對，鹼基對轉換成分子量，也就是說: 

$$
\begin{align}
N(\text{鹼基對}) & = \text{觀察長度}\times\frac{10.4\ \mathrm{\mathring{A}}}{33.2}\\
N(\text{分子量}) &= N(\text{鹼基對})\times 660
\end{align}
$$

- 因為一個鹼基對的平均分子量約為660
##### Metal shadowing
- DNA 是非常細的分子，非常接近電子顯微鏡的解析度極限，因此會用金屬鍍膜
- 概念就是... 
  - 將 DNA 分子鋪在薄膜上，再用重金屬 (如鉑、鈾、鎳) 噴霧撒他 (下雪的概念?)
  - 然後這些金屬沫就會堆積在DNA周圍，使DNA在暗色背景下發亮

![image alt](https://c8.alamy.com/comp/HRF889/viral-dna-HRF889.jpg)

- 這樣就有辦法在顯微鏡下估算DNA的長度了。除此之外，也可以用凝膠電泳來估算分子量

#### C-value paradox
- **C-value**就是每個 **"單倍體細胞"** 的基因組大小
- 不同生物的基因組大小差異極大，但這個大小卻**不一定與生物的複雜度相關**
- genome裡面有大量重複序列、轉座子、偽基因等，並不直接編碼蛋白質 (non-coding)
- 同時，複雜度更多來自基因調控網絡，而非基因數量。這種基因組大小跟生物複雜度不對齊的狀態，被稱為**C值悖論**

![image alt](https://book.bionumbers.org/wp-content/uploads/2014/08/502-f1-GenomeSizesRanges-1.png)

---

## chapter 3
### 訊息儲存
- 中心法則如下: 

```mermaid
flowchart LR
  DNA([DNA])-->|解旋|tc([轉錄])-.->mRNA([產生互補<br>mRNA])-->|修飾<br>離開細胞核|pp([轉譯<br>產生多肽])-->|切割、摺疊<br>轉譯後修飾|protein([蛋白質])
  
  tc-.->rRNA([產生rRNA])-->|和蛋白質<br>結合|su([產生次單元])-->|細胞核外<br>組合|pp
  tc-.->tRNA([產生tRNA])-->|切割折疊|aats([和酵素以及<br>活化的胺基酸<br>產生反應])-->|形成|aat([胺醯tRNA])-->pp
```

> [!Important] 
> ##### 必記 😏
> - DNA在轉錄時，一個為**template strand (anticoding strand, antisense strand)**，一個是**coding strand (nontemplate strand, sense strand)**

#### 蛋白質結構
- 胺基酸由alpha-C為中心，一邊接 $NH_3^+$ ，一邊接 (COO^-)，一邊接 $H$ ，一邊接**R group**
- 胺基酸脫水後連接，以**peptide bond (你也可以說是amide bond)** 相連，多肽分為N端和C端，沒有氫鍵時就是**primary structure**，有氫鍵做成 $\alpha$ -helix，或是 $\beta$ -sheet 時，就是**secondary structure**，方向為N端到C端

![image alt](https://image.slideserve.com/839292/protein-secondary-structure-l.jpg)

> [!Note]
> $\beta$ -sheet有**平行**和**反平行**兩種形式，他們都存在 😗

- **tertiary structure**包含的鍵結很多樣，可以是**van de waal interaction**，也可以是**H-bond**，也可以是**covalent bond**，也可以是**ionic bond**

> GAMT (guanidinoacetate N-methyltransferase) 是creatine (肌酸) 合成的重要酵素，而肌酸在肌肉、心臟與腦中作為能量緩衝分子，透過磷酸肌酸系統快速再生 ATP，以 $\alpha$ -helix 和 $\beta$ -sheet 混合構成， $\beta$ -sheet呈現平行分布的構造 

<iframe src="https://Jacklyn301.github.io/molecular_model/3ORH_Human%20guanidinoacetate%20N-methyltransferase%20with%20SAH.html" width="100%" height="400px"></iframe>

- 蛋白質有時會分成不同區域，並不一定像是globin一樣成為一坨蛋白質，這又被稱為domain
- 這些domain有時可以看到叫做**motifs**的結構，例如所謂的鋅指就是其中一種

> [!Important]
> 如果你說的是functional domain，那分類方式通常只是有功能的一小塊區域 (相當於motif)，並不是一整個三級結構 ! 😗

- 多數蛋白質並非有了自身序列就會自動摺疊，往往需要酵素以及合適的環境
- 但是蛋白質會因為胺基酸疏水或是親水的特性自動摺疊
- 通常來說，Leu、Val、Ile等疏水胺基酸會聚集在蛋白質中間的地方，避免靠近水

> [!Important]
> - **蛋白質折疊的主力，其實就是hydrophobic force**，水分子強迫把所有疏水的東西放在一起
> - **先確保親水疏水，再進行折疊 !** 😲

#### Garrod's experiment
- Archibald Garrod 在 1902 年首次提出**先天性代謝錯誤 inborn errors of metabolism**
- 他發現疾病 (例如研究**alkaptonuria**) 可以因為基因缺陷導致特定酵素缺失，進而影響代謝途徑
- 當時人們以應知道代謝是酵素參與，而它們發現這些代謝疾病似乎有遺傳傾向，因此開始認為gene和酵素有一定的關係

```mermaid
flowchart TB

classDef S fill: #a6a6a6, stroke: #5b5b5b, stroke_dasharray: 5 5
classDef P fill: #ffefad, stroke: #000
classDef E fill: #ffffff, stroke: #000

Phe[Phenylalanine]
Phe-->|透過|Ph(苯丙胺酸氫化酶)
Ph-->|形成|Tyr[Tyrosine]
Tyr-->|透過|Ta(酪氨酸氨基轉移酶)
Ta-->|形成|4hpa[4-hydroxyphenyl-pyruvic<br> acid]
4hpa-->|透過|4hpad(4-羥基苯基丙酮酸雙加氧酶)
4hpad-->|形成|Ha[Homogentisic acid]
Ha-->|透過|ha12d(黑尿酸1,2-雙加氧酶)
ha12d-->|形成|4m3a[4-maleyactoacetic acid]


  Ph-.->A(該酵素缺陷導致苯丙胺酸積累，造成phenylketonuria)
  Ta-.->B(該酵素缺陷導致酪氨酸積累，造成type II <br>tyrosinemia)
  4hpa-.->C(該酵素缺陷導致4-羥基苯基丙酮酸積累，造成type III<br> tyrosinemia)
  ha12d-.->D(該酵素缺陷導致黑尿酸積累，造成alkaptonuria)

class A,B,C,D S;
class Phe P
class Tyr P
class 4hpa P
class Ha P
class Ph E
class Ta E
class 4hpad E
class ha12d E
class 4m3a P

```

- 同時，劍橋科學家 William Bateson 指出alkaptonuria符合孟德爾的隱性遺傳模式，並進一步推動**遺傳學 (genetics)** 這一學科的建立
- 這個實驗和Beadle和Tatum等人用麵包黴 (*Neurospora crassa*) 做出來的實驗假設類似

#### 基因分析
- 在基因分析上也做了一樣的事情。身為子囊菌的麵包黴，在形成2n的合子後會在減數分裂和細胞分裂後生成兩個8個子囊孢子
- 如果將突變的麵包黴和wild type 雜交，而同時該疾病是由單一的基因突變引起，那這8顆孢子，應該就有4顆是突變型
- 後來經過更深一步研究，**從 "一酵素一基因" 假說，變成 "一多肽一基因" 假說**
- 因此，蛋白質還可以作為激素、轉錄因子、細胞膜通道等等

### 如何傳遞訊息?
- Crick發現說，DNA位於真核細胞的細胞核中，但是蛋白質往往是在細胞質中合成。所以一定有東西把DNA的訊息傳到了細胞質
- 他當時注意到了rRNA，但是又發現rRNA是核糖體不可分割的一部份，因此他認為: 

> [!Note]
> 一個細胞中有很多不同種核糖體，而rRNA攜帶特定的訊息，反覆合成同一個蛋白質 ! 🫠

#### Jacob's experiment

- 當然，Jacob等人並不買帳，他們想要證明核糖體並不是訊息載體
- 他們先用 $^{15}N$ 和 $^{13}C$ 等較重的同位素培養細菌，讓這些細菌的核糖體逐漸含有這些標記的同位素
- 然後他們用phage感染細菌，並把細菌轉移到新的培養皿中，這些培養皿含有 $^{14}N$ 和 $^{12}C$，這導致接下來產生的任何新的核糖體都含輕同位素
- 同時利用 $^{32}P$ 標記未來產生的嗜菌體RNA。他們假設，如果Crick是正確的，那會發現只有新的核糖體蛋白質，可以和新的RNA形成核糖體

> [!Tip]
> #### 結果...
> - 後來在輕的核糖體上面 (也就是舊的核糖體)，看到了新合成的嗜菌體RNA
> - 也就是說，這些舊的RNA不僅不可能攜帶嗜菌體的遺傳信息，可能也根本不攜帶任何宿主的遺傳訊息
> - **核糖體從頭到尾基本上就是固定的！** 🧐

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/Francois_Jacob's_experiment_0911.png)

- 後來發現傳遞訊息的RNA，半衰期很短，並且與蛋白質合成同步
- 同時，這些短壽命 RNA 與 DNA 序列相對應，顯示它們是 **"DNA 的抄本"**，更進一步證明他們不是核糖體的固定成分
- 這後來被稱為**mRNA**

### 轉錄
#### mRNA structure
- 通常長這個樣子: 

$$
\boxed{\text{5'-UTR, leader}}-\boxed{\text{coding region}}-\boxed{\text{3'UTR, trailer}}
$$

- coding region對應到的就是DNA的ORF
- 其中，起始密碼子和終止密碼子都是包含於coding region
#### 過程
- 通常分為三個階段: 起始、延伸、中止

|phase|description|
|---|---|
|**Initiation**|酵素辨識promoter (位於基因上游)，pol會在promoter結合，打開雙股螺旋 (約分開12個bp)，然後用NTP建造 |
|**Elongation**|合成時為**RNA本身的5'到3'方向**，轉錄泡隨著RNA pol移動，轉錄完的上游區域會重新變成雙股螺旋，一次一條RNA，一次只拿一股DNA當模板|
|**Termination**|基因末端往往有terminator，會發出終止訊號，並和RNA pol相互作用，使RNA從DNA和RNA pol分離|

- 通常轉錄開始時，RNA 第一個 nucleotide 常常是ATP或是GTP，RNA的5' 保留pppA或是pppG，因為它是 de novo synthesis，沒有 primer
- 它們辨識到底要從哪裡開始轉錄的方式，就是**透過motif來辨識promoter**

> [!Important]
> ##### Most initiations are abortive
> - RNA polymerase 剛開始其實超廢。它常常：
> ```text
> 做2個核苷酸
> ↓
> 失敗 🧐
>
> 做4個核苷酸
> ↓
> 失敗 🙂
>
> 做7個核苷酸
> ↓
> 失敗 💀
> ```
> - RNA常常做一半就掉出去，重新開始，這叫做**abortive initiation**，產生小 RNA。

- 當做到 8~10 nt的時候，這時候 RNA polymerase開始離開 promoter，開始進入穩定 elongation
- 也就是說，剛開始時通常移動速度不會太快，因為這時候要**確保配對的位置是對的**

### 轉譯
#### ribosome
- E.coli的兩個單元大概是30S和50S (沉降係數，離心時辰降到管底的速度)，兩個形成70S的核糖體
  - **small subunit** = 16S rRNA + 21個蛋白質
  - **large subunit** = 23S rRNA + 5S rRNA + 34個蛋白質
- rRNA生存的唯一目的就是變成核糖體，參與催化功能，並不編碼蛋白質

> [!Warning]
> 沉降係數和顆粒質量不成正比，通常來說，關係大致如下: 
> $$\text{沉降係數}\propto(\text{質量})^{\frac{2}{3}}$$

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/composition_of_the_E.coli_ribosome_0911.png)

#### tRNA
- Crick當時想知道到底是什麼東西讓RNA的訊息變成蛋白質的，畢竟還沒甚麼相關的數據和研究
- 他只知道這個分子應該要能辨認RNA，也可以辨認特定的氨基酸。很幸運的是，他的猜測似乎對了 🐱
- tRNA被摺疊成L型三級結構，有兩個功能端，一端就是tRNA的3'，也負責連接胺基酸。另一端是反密碼子區域，可以跟mRNA做互補


<iframe src="https://Jacklyn301.github.io/molecular_model/1EHZ_the%20crystal%20structure%20of%20yeast%20phenylalanine%20tRNA.html" width="100%" height="400px"></iframe>

- 相應的tRNA具體要配對的氨基酸往往是固定的 (不模糊性)，如果該tRNA對應到的氨基酸是alanine，那酵素只能讓alanine何其結合
- 這種酵素通稱為aminoacyl-tRNA synthetase


<iframe src="https://Jacklyn301.github.io/molecular_model/1G59_Glutamyl-tRNA%20synthetase%20complex%20with%20tRNA(Glu).html" width="100%" height="400px"></iframe>


| 特徵     | 解釋  |
| ----| ---- |
| **degeneracy/redundancy**<br>退化性 | 多個密碼子對應同一種胺基酸|
| **unambiguous**<br>不模糊性| 特定一種密碼子只對應一種胺基酸 |
| **universal**<br>廣泛性 | 所有生物共用同一套遺傳密碼，雖然偶有差異 |

#### 轉錄的起始
- translation開頭的codon為AUG
- **Shine-Dalgarno 序列**是細菌 mRNA 上的一段短序列，在AUG上游
- 這些序列不完全是固定的，但是共識序列通常是 `AGGAGG`。它會**和 16S rRNA 的 3′ 端互補配對**

> [!Tip]
> 真核生物沒有Shine-Dalgarno 序列，而是由elF4E蛋白和5'帽結合，吸引核糖體

#### 延伸
- 順序為**A、P、E**
- 起始tRNA在P位點結合，然後延伸的工作在A位點完成
- **peptidyl transferases**負責連接A位點的胺基酸到P位點
- 轉移的過程需要**EF-Tu蛋白和GTP**
- 轉位發生，核糖體往前移一個 codon，**A → P，P → E** 
- tRNA離開核糖體需要**EF-G蛋白和GTP**

|site|description|
|---|---|
|**A 位 (aminoacyl-tRNA)**|新 aminoacyl-tRNA 進入|
|**P 位 (peptidyltRNA)**| 帶有生長中的多肽鏈的 tRNA|
|**E 位 (exit)**|釋放已經卸下胺基酸的 tRNA|

![image alt|697](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/model_of_A_P_and_E_site_of_ribosome_0606.png)


#### 終止
- 當遇到終止密碼子 (UAA, UAG, UGA)，沒有對應的 tRNA
- 釋放因子結合上去，促使多肽鏈釋放
- **RF3** (原核) 會幫助釋放因子離開核糖體，也要靠 **GTP**

![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/initiation_and_elongation_mechanism_in_translation_0606.png)

#### codon bias
- 生物的tRNA有時候會比較偏好某些密碼子，即使密碼子對應的是同一個胺基酸，因為...
  - 不同的tRNA含量有差，使用對應的tRNA比較多的codon，轉譯比較快
  - 高表達量的基因比較偏好那些轉譯不容易錯誤的密碼子
  - 不同動物有不同的密碼子偏好
- 如果你想要大量製造某一個蛋白質，將密碼子修改成E.coli偏好的，就能夠提升表現

#### ORF
- **ORF (open reading frame)** = DNA從起始密碼子到終止密碼子這一段
- 一般來說，一條mRNA可能ORF會有很多個，畢竟你可能可以在一條序列中找到多個起始密碼子和終止密碼子，例如...

```text
5' ───────────────────────────────────── 3' mRNA
      AUG───────UAA                         可能1
          AUG──────────────UGA              可能2
             AUG───UAG                      可能3
```

- 但是對典型的 eukaryotic mRNA，ribosome 通常會**從 5′ cap 附近開始 scanning**，找到合適的 start codon 後開始翻譯
- 因此，如果有一個主要的、較長的 coding region，它就很可能是主要 protein-coding ORF


### 複製和突變
#### replication
- Crick等人在發表論文時，就已經有預測DNA應該會複製，以將訊息傳給子細胞
- 而它們也預測DNA是透過**semiconservative replication**
- 當然，當時還有其他假設，例如**conservative (全保留)**、**dispersive (分散式)**
- 而透過**Meselson–Stahl experiment**，確定了DNA是半保留複製

#### 無害的突變
- 通常無害的點突變分為兩種: 
   - **silent mutation**: 突變後的codon對應突變前的同一個胺基酸，例如 `AAA` = `AAG` = Lysine (先不考慮codon bias的話 😗)
   - **conservative**: 突變後的codon對應突變前codon的胺基酸性質類似，例如 `CUC` = Leucine，`AUC` = Isoleucine，Leu和Ile皆為hydrophobic，蛋白質摺疊時比較不會出問題

#### sickle cell disease
- 一般人的RBC呈現biconcave disc (雙凹圓盤狀)
- 對於同型合子的病患來說，**氧氣充足的情況下，RBC可以維持正常形狀**，但是一旦運動或是氧含量下降，就會變成crescent (新月形)
- 這些血球無法通過capillaries，因此會阻塞、撕破血管壁
- 這主要是因為血球的hemoglobin在氧含量下降時，原本融於水的他們會聚集，形成長纖維

#### 如何驗證
- 利用蛋白質定序得出的。順序大概是: 
  - $\beta$ -globin利用酵素切斷特定肽鍵，形成多段peptides
  - 然後這坨混合物先電泳拉開距離
  - 然後把載體 (紙) 轉90度，再電泳一次，從另一個方向把多肽們拉開
  - 這些多肽會像點一樣散步在紙上，而不同蛋白質，點分布的情形就會不一樣

> [!Note]
> 這就幾乎相當於這種蛋白質的 fingerprint ! 😏

- 所以如果去看看HbA (正常 $\beta$ 球蛋白)，以及HbS (不正常 $\beta$ 球蛋白)，圖譜上就會有差異

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/fingerprints_of_hemoglobin_A_and_hemoglobin_S_0911.png)

#### 序列
![image alt](https://cdn.numerade.com/ask_images/40c7a5ca5a494b1d93ed3e29aa4a4c90.jpg)

- 點突變導致原本正常序列的Glutamate變成Valine，前者帶電，親水性；後者偏向疏水性
- 這導致hydrophobic interaction出現在血紅素之間，他們會聚集成纖維，使紅血球被撐成crecent，甚至破裂

> [!Note] 
> 紅血球易裂開才是造成貧血的主要原因，因為突變的血紅蛋白依然帶有攜氧能力 😗

### 備註: 胺基酸的冷知識
![image alt](https://www.sb-peptide.com/image/Amino-acid-periodic-chart.jpg)
#### Leu和Ile的愛恨情仇
- 這兩個長的很像，性質也類似
- 但蛋白質在摺疊、形成 secondary structure 或 packing 時，Ile 的 $\beta$ -carbon 周圍已經塞了一個 methyl group
- 這會讓它的側鏈比較 bulky，靠近 peptide backbone，**也就是比較 "卡"**


> [!Tip]
> - 🧬 Ile：「我要轉一下。」
> - 🧬 Backbone：「這裡沒位置。」
> - 🧬 Ile：「那我往旁邊。」
> - 🧬 Neighboring residue：「也沒位置。」
> - 🧬 Ile：「…… 😗」

#### OH和SH
- 相對來說，free的SH和free的OH比起來，更有攻擊性
- 也就是說，cystenine的攻擊性可以說是20種氨基酸裡面最強的
- 但是由於多數的-SH會變成雙硫鍵，因此很少Cys可以參與化學反應

#### Pro的叛逆
- proline的側鍵包含一個**吡咯烷環 (pyrrolidine ring)**，它的氮原子與 $\alpha$ -碳同時連接，形成一個五元環
- 由於他是二級胺 (secondary amine)，所以在形成residue時，就沒有H可以提供H-bond
- 同時，proline 的環結構使得 $\phi$ 角幾乎固定，主鏈不能自由旋轉 (原來是結構殺手 🤣)
- 但是正因為他很硬，這件事情有時候反而非常有用
- 例如在**某些turns、loops、bends裡面，Proline 可以幫助蛋白質形成特定幾何構形**


---

## chapter 4
### restriction endonuclease
- Stewart Linn在1960年代發現E.coli的一個限制酶
- 之所以被稱為 "限制"，是因為這種酵素的主要功能就是**把病毒入侵的DNA "切掉"**，而且是切在virus DNA的中間，所以叫做 "內切酶"
- 但是這個限制酶並無法準確切割特定位點，找到這種精準剪刀的幻想也已失敗告終 🫠

#### HindII
- *Hin*dII 來自 Haemophilus influenzae 的第二種限制酶 **(H + in + Rd菌株 + II)**

> [!Important]
> Type III 的限制酶往往是在辨識序列 "之外" 的區域 (例如20幾個bp後) 切割，而中間這20bp具體的序列是什麼並不影響酵素辨識 ! 🐱

- 產生的是平末端，如下: 

```text
    ↓
GTPy PuAC
CAPu PyTG
    ↑
```

- 其中，Py代表嘧啶 (C/T)，Pu代表嘌呤 (A/G)
> [!Important]
> 這些限制酶只看你的序列是什麼，但凡有符合的序列就會切開，形成DSB，不管是不是在想要保留的基因序列上 ! 😗

- 如果要切的限制位點要很長，例如*Not*I (`GCGGCCGC`，共8個鹼基對)，那麼平均來說要找該序列的機率更低，切出來的DNA片段也會更長
> [!Note]
> 這種restriction sequence很長的限制酶，又被稱為**rare cutter** 🐱

- 然而，有些限制酶明明辨識同一個位點，但是切割的區域不一樣，這時候被稱為**neoschizomers**或是**heteroschizomer**，例如: 
  - *Sma*I 辨識 `CCCGGG`，切在中間 → 產生 平端 (blunt ends)。
  - *Xma*I 也辨識 `CCCGGG`，但切在不同位置 → 產生 黏性端 (sticky ends)
- 相反，不同來源的限制酶，辨識同一個序列，而且切割位置也相同，這被稱為**isoschizomer**，例如: 
  - *Sph*I 和 *Bbu*I 都辨識 `GCATGC`，並在同樣位置切割

> [!Note]
> sticky end通常更容易把兩個不同的DNA分子連接在一起 🧐

- 它們通常辨識的序列為**回文序列 (palindrome)**，也就是一股從左到右讀，和另一股從右到左讀是一樣的


|類型|定義|特徵|舉例|
|---|---|---|---|
|5′ overhang|在 DNA 的 **5′ 端留下單股突出序列**|突出端帶有磷酸基，容易與互補序列配對|EcoRI等限制酶切割|	
|3′ overhang|在 DNA 的 **3′ 端留下單股突出序列**|突出端帶有羥基 (-OH)|KpnI等限制酶切割|


#### Restriction-Modification system
- 限制-修飾系統，又被稱為**R-M system**
- 這套系統是為了確保細菌不會手殘把自己的DNA切掉了，通常配備: 
  - **Restriction enzyme**: 負責辨識DNA的限制切點序列並切割
  - **DNA methyltransferase**: 在自己 DNA 的限制酶辨識序列上，加入甲基 (methyl group)，限制酶就無法切割已被甲基化的序列

> [!Tip]
> #### 等一下...
> - Q: 如果酵素可以讓兩股都甲基化，那DNA複製的時候，最終產生的DNA不就只會有一股是有甲基化的?
> - A: DNA 複製後，確實會先產生**半甲基化 DNA** (舊股有甲基、新股沒有)，所以會有酵素 (如DNMT1)，專門負責辨認半甲基化 DNA，並且在新股上補上甲基

##### 舊甲基化 vs 新甲基化

|enzyme|舊甲基化酶|新甲基化酶|
|---|---|---|
|function|辨認半甲基化 DNA，它看到舊股有甲基，就在**新股同樣位置補上甲基**|在需要建立**新的甲基化標記**時 (例如發育或分化)，會在原本沒有甲基的 CpG 上加上甲基|
|example|DNMT1|DNMT3|


### 如果vector是plasmids
#### 第一個成功的DNA重組: Boyer 和 Cohen
- Boyer 和 Cohen要證明外源 DNA 可以被剪接到質體中，並在大腸桿菌裡穩定存在，具體步驟大概是: 

```mermaid
timeline
title recombinant DNA assembled in vitro 🦠
   選擇載體質體: 利用小型質體 pSC101: 該質體具備<br>抗四環素<br>抗性標記
   選擇另一個載體: 利用小型質體 RSF1010: 該質體具備<br>抗鏈黴素<br>抗性標記
   切割 DNA 片段: 利用限制酶 EcoRI<br>切割兩個質體: DNA ligase<br>將磷酸二酯鍵封合
   轉入大腸桿菌: 使用 CaCl₂ 處理<br>增加細胞膜通透性: 熱震法促進<br>質體進入細胞
   篩選與表達: 在含抗生素的<br>培養基上生長: 這些攜帶兩種<br>抗性基因的細菌<br>可以存活
```

> [!Note]
> - DNA ligase需要ATP才可以把SSB接起來
> - 還要確保你的單股中，5'一定要有磷酸根

#### transformation 的方法
- 這些vector通常會有ori，而外來基因沒有。也就是說，只有當外來基因成功和vector重組，才有表現的可能
- 讓DNA可以transformation成功的方式大概有: 
  - 利用 CaCl₂ 等鈣鹽，讓細胞膜通透
  - 利用電的，迅速在細胞膜上弄出小洞 (electroporation，電穿孔)，然後期望DNA可以進去 🙂


#### pBR plasmid series
- Boyer 和他的同事們建立了一套載體，被稱為 **pBR 質體系列 (pBR plasmid series)**
- 這些質體，例如經典的pUC vector，有不少特徵: 
  - **屬於小型 DNA**: 去除大片段不必要的序列，大約留下 4–5 kb，方便操作與轉染
  - **抗生素抗性基因**: 例如 ampicillin resistance ( $Amp^R$ )，可用來篩選帶有質體的細菌
  - **多重限制酶切位點 (MCS)**: 在 lacZ 基因區域插入多個限制酶切位點，方便插入外源 DNA
  - **lacZ 報導系統**: 插入外源 DNA 會破壞 lacZ，導致 $\beta$ -galactosidase 活性消失，因此可用**藍白篩選**判斷是否成功插入

![image alt](https://i.pinimg.com/736x/71/35/46/7135463fceb69633d141aa63e8fa4c75.jpg)

> [!Important]
> - 藍白篩檢用的是人工合成的半乳糖苷 (X-gal)，當他被 $\beta$ -galactosidase分解時，會釋放出半乳糖以及染料 (indigo dye)，菌株就會是藍藍的 🔵🔵
> - 如果你的外來基因有成功插入，那就造不出 $\beta$ -galactosidase，所以**轉殖成功的菌株是白色的** 🐱


#### 假陽性問題
- 有時候，看到白色菌株，並不一定代表是轉殖成功的菌株，這又被稱為**false-positive**
- 由於在製備 vector 的過程中，DNA 末端可能被核酸酶 **"輕微咬掉"** 幾個核苷酸。這種降解不一定影響整個質體的封閉循環，但可能破壞 lacZ’ 的閱讀框或關鍵序列
- 如果這些稍微受損的 vector 沒有插入外源 DNA，而是直接自己封閉成環狀，此時 lacZ’ 基因已經被破壞。菌株呈現白色
- 但其實裡面沒有外源基因，因為質體已經 "受損一點" 了 
- 甚至，如果vector重組回去，同時上面有抗藥性抗性基因，原本寄望可以用 **"抗生素抗性基因的細菌 = 轉殖vector成功的細菌"** 的篩選機制就會失敗

#### alkaline phosphatase 解決
- 在 DNA 片段的連接過程中，DNA ligase 需要 5'-磷酸 和 3'-OH 才能形成磷酸二酯鍵
- 如果 vector 自己有 5'-磷酸，就可能在沒有 insert 的情況下，自己又組回去 💀
- 為了增加成功率，研究人員會使用**鹼性磷酸酶** (alkaline phosphatase, AP)
- 他會**移除 vector 末端的 5'-磷酸**，只留下 3'-OH。這樣 vector 就不會自己組回去
- 然後，只有當外源 DNA insert 提供 5'-磷酸時，ligase 才能完成連接
- 雖然**連接後會有一股無法形成磷酸二酯鍵** (剛剛已經提及ligase無法在5'沒有磷酸基的情況下形成phosphodiester bond)，但這個問題，細菌會解決 🙂

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/alkaline_phosphatase_prevents_vector_religation_0911.png)

| 篩選方式 | 原理 | 優點 | 限制/缺點 |
| --- | --- | --- | --- |
| **抗生素篩檢** | 向質體載體中加入抗生素抗性基因 (如 $Amp^R$ )。只有成功帶有質體的細菌能在含抗生素的培養基上存活 | • 簡單直接<br>•  可有效區分「有質體」 vs 「無質體」 | • 無法區分「有質體但無外源基因插入」的情況<br>• 只能確認轉殖是否成功，不保證插入片段存在 |
| **藍白篩檢** | 利用 lacZ 基因編碼的 $\beta$ -galactosidase。若外源 DNA 插入破壞 lacZ → 菌落呈白色；若 lacZ 完整 → 菌落呈藍色(在 X-gal + IPTG 培養基上) | • 可區分「有插入片段」 vs 「無插入片段」<br>• 比抗生素篩檢更精細 | • 可能出現如 lacZ 自身突變、培養條件影響等問題<br>• 仍需 PCR 或測序確認 |


> [!Tip]
> ##### 補充DNA ligase
> - DNA ligase可以透過和AMP結合，形成活化的酵素。這個酵素會把AMP直接接上5'黏性末端的磷酸基上
> - 然後這個高能磷酸基就有能量形成新的磷酸二酯鍵

### 如果vector是phage
- phage在基因轉殖上並不是透過觀察菌落，而是觀察plaques (嗜菌斑)，也就是細菌死掉溶解後形成的無色斑塊

> [!Important]
> **一個圓形噬菌斑 = 一個單一噬菌體的擴散結果** 🐱

- phage (例如 $\lambda$ ) 的優勢就是相對於質體來說，可以**插入更大的外來基因** (畢竟一個超大質體通常是沒甚麼機會塞到細菌裡面)
- 但是phage的頭部也就那樣大，頂多裝20 kb
- 如果你要克隆基因組這種超大的東西，當然是能一次複製長一點的片段比較輕鬆阿，所以用phage就是一個不錯的選擇 😗

> [!Tip]
> - 🧑‍🔬: 「Plasmid，今天要克隆一段 DNA，大概 5 kb。」
> - 🧬: 「可以，交給我。😗」
> - 🧑‍🔬: 「那如果是 20 kb？」
> - 🧬: 「……勉強試試。」😐
> - 🧑‍🔬: 「30 kb 呢？」
> - 🧬: 「……」
> - 🧑‍🔬: 「Plasmid？」
> - 🧬: 「你要不要考慮一下別人。」💀

- 天然 $\lambda$ phage 基因組約 48.5 kb，其中有些區域 (又被稱為stuffers) 可以刪除，騰出 10–20 kb 的空間
- 用限制酶切開 vector，產生可插入外源 DNA 的位置，將想要的基因片段嵌入到 phage vector
- 同時，原本的基因組變成兩段，也就是left arm和right arm，這兩個arm都有cos site，這能讓 DNA 被高效率打包進 phage 顆粒

> [!Important]
> - Q: cos site是什麼? 🐱
> - A: cos site是病毒在滾環複製，產生連續的多個基因組後，terminase把這條鏈切回一條條genome的切點。 🐱
> - Q: 那你要怎麼確定，切掉stuffers後，其他兩個arms不會自己接起來? 🧐
> - A: 如果只有兩個 arms自己接起來，DNA 長度會很短，**過短的DNA並沒有機會被封裝在phage裡面** ! 😏

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/cloning_and_gene_transferation_through_phage_0911.png)

#### 轉印噬菌斑
- 先在噬菌斑培養皿上覆蓋硝酸纖維素膜，以將DNA轉印到膜上面，並標記好膜的位置以對應原始斑點
- 用鹼性溶液處理，使 DNA 解旋，變成單股，最後烘乾或紫外線交聯固定 DNA
- 而且還要加入很多非特異性的DNA和蛋白質浸泡膜，好先飽和未被target的區域
- 主要原因是因為，probe 不是一個非常有禮貌的客人，他可能會...

> [!Tip]
> - 🧬 probe: 「這裡有 DNA。」
> - 🧬 probe: 「那裡也有 DNA。」
> - 🧬 probe: 「這個 filter 看起來也不錯。」
> - 🧬 probe: 「我隨便黏一下。😗」

- 結果 filter 上很多非 target 的 DNA、protein、甚至 membrane binding sites 都可能造成 nonspecific adsorption
- 這會讓培養皿看起來非常髒，到處都是probe 💀
- 所以最好的方式就是先把位置停滿，常用的有鮭魚精 DNA (salmon sperm DNA) 或牛血清白蛋白 (BSA)
- 這些分子不會和探針特異性結合，但能佔據潛在的黏附位點
- 當探針結合在真正的目標DNA上並雜交時，用X-ray檢測時就會讓該噬菌斑**呈現黑色**

> [!Important]
> 被標記成功，呈現出**黑色的噬菌斑**，這個情形也被稱為 positive hybridization

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/selection_of_positive_genomic_clones_by_plaque_hybridization_0912.png)

> [!Note]
> 除了用probe，如果該病毒在複製時還會產生特定的蛋白質，那可以**用 "抗體" 去標記這些蛋白質** 😏

### 如果vector是cosmid
- cosmid其實就是 **cos** site 和 plas**mid** 的結合。有嗜菌體的cos site可以把自己包裝在phage裡面，也可以在細菌身體產生質體，因為有質體的ori
- 這種vector也是在基因編輯好，in vitro包裝好後才去感染病毒
- 由於這種vector幾乎除了 $\lambda$ phage基因組的cos site之外，其他都被切掉了
- 也因此，當cosmid被包裝入病毒，然後DNA被注入細菌身體裡後，**他連感染細菌後自我複製的能力都沒有**

#### M13 phage vectors
- 該載體同樣有*lacZ*基因，也有多個複製位點 (multiple cloning site)

> [!Important]
> 多個複製位點的意思，就是一DNA區段包含各種噬菌體RNA聚合酶的promoter，也就是說，可以選不同種phage幫忙包裝編輯的基因，並且感染和成功複製病毒 😏

- 他的來源，M13 bacteriophage 是感染 E. coli 的**絲狀(filamentous) 噬菌體**，而的基因組是環狀的 **"ssDNA"**
- 在轉殖入細菌後，產生並從細菌身上釋放出的也是 **"ssDNA"**，這些被釋放的單股被稱為**positive (+) strands**，而身為模板留在細胞的是**negative (-) strand**
- 但是當他感染E.coli後，會在細胞內部形成dsDNA，然後在病毒釋放出來時，複製的基因是以單股的ssDNA形式釋放

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/obtaining_ssDNA_by_cloning_in_M13_phage_0912.png)

### 如果vector是phagemids
- 和cosmid類似，也同時有噬菌體包裝以及質體的特徵
- 舉例來說，**pBluescript phagemid** 包含: 
   - T3 & T7 phage promoter
   - 21種位於*lacZ*的限制酶切位
   - *lacI* (repressor，控制*lacZ*表現)
   - $Amp^r$ (抗生素抗性)
   - 基因組為ssDNA的f1噬菌體之ori (所以也可以用f1 phage來轉殖，形成ssDNA)
   - 大腸桿菌自身的ori

#### 嵌入超超超大DNA的載體
- 這些載體可以嵌入數十萬個bp的DNA
- 常見的例子有:
   - *Agrobacterium tumefaciens* (根癌農桿菌) 的**Ti vector**
   - **酵母菌人工染色體 (YACs)**
   - **細菌人工染色體 (BACs)** 

### probe 和 cDNA
- 通常來說，我們當然希望核酸探針能夠完全互補
- 不過呢，要是你不那麼一板一眼，覺得 "啊有九成核甘酸有成功雜交就好啦 😗"，是有辦法的，也就是說，你可以降低所謂的**stringency**，例如用溫度: 
   - **低溫 (低嚴格度)**，探針和目標序列即使只有部分互補，也能暫時穩定結合。這可能出現非特異性結合，導致**背景訊號高**
   - **高溫 (高嚴格度)**，只有完全互補的探針-目標序列能穩定存在，同時部分互補的氫鍵在高溫下會斷裂。這會使**訊號更乾淨，特異性更高**

#### 如何解決 "知道多肽卻不知道基因序列"
- 讓我們舉一個有趣的例子，我想要找出某短肽對應的基因序列，如下: 

$$Met-Glu-Trp-Ile-Cys-Pro$$

- 由於degeneration，因此可能有多個密碼子對應同一個胺基酸，因此我們看完了密碼子表後，將該胺基酸對應的密碼子個數寫下來: 

$$1-2-1-3-2-4$$

- 同時，我們發現proline有四個密碼子都對應 (CCA、CCU、CCC、CCG)，而且他身為末端的胺基酸，因此**原本所謂的 "18核甘酸探針"，我只需要修成 "17核甘酸探針"，並且確保以 "CC" 結尾**
- 剩下的胺基酸，再把對應的密碼子個數 "全部相乘": 

$$1\times 2\times 1\times 3\times 2 = \boxed{12}$$

> [!Note]
> 所以你為了定序該短多肽背後的基因序列，你需要12種序列不同的探針 😗


#### cDNA是啥東西
- cDNA = complementary DNA、copy DNA，就是**從RNA反轉錄過來的DNA**
- 所以基本上，形成cDNA的中心法則就是... 痾，你要有mRNA模板，還要有一個反轉錄酶 (reverse transcriptase)
- 當然，就跟所有的聚合酶一樣，反轉錄酶沒有primer就啥也不會。我們知道mRNA通常有個poly-A tail，那我們的primer... 就是用一個poly-T (或是叫做oligo-dT)去跟mRNA互補 🤣
- 等到反轉錄酶合成一單股的DNA，接下來就是用**RNAse (通常是ribonuclease H)** 把原本的mRNA模板吃掉
- 而這些酵素吃完後殘留的RNA小片段，就形成另一股cRNA的primer

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/synthesis_of_cDNA_0912.png)

#### nick translation
> [!Tip]
> - Q: 那我們讓DNA pol登場合成另一股DNA，但是這些引子短短的又散布在各區，要是pol前進時，前面有另一個片段怎麼辦? 🧐
> - A: 那就前面拆掉，後面繼續蓋 🙂
> - Q: ？？？？　💀

- Nick就是所謂的單股斷裂 (SSB)
- DNA polymerase I 在合成另一股cDNA時，可以同時進行: 
  - **5’→3’ exonuclease** 活性: 往前移除原本的核苷酸
  - **5’→3’ polymerase** 活性: 在同一位置補上新的核苷酸

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/graph_of_nick_translation_during_the_synthesis_of_DNA_by_DNA_pol_I_0912.png)

#### 那如何送到vector上面? 🫠
- 首先，你要有sticky end吧，但是由於cDNA沒有，除了用限制酶來接 (通常不太好，因為往往會破壞基因)，也可以用**terminal deoxynucleotidyl transferase (TdT)**
- TdT 可以**直接在sscDNA 的 3'-OH 末端加上核苷酸**，這種加上尾巴的方式，通常就是一直加同一個核甘酸 (例如poly-dC)
- 然後在vector的其中一單股末端**加上互補於該尾巴的核甘酸** (例如poly-dG)
- 手刻stick-end完成 !! 🐱

#### Rapid Amplification of cDNA Ends
- 以上這個技術可以用在**RACE**上面
- 也就是利用已知的部分 cDNA 序列，透過特殊的引子設計與 PCR 擴增，延伸並 "捕捉" 未知的端序列
- 通常就是5'-RACE和3'-RACE: 
   - **5’ RACE**: 先將 mRNA 逆轉錄成 cDNA，再在 5’ 端加上 **adaptor (接頭序列)**，利用 adaptor 特異性引子 + 已知基因內部引子進行 PCR
   - **3’ RACE**: 利用 mRNA 的 poly-A 尾巴，加上 **poly-dT adaptor** 引子，與基因內部引子一起 PCR 擴增

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/RACE_procedure_to_fill_in_the_59-end_of_cDNA_0912.png)

### PCR (沒錯又是他) 🙂
#### standard PCR
- PCR由Kary Mullis等人在1980發明，是為了擴增DNA，才可以在電泳時清晰觀察到分子的位置
- 首先需要有一個在DNA denature時不會變性的polymerase，例如*Taq* pol (來自溫泉菌 *Thermus aquaticus*)
- 會用寡核甘酸序列oligonucleotides，當作**DNA primer**
- 需要的有:
> - primer
> - 目標DNA
> - 耐熱的DNA polymerase
> - 四種dNTPs

- 步驟大概如下: 
   - 95攝氏度: denature DNA
   - 50攝氏度: primer annealing
   - 70攝氏度: *Taq* pol activate
   - 無限循環 🙂

![image alt](https://microbenotes.com/wp-content/uploads/2022/07/Polymerase-Chain-Reaction-PCR.jpg)

#### RT-PCR
- 也就是克隆出cDNA
- 他與一般的PCR差別在於，一開始的時候會把mRNA拿去當模板逆轉錄
- 在逆轉錄出單股cDNA後，再利用引子和聚合酶把cDNA變成雙股
- 然後後面就跟標準PCR了

> [!Tip]
> ##### 我甚至可以加上限制切點!
> - 我可以在**引子的後端 (也就是未與模板配對的地方)，加入某個限制酶的黏性末端**，這樣在複製完後的cDNA可以直接轉殖到vector上
> - 甚至，我**兩端的引子攜帶的限制酶切為序列可以不一樣**，這確保了方向性，不會讓cDNA接反 ! 😏

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/using_RT-PCR_to_clone_a_single_cDNA_0913.png)

#### Real-Time PCR
- 也就是即時螢光定量PCR
- 通常會在模板的DNA解璇後，在上面加上一個probe，這個probe通常連接兩樣東西: 
  - **螢光標記 (fluorescent tag):** 位於引子5'，其可以往外散發光子，產生螢光
  - **淬滅標記 (quenching tag):** 位於引子3'，其可以吸收螢光標記的能量，使之螢光消失
- 由於該聚合酶有**5'-3'polymerase**活性，也有**5’→3’ exonuclease**，當聚合酶在合成另一股DNA時，會接近probe
- 而他不會因此停止聚合，而是將前方的核甘酸剪掉，在後面換上新的
- 因此，**接近5'的螢光標記會先被pol剪下來，脫離淬滅標記**
- 這使得該螢光標記重新有了發光的能力

> [!Tip]
> 不斷循環和標記下去，樣本裡面的螢光偵測數越高，複製的DNA就越多 ! 😏

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/process_of_real-time_PCR_0913.png)

### 表現克隆基因的方法
- 通常有些插入基因的載體中，會在上游加上啟動子 (例如lac promoter)
- 然後一旦加入IPTG，該轉殖後的細菌就可以表達該基因

#### 為什麼需要Inducible Expression Vectors
- 有時候要有辦法控制基因什麼時候可以開，什麼時候可以關
- 就算你的產物對細菌不產生實際毒性，天天要他表現也會累死這隻細菌，反而減少該基因的產量
- 而且如果蛋白質太多，蛋白質可能會形成不溶於水的聚集體
- 科學家在希望細菌表達基因時，會加入IPTG，使啟動子接合到pol上

> [!Important]
> - 但是有時候會出現leaky的狀態，也就是即使沒有加IPTG，也有可能會表現一點點 🙂
> - 所以其中一個方式就是在你的operon裡面額外加上一個*lacI* gene，這樣在表現你想要的基因時，repressor也會一起被轉錄出賴，並且加強該基因的抑制

#### 混合型的promoter
- lac promoter有一個問題，就是他的活性太弱了
- 因此後來又做了一個叫做**tre promoter**的東西，也就是可以被IPTG誘導，但是活性有trp operon的強度
- $P_{BAD}$ 是一種可以被阿拉伯糖誘導的啟動子，在一些實驗中，會把綠**色的螢光蛋白 (GFP)** clone到 $P_{BAD}$ 載體中
- 這樣，隨著阿拉伯糖濃度增加，電泳上螢光條紋的信號也會增強

#### 溫度控制型promoter
- 有些promoter是屬於溫度敏感型，例如 $\lambda$ phage promoter $P_L$ 
- 該基因轉殖到細菌裡面時，會在載體上加入*cI857*，也就是這個promoter的repressor
- 如果溫度較低 (32攝氏度)，這個repressor就會活化，阻遏promoter，z防止轉錄
- 如果溫度較高 (42攝氏度)，repressor在此環境下會失去功能，使operon被開啟

#### fusion protein
- 有些蛋白不一定只是原序列，往往會有不必要的東西在上面
- 例如，你以藍白篩檢的質體為主時，限制酶切點在lacZ基因裡面，最後轉錄出來的蛋白就是 "目標序列 + 部分 $\beta$ -galactosidase"
- 即使是混合蛋白，但是混核蛋白有時是有用的
- 例如 **"寡組胺酸表現載體"**，這載體在基因轉殖時，會在MCS的上游有一段His的短連續序列 (通常是六個)
- 由於寡組胺酸對鎳 $Ni{2+}$ 有很強的親和性，因此在做親和性的層析時，只要打碎細菌，然後把一坨混合物倒入管柱，就很容易把這些有標記的蛋白質析出來
- 而His tag是可以被去除的，通常用的是enterokinase (蛋白酶的一種)，把His tag切掉

![image alt](https://www.evitria.com/app/uploads/2022/11/purification-his-tagged-proteins.png)

- 而lacZ部分片段也有它的用處。例如可以用他的特殊性，以 "抗體特異性" 篩選

```mermaid
timeline
title 篩選噬菌斑 
  blotting: 將培養板上的<br>噬菌斑中的蛋白質<br>轉印到濾膜上: 濾膜就像是一張<br>「複製版」，保留了<br>各斑點的蛋白分布
  抗體檢測: 將濾膜與特異性<br>抗體孵育，抗體<br>會專一性地結合<br>到目標蛋白: 接著再加入帶<br>標記的 protein A<br>它會結合到抗體的<br> Fc 區域，讓訊號<br>可以被偵測
  autoradiography: 將濾膜放到感光片上<br>標記的 protein A<br>會顯示訊號: 最後得到的影像<br>能指出哪個噬菌斑<br>含有目標蛋白
```

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/synthesize_and_detect_positive_lambda_gt11_clones_by_antibody_screening_0912.png)

#### 真核生物基因的問題
- 其中一個狀況是，細菌產生某轉殖基因的蛋白質時，完全有可能把他視為垃圾分解掉
- 抑或是，這些蛋白質在細菌體內也沒有適當折疊的，反而可能因為疏水作用，這些外來蛋白質紛紛抱團取暖，形成一坨不溶於水的廢物

<!-- 我知道我講的很粗暴但就是這樣喔呵呵 🙂 -->

- 這時就可以使用**shuttle vector**，該載體在細菌和酵母菌中都可以表達
- 這樣，當外來基因轉殖入酵母時，他會幫忙比較正確的折疊以及修飾

> [!Note]
> ##### 舉例: 2-micron plasmid
> - 該質體同時有yeast的ori，也有pBR322的複製起點 😗

- 把vector轉殖入真核生物的方法有以下方式: 
   - DNA混合磷酸鹽buffer，加入鈣鹽**產生沉澱** ( $Ca_3(PO_4)_2$ )，然後讓細胞把這些混著DNA的沉澱吃下去
   - 用脂肪顆粒泡 **(liposomes)** 包著DNA，然後等著細胞把脂質溶到細胞膜裡面
   - 植物的轉殖方式主要是把包裹著DNA的金屬顆粒射進植物細胞裡面 **(biolistic)**，通俗來說就像是中彈 🫠

#### baculovirus
- 他是一種有超大環狀DNA genome的病毒，當他感染毛毛蟲時，他在毛毛蟲身體內表現自身蛋白質 (polyhedrin，多角體蛋白) 的速度快的驚人
- 所以科學家就覺得 "媽的他的promoter一定很神"，然後就把這個promoter納入vector

### Ti plasmid
- 如果是剛剛講的shutter vector，人家好歹在細菌和真菌裡面都可以用，但是偏偏植物看不懂
- 如果要轉殖於植物，就需要用到Ti plasmid
- 根癌農桿菌 (*Agrobacterium tumefaciens*) 會把Ti plasmid感染到植物細胞，隨後該plasmid上面的基因片段-- T-DNA，嵌入到植物基因組
- T-DNA上的促進植物生長的基音就會讓細胞瘋狂分裂
- T-DNA也有製造合成**鴉片鹼 (opines)** 的酵素，以當作細菌自己的食物來源。同時，該基因也有一個很神的promoter
- 然後，一樣的，腦子很靈的科學家就想透過Ti plasmid，以及那很神的promoter，**把抗殺草劑或是控制果實成熟的基因插到裡面去**

![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/Ti-plasmid_structure_0603.png)

---

## chapter 5
### 分開分子的方法
#### Gel Electrophoresis
- 如果想要從一堆DNA或是RNA裡面純化出特定一段，就可以用電泳分離片段
   - 用comb在agarose上弄出well (或是slot)
   - DNA/RNA從負極走到正極
   - 分子小的跑得快，分子大的跑得慢 (**主要是因為網格導致的阻力**)
   - 可以用跑的距離估算分子量
- 會染色DNA，例如用Ethidium Bromide，然後用UV去照
- 在分的時候，為了預估DNA大小，會在最旁邊一格well加入marker
- 也有可能會用crystal violet (只是這比較少用)

$$\log(M) = a-b\cdot d$$

- 其中， $M$ 為DNA片段大小， $d$ = 遷移距離， $a$ 和 $b$ 是由marker校正得到的常數
- 當然，在小片段 (<100 bp) 或超大片段 (>20 kb) 時，關係可能偏離線性

> [!Note]
> - 當然也有蛋白質電泳，只是相對來說稍微複雜些
> - EtBr可能是致突變劑 💀
> - RNA其實也可以電泳，只是它很容易水解，所以在製造樣本時盡量乾淨

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/analysis_of_DNA_fragment_size_by_gel_electrophoresis_0913.png)

#### 為啥要用PFGE
- DNA就像是義大利麵一樣，越長就越容易在提取時斷給你看
- 而且，普通 agarose gel 在持續電場下，DNA > 30–50 kb 幾乎不會分開 (想想看頭髮卡在排水網上的畫面 🙂)
- **pulsed-field gel electrophoresis** (PFGE，脈衝場凝膠電泳) 可以透過不斷改變電場方向，讓大分子DNA重新定位
- 這樣它們可以逐步鑽過凝膠網格，依照大小分開
- 這種電泳甚至可以分離細菌的整個genome
- 只是這種電泳就是要跑很久... 要十幾個小時 🤣

> [!Tip]
> ##### 想像一下: 
> - Q: 如果你懶得撿排水網上的頭髮怎麼辦? 
> - A: 用水沖進去? 
> - Q: 可是它會卡住阿。
> - A: 那我用蓮蓬頭，然後刷刷刷刷那樣不連續的沖排水孔 😗

#### 那SDS-PAGE是啥? 
- 是 **"利用SDS處理過的聚丙烯胺凝膠電泳"**，主要分離的不是核酸，而是蛋白質
- 而且蛋白質在分離之前還會用**sodium dodecyl sulfate (SDS) 處理**，讓多肽帶負電
- 跑完後的多肽是看不見的，所以會用**Coomassie Blue**染色，產生條紋
- 同樣的，它通常也有marker，以千道爾頓為單位，顏色多樣

> [!Note]
> - 簡單來說，把他當成清潔劑，他會把一條一條多肽獨立分開，並且讓所有多肽上都布滿負電荷
> - 和核酸的電泳一樣，短得多肽跑得快，長得多肽跑得慢 😏

![image alt](https://media.geeksforgeeks.org/wp-content/uploads/20240209122237/SDS-PAGE.png)


|特性|Agarose|Polyacrylamide|
|---|---|---|
|澆灌凝膠|水平|垂直|
|毒性|無毒|單體有神經毒性|
|孔洞|大|小|
|均勻度|較差|非常均勻|
|解析度|中等|極高|
|適合分離|大分子DNA|小分子蛋白質<br>或是大分子DNA|


#### 二維凝膠電泳
- 雖然SDS-PAGE分離多肽挺不錯的，但是這些分離的多肽屬於 "分子量相似"，因此即使在同一個條紋上的多肽，依然是很複雜的混合物
- 所以有科學家乾脆讓蛋白質跑兩次電泳，而兩次的聚丙烯胺濃度和pH值有所差異，只是這不能用SDS，因此無法分離單一的多肽
- 因此二為凝膠電泳就是解決這個問題。具體來說就是: 
  - 先用細管凝膠做出有pH梯度和電場的環境，讓這些蛋白質在管中走到屬於自己的**等電點 (isoelectric point)** 上
  - 這一步驟又稱為**等電聚焦 (isoelectric focusing)**，通常需要非常強的電壓
  - 然後把該凝膠取出，進行常規的SDS-PAGE
  - 此時，膠盤上的每一個點，就是一個蛋白質 
  - 當然，在實際上跑的時候，實驗的誤差可能會導致蛋白質脫尾

![image alt](https://www.creative-proteomics.com/blog/wp-content/uploads/2018/03/2D-Electrophoresis-cover.jpg)


### 色層分析法
- 蛋白質有三個維度特性: **電荷、大小、親和性**

#### 離子交換層析 (ion exchange)
- 主要利用**樹酯 (resin)**，根據物質的電荷進行分離
- 這些樹酯上面通常有一些特定的基團，**例如DEAE (二乙胺基乙基)** 帶有正電荷，可以把帶負電的物質分離出來，這叫**陰離子交換層析**
- 至於層析後到底要怎麼把欲保留的蛋白質從resin上取下來? 主要就是用**極濃的鹽類水溶液把他們 "洗 (eluted)" 出來**，或是**改變沖洗液的pH值**
- 在elution時，沖洗液的濃度會越來越高，並且 "分次收集" 
- 如果收集的東西是酵素，你可以用底物的反應情況 (照分光光度儀推測反應速率)

![image alt](https://api.intechopen.com/media/chapter/44033/media/image5_w.jpg)

- 當然，也可以用帶有負電荷基團 phosphocellulose 的resin，就可以做**陽離子交換層析**

#### 凝膠過濾層析 (gel filtration)
- 分離蛋白質的重點: **步驟越少越好 !**
- 但是如果你同時弄陰離子和陽離子交換層析，那你往往要第三步: 乾脆直接用蛋白質大小
- 這時用的樹酯會有多孔，當大大小小的分子流過這些resin時，小分子會穿過樹酯的孔洞，大分子會直接繞過
- 因此大分子會比較快洗出來

![image alt](https://i.pinimg.com/originals/f3/24/d8/f324d8a28f8c4ddf45c8cc7041b1a556.jpg)

#### 親合層析法 (affinity)
- **affinity chromatography** 的其中一個例子，例如resin上面有抗體 (生物性親合)
- 這跟剛剛的其他層析最不一樣的地方就是: **這篩選方式幾乎有絕對的特異性**，例如在上一章節提到的用鎳來特異性吸引寡His鏈 (化學性親合)

> [!Tip]
> 甚至如果你確定這批結合到resin上的很 "純"，你乾脆直接把resin和蛋白混合混合，拿去離心，提取pellet就好 ! 😏

- 而elute的方法，通常就是用可以競爭該特異性位點的物質去洗，目的就是破壞特異性連結

### label tracer
- 如果只是用紫外光析收或是染料染色，如果RNA或是DNA的數量太少太少，直接用這種方式測量幾乎不可能
- 因此有人就嘗試用放射標記，例如用可和其互補的probe，並且該probe有放射性同位素，像是... 🐱🐱

#### Autoradiography
- **放射自顯影**的機制有點像是底片，就是讓一些放射性的DNA進行電泳後，把agarose和**X-ray膠片接觸**
- 然後放置好幾天，讓DNA的輻射**曝光底片**，顯影後，膠片上會出現黑色條帶
- 為了增加靈敏度，可以利用**intensifying screen**，這種屏幕在遇到激發的電子 ( $\beta$ -electron) 時就會發光，而放射線就常常來自於電子

![image alt](https://xbio-live.s3.amazonaws.com/bio-dictionary/thumb/AUTORADIOGRAPHYII.DP.RGB.png)

- 通常在intensifying screen上顯影最好的物質就是 $^{32}P$ ，其 $\beta$ -electron能量夠強
- 如果是想要預估DNA片段中放射性的精確含量，那可以將該底片偵測其吸光值。**吸光值越高，放射性越強**

#### Phosphorimaging
- 放射自顯影有一個問題，就是當衰變的強度到達一定量的時候，這個底片基本上就幾乎全黑了
- 也就是說，他有**飽和的問題**，可能五萬次衰變的條紋跟一萬次衰變的長相一模一樣
- 甚至有些同位素的強度根本不夠高，底片上可能根本沒有痕跡
- **磷光呈像儀**可以透過檢測放射出來的電子進行分析，也就是用電腦偵測放射線了
- 具體來說: 
   - 你拿一個樣品，將其和**phosphorimager plate**放在一起
   - 這個板子上的原子基本呈現激發態
   - 當樣品的 $\beta$ -electron撞到這個板子時，就會釋放出能量
   - 而這些能量會被儀器偵測到，並且以顏色 (false color) 呈現能量強度差

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/false_color_phosphorimager_scan_of_an_RNA_blot_0915.png)

#### Liquid scintillation counting
- 基本上就是將放射出來的電子，轉成光子的能量，然後儀器去捕捉發出來的光脈衝
- 例如，你可以把一個agarose上的條帶丟閃爍液裡面，當螢光劑分子吸收放射出來的電子能量，就會出現閃光
- 而電腦要做的，就是算**光脈衝的量 (計數)**，閃越多次，代表信號越強
- 這也通常用於如果你的同位素能量太弱的話，使用的替代方案

### nonradioactive tracer

> [!Tip]
> - Q: 即使偵測放射線靈敏度很好，但是總是有人覺得很危險
> - A: 不如請酵素來幫忙? 😗😗

- 酵素在良好的活性下，就可以倍增式的製造產物，從而放大信號，例如你可以用這種方式...
   - 我製造一種探針，該探針會在某些核甘酸 (例如dUTP) 上面接上特定的蛋白質 (例如biotin，生物素)
   - 把這種probe和待測的DNA雜交，這樣DNA上就有生物素探針
   - 在鹼性磷酸酶 (alkaline phosphatase) 上**配上具有專一性辨識蛋白質的avidin**，例如這裡就是在鹼性磷酸酶 + avidin組合 (avidin強度在此處跟抗體可能差不多)
   - 然後丟進雜交後的DNA裡面，使鹼性磷酸酶和probe結合
   - 接下來再撒入銜接磷酸基的螢光分子
   - **當磷酸基被酵素切下來時，分子就能夠發光**，發光越多 = 斷更多磷酸基 = 更多酵素同時幫忙 = 更多probe = 更多被標記的DNA

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/detecting_nucleic_acids_with_a_nonradioactive_probe--take_AKP_and_biotin_for_example_0913.png)

### 當你發現雜交也有用時
#### Southern blots
- 由Edwin Southern在1975年發現，通常是在大量核酸裡，檢測特定 DNA 片段
- 原理通常是把 DNA 片段分離後，轉移到膜上，再用標記探針檢測

```mermaid
timeline
  title Southern blot 🧬
   DNA 切割: 用限制酶<br>把基因組 DNA<br>切成片段
   凝膠電泳: 在 agarose gel<br>中分離片段<br>依大小不同<br>跑出不同位置: 這時的條帶<br>會像瀑布一樣<br>黏在一起 🤣
   blotting: 把 DNA 從凝膠轉移<br>到硝酸纖維素膜<br>或尼龍膜上: DNA 固定在膜上
   hybridization: 加入帶標記的<br>DNA/RNA 探針: 可以是放射性<br>或非放射性: 探針會和膜上的<br>互補序列結合
   檢測: autoradiography<br>或化學顯色<br>檢測信號: 如果存在多個條帶<br>可能代表存在<br>多個類似基因
```

![image alt](https://sciencevivid.com/wp-content/uploads/2022/06/SOUTHERN-BLOTTING.png)

#### DNA fingerprint
- 事實上，Southern blots也可以做為犯罪鑑定
- 例如，我們知道每個人的STR (或是minisatellite等重複序列) 的 "數量" 不一樣
- 也因此，在做限制酶切位時，不同人的同一條染色體，可能短序列大小不一樣，因為有些人STR重複多，有些重複少
- 那我們如果做一個雜交於STR的探針，那不同的人blotting後，條紋也會不一樣!


![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/southern_blotting_tandem_repeat_0306.png)

> [!Note]
> - 因為每個人的條紋都不一樣，因此這也被稱為DNA指紋 😗
> - 不過如果是同卵雙胞胎的話，產生的條帶基本是一樣的 😏

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/G.%20Vassart%20et%20al.%2C%20A_sequence_in_M13_phage_detects_hypervariable_minisatellites_in_human_and_animal_DNA_0915.png)

- 雖然說大家的DNA fingerprint都不太一樣，不過通常來說，這些條帶其實也有遺傳的傾向
- 因此，這也可以用來確定，痾，你身邊的某個孩子到底是不是你的 🤣

> [!Tip]
> 請問下列圖片中，A和B誰是兇手? 🧐

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/use_of_DNA_typing_to_help_identify_a_rapist_0915.png)

#### RFLP
- 利用限制酶切割 DNA 後，因為不同個體的 DNA 序列存在差異，導致切割片段的長度不同
- 但跟一般辨識STR長度的差別在於，這個東西是看突變，而且往往是位於限制酶切位上的點突變
- 限制酶只能辨識特定序列 (例如 GAATTC)，如果某個個體在這個序列上有突變，限制酶就切不開
- 這就導致不同個體的 DNA 在電泳中會呈現不同片段長度
![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/RFLP_SCD_0306.png)

#### in situ hybridization
- 原位雜交的準備條件，要先確保細胞中的染色體展開，並且**部分呈現解璇狀態** (不然你的probe插不進去)
- 然後讓染色體跟已標記的探針雜交，這樣這些標記就會散布在某些特定細胞上
- 如果probe上面有螢光標記，就是 **fluorescent in situ hybridization (FISH 🐟)**
- 這也可以做染色體分析、以及基因是否有移位、不正常缺失等等

![image alt](https://www.genome.gov/sites/default/files/tg/en/illustration/fluorescence_in_situ_hybridization_fish.jpg)



#### Western blot
- 不同於Southern blot檢測的是核酸，Western blot用途主要是用來**檢測特定蛋白質的存在與大小**
- 原理基本上就是將蛋白質分離後轉移到膜上，再用**抗體辨識**

```mermaid
timeline
  title Western blot 🧬
   蛋白質萃取: 從細胞或組織中<br>取出蛋白質: 利用 SDS-PAGE<br>按分子量<br>分離蛋白質
   blotting: 把蛋白質<br>從凝膠轉移到<br>PVDF 或硝酸<br>纖維素膜
   blocking: 用牛血清白蛋白<br>封閉膜上的<br>非特異性結合位點: 這讓抗體沒有<br>機會亂黏，減少<br>背景雜訊
   抗體檢測: primary<br>antibody 專一性<br>辨識目標蛋白: secondary<br>antibody 帶有<br>酵素或螢光標記<br>用來顯示訊號
   顯影: 透過化學發光、<br>螢光或顏色顯影<br>檢測蛋白質
```

![image alt](https://www.biomol.com/media/image/1f/3e/8f/Principle_WB_EN.png)

### DNA定序 (🙂)
#### Sanger
- 1975年Sanger和他的同事Maxam發現了一種極度精準的定序法，這讓它們拿到了1980年諾貝爾獎
- 方法叫做**chain-termination DNA sequencing**
- 利用雙去氧核甘三磷酸**ddNTP**，中止DNA繼續複製，然後透過段在哪裡去推測DNA序列。具體方法:

> [!Note]
> - 加入ssDNA、primer (約21 nt)、DNA polI、dNTPs、還有一點點ddNTPs
> - DNA合成，其中ddNTPs**隨機插入**，產生不同長度的DNA片段。
> - 傳統上把反應分成四管，每一管只放一種ddNTP(也就是ddATP、ddTTP、ddCTP、ddGTP)
> - 當隨機接上一個ddNTPs，就會停止配對，這些DNA的聚合何時終止是隨機的，因而產生長長短短的序列
> - 然後把各個反應混合物片段以電泳分離...

![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/sanger_sequencing_0330.png)

- 在短序列的情況下，條帶是可以分離長度只相差一個鹼基的片段
- 注意，我說的是 **"短序列情況"** 🤣

> [!Tip]
> Sanger那年代還沒有PCR，要弄出單股DNA，他們有時是請M13 phage幫忙生出cloned的單股DNA 😗

#### automated
- 進階的Sanger用的是**以不同顏色螢光標記的ddNTPs**，用雷射偵測顏色，電腦自動作色彩峰圖(chromatogram)
- 也就是說，這些序列是可以放在同一個泳道，在電泳期間，DNA一邊跑，儀器一邊測量
- 現在進行基因組定序時，sequenators一台裡面有數十甚至數百列泳道，等到每個泳道測定完成後，儀器會自動將結果傳入電腦進行分析

![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/sanger_sequencing_with_dye-labeled_segment_0613.png)

#### 高通量定序
- 也被稱為NGS (次世代定序)，他們一次定序的讀取片段通常較短，可能只有幾十個鹼基
- 1990年代出現pyrosequencing (焦磷酸定序)，相對於Sanger，精度不差，而且讀取速度更快，也不需要電泳
- 用的機制就是在DNA pol在一個個接上核甘酸時，一次會釋放一個焦磷酸鹽 (PPi) 的特性，利用螢光，讓儀器有機會偵測焦磷酸鹽的釋放，從而分析出序列

$$
\begin{align}
& dNMP_n + dNTP\quad \underrightarrow{DNA\ pol}\quad dNTP_{n+1} + PPi\\
& PPi + \text{adenosine phosphosulfate} \quad\underrightarrow{ATP\ sulfurylase}\quad ATP + \text{sulfate}\\
& ATP + \text{luciferin} + O_2  \quad\underrightarrow{lucferase}\quad AMP + PPi + \text{oxyluciferin} + CO_2 + light
\end{align}
$$

- 每一輪反應結束後，會利用像 apyrase 這類酵素把未反應的 nucleotide 和相關反應物清掉，讓下一個 flow 不會被上一輪污染
- 一些pyrosequencing是在固向載體上面進行聚合 (例如在bead或是板子上面)
- 相反，有些是在溶液裡面進行反應
- 當然，在液相反應裡，所有 dNTP 都在同一池子裡，如果不去除或控制，聚合酶可能會一次加上多個核苷酸，導致 "同步性" 失敗



#### pyrogram
- 在焦磷酸定序裡面，最重要的特點是: **加入 nucleotide 之後，新末端仍然有一個 3'-OH**
- 所以pol如果連續遇到同一個重複核甘酸，例如 `TTTTT` ，狀況就會變成... **一次產生超級亮的T訊號**
- 這在**pyrogram**上就可以清楚看到，可能小峰訊號就是代表一個核甘酸，中峰訊號是連續兩個相同核甘酸，超大峰訊號就是... 嗯 🤣

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/example_of_pyrogram_in_pyrosequencing_0915.jpg)

#### 焦磷酸定序的毛病
##### 1. 越讀越爛
- 首先，就是他**最多一次定序200~300 bp**，超過這個值，定序的精確度就會越來越差
- 因為 flow-by-flow 的 signal 在讀得越長之後，**會越來越難維持乾淨、可判讀的訊號**
- 每一輪都可能會很倒楣的出現...
  - nucleotide 沒有完全被清掉
  - apyrase 清除不完全
  - 背景噪音
  - 不同 template molecules 反應速度不完全一致
- 於是跑很多 cycle 後，前面的誤差會累積

##### 2. 聚合速率不同步
- 還有一個問題就是**不同步性**。你難道真的以為所有pol會乖乖聽話，一個口令一個動作? 🙂🙂

> [!Tip]
> - 理想: 
> ```text
> Molecule 1:  A → C → G → T 🧐
> Molecule 2:  A → C → G → T 🧐
> Molecule 3:  A → C → G → T 🧐
> ```
> - 現實: 
> ```
> Cycle 1:   █████████████ 同步
> Cycle 50:  ███████████   還行
> Cycle 150: ███████       開始散
> Cycle 250: ███           🫠🫠
> ```

##### 3. 你以為 pyrogram 的峰高真的可以拿來數數?
- 即使峰的高度和一次flow的連續核甘酸數量有正相關，但是，你要怎麼推回一個具體的數量? 舉例: 

```text
AAAAAAA
AAAAAAAA
AAAAAAAAA
🙂🙂🙂🙂
```
> - 🧍：「額，這到底是 8 個 A 還是 9 個 A？」
> - 🔬：「嗯……」
> - 📈：「我看起來覺得是 8.6。」
> - 🐱：「你給我閉嘴。」💀

#### 那Illumina為什麼不會這樣? 🧐
- Illumina裡面的每個 dNTP 都帶有 **"可逆封閉基團" (reversible terminator)**，一次只能加一個
- 加完後，螢光訊號被讀取，**需要再去除封閉基團，下一個循環才能繼續**
- 最經典的就是 5'-DMT 保護基
- 每一輪大致就是: **把保護拿掉 → 讓 OH 可以反應 → 接下一個 nucleotide → 再處理化學基團**
- 而且DNA 片段固定在 flow cell 上，反應是同步進行的，**每個循環只會有一個核苷酸被加入並被偵測**

```mermaid 
graph TB
A[ DNA切成很多小片段，每一個片段用oligonucleotide接頭，adaptor，連接5'跟3']-->B[接頭包含primer，用來執行PCR，以及binding region，DNA接在某個基底上面需要用，]-->C[DNA被固定在玻片表面，玻片被稱為flowcell]-->D[開始橋式PCR，每一輪做完後分開雙股DNA，繼續下一輪，最終產生單股DNA叢集cluster]-->E[開始螢光定序，期間會用修飾的螢光核甘酸來阻止DNA複製。每次DNA合成停止時會發出特定的光。]-->F[例如每次加上ATCG，顏色就是🟠🔵🔴🟢]-->G[CCD拍照📸，然後去除螢光跟終止功能，開始下一輪。]-->E
```

![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/NGS_Illumina_0330.png)

- 目前的技術已經可以做全基因組定序，不過更多時候，普遍更偏好做全外顯子定序
- 當然，也可以乾脆做**轉錄組定序 (transcriptome)**


#### restriction mapping
- 從字面意思上來分析，其實就是畫出 "限制酶切位點的地圖"
- 也就是**根據切完後的片段大小，畫出DNA上各restriction site的位置**
- 假如說你有一個10kb的DNA，你在一個試管內，透過EcoRI限制酶切斷後再跑電泳，你可以得到兩段DNA
- 這兩段可能跑電泳後，你得到了...

```text
0------6----10
       ↑
     EcoRI
```

- 然後你再用BamHI，在另一個是管理裡面，切斷DNA，跑電泳後你得到...

```text
0---3-------10
    ↑
  BamHI
```
- 好，那問題是，這兩個位點到底相對位置在哪，因為根據這種判斷，你通常有兩個可能結果...

```text
0---3---6----10
    B   E

0------6-3---10
       E B
       
🙂🙂
```

- 因此實驗後半段會做double digest，也就是同時加入兩個限制酶
  - 假如說你最後得到兩個條紋: 3kb和4kb，那相對位置就是第一種可能
  - 假如說你最後得到三個條紋: 6kb、1kb和3kb，那相對位置就是第二個可能

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/restriction_mapping_experiment_example_0917.png)

> [!Tip] 
> - 你甚至可以用Southern blots，例如你把BamHI那個3kb的片段做成螢光探針，然後拿去用Sounthern blots去跟EcoRI切過的DNA進行雜交
> - 然後如果6kb的那一段發光，代表BamHI和EcoRI切出來的片段**在這裡有重疊** 😏
> - 以下圖片可以自行比對一下，右手邊的A和B片段，如果做成探針的話，會在左手邊的哪些片段有重疊 ?

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/using_Southern_blots_in_restriction_mapping_0917.png)

### 定點誘變跟蛋白質
- 也就是透過點突變，改變轉錄出的蛋白質的其中一個胺基酸，看看這個改變會對蛋白質功能造成甚麼影響
- 例如，Tyr跟Phe的結構只是在苯環上是否有 $-OH$ 基團的差別而已，但是否這個差別就足以影響該酵素活性? 
- 所以我們試著將質體上的其中一個TAC (Tyr密碼子) 變成 TTA (Phe密碼子)，要做到這種精細度的點突變，我們可以這樣...
  - 在欲誘變基因的質體上，於限制酶切位點 (例如 5'-GATC'3'，Dpul限制酶切點) 上進行甲基化
  - 然後在加熱分開雙股後，加入引子，該引子要重疊於我們想要改變的密碼子片段
  - 這樣形成的兩個質體會在點突變的區域無法和primer配對成功，形成一個突起
  - 此時進行PCR (用Pfu polymerase)，這會形成兩種質體: 
```
序列正常 + 甲基化
序列點突變 + 沒有甲基化
```
  - 然後在這混合的質體裡面，加入Dpnl限制酶

> [!Important]
> **Dpnl會把帶有甲基化的區域剪斷**，這導致相應的，序列正常的質體失去功能，只保留了點突變的 ! 😏

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/PCR-based_site-directed_mutagenesis_0917.png)

### 轉錄本的定位和定量
#### Northern blots
- 基本上就是... 額，Southern blots的RNA版
- 也就是從細胞抽取混合RNA，跑電泳，轉印到纖維素膜，然後丟cDNA probe去雜交，然後X-ray成像

![image alt](https://www.discoveryandinnovation.com/BIOL202/notes/images/Northern_blot6.jpg)

> [!Tip]
> ##### 等一等 🧐
> - Q: 如果只是想知道「有沒有這段 RNA」，理論上真的可以直接丟 probe 啊。為什麼還要先辛苦跑膠、轉膜、再雜交？😗
> - A: 因為研究者通常不只想知道「有沒有」，還想知道「多大」、「有幾種」、「是不是正確的 transcript」😏
> - Q: 🧐
> - A: 你如果只是要知道有沒有表現，可以用microarray，但重點是，我們想知道這些表現的mRNA有多長，甚至可以觀測到可變基因剪切，以及基因的突變等等 🐱

#### S1 mapping
- S1 nuclease mapping是早期分子生物學家在沒有 RNA-seq、5' RACE 的年代，用來**精確定位轉錄起始點 (Transcription Start Site, TSS)** 的重要技術
- 邏輯上就是: 

> [!Note]
> 用一條已知位置的 DNA probe 去找 RNA 的配對區域，然後把沒配對的部分吃掉，再量剩下多長 😗

- S1 nuclease 有專門切除ssDNA或是ssRNA的功能
- 在切除之前，可以大致知道下不同限制酶相對於TSS的位置。我們用以下的圖來說明

##### 5'end S1 mapping
- 這個題目想要問的是: 在TSS下游多少合該酸的地方，是BamHI切除的位置，**相當於先用BamHI來把DNA弄短一點，縮短範圍**
- 假如說你切好之後，我們再開始標記5'，標記方式就是先用鹼性磷酸酶把末端的5' $\gamma$ 磷酸基去除，然後再替換一個新的，以 $^{32}P$ 標記的磷酸基 
- 這時你會... 等等，產生的還不是probe，因為你還是雙股 🤣
- 所以你還需要知道另一個限制酶，可以切除另一端的標記，這個標記需要在TSS的上游
- 切除後，你就會得到一個probe，就是**5'標記的區域是BamHI切位，並且涵蓋TSS的probe**

> [!Tip]
> 把這個probe跟轉錄的RNA雜交，加入 S1 mapping 後，非雜交的單股區域會被分解掉，這時你只要**把這個雜交的傢伙透過電泳分析下長度，就可以知道限制酶切位距離TSS下游多少** 😏

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/S1_mapping_the_5'-end_of_a_transcript_0918.png)

> [!Warning]
> 這個實驗的最大問題是... **你一定要對這個基因有一個基本的見解** (例如限制酶切位點相對於基因位於哪裡) ，不然你就是瞎切 🙂💀

#### primer extension
- 當你覺得S1 mapping很麻煩 (例如我)，那就考慮用extension mapping
- 這甚至不用先確保限制酶的相對位置，也根本不需要間接考慮RNA保護多少probe這種問題。你只要知道反轉錄酶走的多遠。具體來說就是...

```mermaid
   timeline 
   title primer extension 🧬
     5' labeled primer: 做一個primer<br>自行設置primer序列: primer的5'要<br>同樣標記P同位素
     primer bind to RNA: 接著加入<br>反轉錄酶延伸: 到了RNA 5'<br>也就是TSS處<br>停下
     denature: 此時跑完後<br>會形成兩股<br>ssRNA + sscDNA: 接下來跑膠<br>標記的條帶是<br>我們需要的DNA
     量 radioactive<br>cDNA 多長: Primer + cDNA長<br>就是TSS位置 😎
```

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/primer_extension_process_0917.png)

#### Run-off transcription
- 如果剛剛的primer extension是從RNA的反轉錄得到，那可不可以直接從DNA，得到相對TSS的RNA長度? 答案是肯定的
- 假如說你要知道promoter的必要區域，你就可以看看多個DNA片段 (例如A = -500、B = -300、C = -100)，然後你發現C沒有轉錄出RNA，那重要區域就是在-300到-100之間

```mermaid
graph LR
  A([製造出<br>克隆DNA基因])
  A-->B([以限制酶在TSS<br>下游切割基因])
  B-->C([in vitro<br>transcription])
  C-->D([RNA pol會一直跑<br>直到從限制酶<br>切位點飛出])
  D-->E([產生了有頭<br>無尾的RNA])
  E-->F([RNA長度<br>就是起點到<br>內切酶切位的位置])
```

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/run-off_transcription_process_0918.png)

### 當你想做細胞內實驗
#### nuclear run-off transcription
- 這主要要做的事，是把轉錄到一半的真核生物細胞核取出，此時細胞核會因為沒有能量和原料停止轉錄
- 然後給它需要的能量和標記後的原料，並且加入heparin，結合游離的RNA pol
- 剩下的pol在細胞外繼續轉錄
- 這相當於按了時間暫停，**把細胞核當時要轉錄的RNA、轉錄的量和速率等等的資訊呈現出來**，即使這些轉錄下來的片段並非完整RNA，依然可以鑑定

![image alt](https://image.slideserve.com/830826/slide13-l.jpg)

#### reporter gene transcription

> [!Tip]
> - **Reporter gene**：一個容易被偵測或定量的基因，
> - 用來作為其他基因調控活性的「readout」。

- 為了測量promoter的活性，我們可以將該promoter連到一個reporter gene上面，例如編碼 $\beta$ -galactosidase、CAT、或是螢光酶 (讓螢火蟲發光的酵素)
- 然後在promoter下游嵌入該基因時，就可以透過轉錄出的情形的強弱，判斷這promoter的強度，也就是

```mermaid
graph LR
H1([strong promoter activity])-->A1(more transcription)-->A2(more reporter expression)-->A3(stronger signal)

H2([weak promoter activity])-->B1(less transcription)-->B2(less reporter expression)-->B3(weaker signal)

```

- 甚至，也可以用reporter gene，透過替換 "會影響轉譯的基因"，來看看轉譯的效果有沒有改變

##### 讓我們看看例子...
- CAT = chloramphenicol acetyltransferase，氯黴素乙醯轉移酶 是一種細菌酵素，最有名的功能是讓細菌對抗生素 chloramphenicol (CAM，氯黴素) 產生抗藥性
- 具體就是透過上面加入乙醯基，讓CAM無法結合到核糖體，失去活性
- 所以基本上就是看看在自顯影畫面上，有多少的acetylated CAM 😗
  - 在質體上移除原本的 gene，並將 **cat gene** 接到原本的 regulatory region/promoter 下游
  - 將這個重組質體導入細胞
  - 萃取細胞中的 proteins，取得包含 CAT 的 cell extract
  - 加入帶有放射性標記的 $^{14}C$ -CAM 與 acetyl-CoA
  - 若 extract 中存在 CAT，CAT 會催化 CAM 的乙醯化，形成 **acetylated CAM**
  - 使用 **thin-layer chromatography (TLC)** 分離 CAM 與 acetylated CAM
  - 透過 autoradiography 偵測帶有 $^{14}C$ 標記的 CAM 及其乙醯化產物

> [!Important]
> - CAT activity 越高 → CAT reporter expression 越高 → 可推測該 regulatory region/promoter 的 activity 越高 😏

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/using_a_reporter_gene_CAT_to_analyse_the_activity_of_promoters_0918.png)

### 測量DNA跟protein的交互作用
#### Filter binding
- btw，這方法其實有點點outdated了 🤣

> [!Tip]
> 我們那個年代沒有 fancy fluorescence，所以拿濾膜來吧 💀

- 其實實驗利用的就是一個對蛋白質有親合性的濾膜，然後透過它當 **"濾網"**，過濾DNA和蛋白質，看看DNA有沒有跟者蛋白質一起附著 (**retention**) 在濾膜上
- 首先呢，你要準備一個**標記過的小DNA片段** (才可以看見並穿過濾膜)，然後跟著你想要的protein一起倒進濾膜上面，如果實驗結果是: 
  - DNA alone → 幾乎沒有 retention
  - protein alone → 大量 retention
  - DNA + protein → 大量 retention
- 那就可以確認有相關的interaction在DNA和protein之間 😗😗

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/nitrocellulose_filter-binding_assay_0917.png)

#### gel mobility shift, EMSA
- 另一種方法就是乾脆把DNA混合蛋白質，一起丟進well裡跑電泳，然後看看它跟free DNA之間游動距離的差距
- 通常，攜帶蛋白質越多的DNA，跑起來越笨重 😗
- 所以...
   - 如果land 1是free DNA，那會形成一條條帶，跑得最遠
   - 如果land 2是 DNA + protein 1，那會形成兩條條帶，一個結合了DNA，跑得較慢，一個幸運沒有結合的
   - 如果land 3是 DNA + protein 1 + protein 2，那會形成三條條帶，以此類推 😗

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/gel_mobility_shift_assay_0918.png)

#### DNase and DMS footprinting
> [!Tip]
> 好啦，知道你黏 DNA 了，那你到底黏在哪幾個 nucleotide？ 🧐🧬

- 我們知道DNase可以分解DNA，也因此，我們可以透過這個來預期，到底蛋白質是黏在DNA的哪裡
- 也就是說，如果 protein 正好黏在 DNA 某個區域，那就可以阻止DNase接近這個區域
  - 首先，就是在雙股DNA上先做標記 (例如5')
  - 然後，在mild conditions (溫和條件) 下，用DNase去分解他們

> [!Important]
> 在 footprinting 裡，理想情況其實是**一條 DNA 分子最好只被切一次**，如果你不是在mild condition下進行，用DNase全部切成一盤散沙，那也不用做甚麼實驗了 🙂

  - 在DNase切的時候，會形成大大小小的片段，但有些長度的片段不會形成，因為他們會因為被蛋白質擋住而無法被切到
  - 切完後再跑電泳，然後看看哪些地方 **"沒有條帶"** 

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/DNase_footprinting_0918.png)

- DMS footprint 走的也是類似的道理，只是這時不是看哪裡可以切開DNA，而是哪裡的DNA有附著甲基
- **DMS = dimethyl sulfate**，它是一種可以對 DNA 上特定鹼基進行 methylation 的物質
- 如果 protein 正好黏在 DNA 某個區域，它會阻擋 DMS 接觸那附近的鹼基，那些鹼基就不會被甲基化
- 然後，用piperidine去除甲基化的purine，在沒有purine的區域剪切，產生大大小小的DNA片段後，再拿去跑膠，看看哪裡的條帶消失了

#### Chromatin immunoprecipitation (ChIP)
- 這個技術需要用到抗體
- 首先就是把染色質提取出來，然後用甲醛 (formaldehyde) 先固化，這讓蛋白質和DNA之間出現共價鍵
- 然後再用超音波把DNA震成小片段，接下來利用抗體的專一性特性，讓抗體結合附著在DNA上的蛋白質，讓它們聚在一起 (這些抗體通常附著在bead上)
- 接下來就是分離DNA和蛋白質，將蛋白質以及擴增後的DNA進行分析

![image alt](https://bioclone.net/wp-content/uploads/2023/04/Tech-Chromatin-Immunoprecipitation-Workflow.jpg)

#### 比較一下

|method	|問題是|方法簡介|
|---|---|---|
|**Filter binding**|DNA 有沒有 bind protein|用蛋白質可附著的濾網|
|**EMSA**|有沒有形成 DNA–protein complex？complex 的 mobility 怎麼變？|DNA + protein再跑膠|
|**DMS footprinting**|蛋白質到底碰 DNA 的哪裡？|DMS甲基化purine後剪切成DNA片段，跑膠看**看缺失的DNA片段長度**|
|**ChIP**|在細胞內，某個 protein 是否和特定 genomic region 有 association？|Cross-link → chromatin fragmentation → antibody immunoprecipitation → 分析被拉下來的 DNA|

### 如何檢測蛋白質交互作用
#### Immunoprecipitation, IP
- 假如說我有一個未知的蛋白質混合溶液 (ahem) ，而不知道裡面的A跟B蛋白之間有沒有交互作用
- 那我可以先用帶有A抗體的bead把A先沉澱下來，然後我把這些收集的A蛋白做Western blots
- 但是我在轉印的膜上面加入標記的B抗體，如果有偵測到上面有B蛋白，那 **就有可能是因為和A產生交互作用而被吸上來的**

#### Yeast two-hybrid (Y2H)

> [!Tip]
> 不要直接問「兩個 protein 有沒有黏在一起？」，我們讓它們「如果有黏在一起，就把一個 reporter gene 打開」。💡

- 就舉經典的Gal4轉錄因子為例 
- GAL4 轉錄因子有兩個平常分開的功能區域: 
   - **DNA-binding domain (BD)**: 能結合到 DNA 上的 promoter region
   - **activation domain (AD)**: 能招募轉錄複合體，啟動基因表達
- 如果把這兩個區域分開，單獨存在時都不能啟動轉錄
- 但如果 BD 與 AD 被兩個互相結合的蛋白質拉到一起，就能重新組合成完整的 GAL4 功能，基因表達啟動。通常來說: 
   - 科學家先構建融合蛋白: 亞基包含 **"蛋白質 X + BD"** ，以及 **"蛋白質 Y + AD"**
   - 把這兩個融合基因轉入酵母細胞，如果 X 與 Y 本身在生物體內就是 partner，那麼在 Y2H 系統中它們也會自然結合
   - X 和 Y的交互作用可以促進原本分很開的 BD 和 AD 結合在一起
   - 沒有 X–Y 的結合，GAL4 的 BD 和 AD 永遠不會 "自動合體"

> [!Important]
> 也就是說，如果轉錄有成功出現，那就代表X和Y 蛋白可能有交互作用 ! 😏


![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/yeast-two-hybrid_mechanism_0603.png)

### 找到和其他分子有交互作用的RNA
#### SELEX
- 全名是 Systematic Evolution of Ligands by EXponential enrichment
- 首先會轉錄一大堆random DMA，產生一大堆random RNA
- 然後利用親和性管柱層析，去洗一大堆random RNA，然後把有親和性的RNA反轉錄成cDNA，進行PCR
- 當得到大量的cDNA後，再進行轉錄一次，然後洗一次，逆轉錄一次，PCR一次，無限循環....

> [!Note]
> ##### 為什麼非要洗這麼多次不可? 🧐
> - 因為在層析的時候，第一次被抓下來的東西，不一定全部都是 "真正高親和力、特異性高" 的 ligand，可能會:
> ```text
> 超高 affinity      → 留下 🤗
> 中等 affinity      → 也可能留下 😗
> 低 affinity        → 有些也可能留下 💀
> ```
> - 因次，透過不斷循環，就可以讓高親和力的DNA/RNA比例越來越高

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/systematic_evolution_of_ligands_by_exponential_enrichment_assay_0918.png)

### 敲除和轉基因
#### knockout mice
> 乾脆我們來看以下圖示範... 🤣🤣

##### 處理細胞

- 在敲除基因時，首先，你要有一個質體，這個DNA上有你要敲除的基因，然後，在這個基因上插一個抗生素抗性基因 (例如 $neo^r$ )

> [!Note]
> - 這個基因會在各種類似的抗生素上面加上磷酸基，使其失效
> - 在真核生物上，該基因對應的是G418。G418 屬於 **aminoglycoside** (胺基醣類抗生素)
> - 在真核細胞中，它會干擾核糖體讀取 mRNA，最終使細胞無正常蛋白質而死

- 這個基因跟E.coli基因轉殖時一樣，是為了篩選轉殖細胞
- 在target基因附近也會裝上一個 *tk*，這裡的 tk 通常指 HSV **thymidine kinase**
- 有tk的細胞會讓細胞對 ganciclovir 敏感，因此導致細胞死亡。這與成為了一個篩選機器
- 這個質體背負重要任務，他要進去老鼠的胚胎幹細胞裡面，選擇**跟染色體做基因互換**
- 這時，基因融合的方式，其實有三種可能: 

```
A. 我把被破壞的target gene換給了老鼠 🤗
B. 我把被破壞的target gene、tk都換給了老鼠 😏
C. ...我忘了換 😗
```
- 之後，我將這些細胞篩選，加入G418和ganciclovir，此時...
   - C沒有 $neo^r$ ，當她碰到G418時，就會轉錄出差吋而死亡
   - B有 *tk*，這使得他對ganciclovir敏感，死亡
   - **最終只有A留下來**

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/creating_stem_cells_with_an_interrupted_gene_during_gene_knockout_0918.png)
 
##### 轉入細胞
- 接下來，我們將這些轉殖的，knockout基因的細胞注入小鼠囊胚
- 然後如果這胚胎成功長大，恭喜，你會得到一隻... chimera mouse 🐭🧩

> [!Tip]
> 🙂🙂🙂🙂 (這是無語的意思)

- 所以關鍵其實是: **knockout ES cells 有沒有進入 germline**。如果 knockout ES cells 最後有貢獻到germ cell，在未來形成精子或是卵子，這個 knockout allele 就可以傳給下一代
- 所以我們會拿這隻 chimera 去跟正常 mouse breeding，如果幸運的話，你可以拿到一隻異型合子 (WT / KO)

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/placing_the_interrupted_gene_in_the_animal_during_gene_knockout_0918.png)


