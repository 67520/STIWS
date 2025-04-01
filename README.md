# STIWS - 中药质谱解析工具
STIWS 是一款专为中药质谱解析设计的辅助工具，整合了多源数据库和机器学习算法，助力中药成分分析与鉴定。

## ✨ 核心功能

- **中药成分数据库查询**  
  整合 ETCM、TCMSP、Herb 及 TM-MC 等中药成分数据库
- **母离子精准匹配**  
  - 目标药材匹配模式  
  - 混合匹配模式  
  - 全库匹配模式  
- **未知化合物识别**  
  基于 ESI-MS 靶向识别特定类型未知成分
- **已知化合物鉴定**  
  通过 ESI-MS 快速鉴定已知化合物

## 📚 致谢与引用

本工具得益于以下数据库的宝贵贡献（排名不分先后）：

### 中医药数据库
- [TCMSP](https://tcmspw.com/) - 中药系统药理学数据库  
  *Ru et al. J Cheminform. 2014*
- [ETCM](http://www.nrc.ac.cn:9090/ETCM/) - 中药百科全书  
  *Xu et al. Nucleic Acids Res. 2019*
- [HERB](https://herb.ac.cn/) - 高通量中药数据库  
  *Fang et al. Nucleic Acids Res. 2021*
- [TM-MC](http://informatics.kiom.re.kr/compound/) - 东北亚传统医药数据库  
  *Kim et al. BMC Complement Altern Med. 2015*

### 质谱数据库
- [GNPS](https://gnps.ucsd.edu/) - 天然产物分子网络  
  *Wang et al. Nat Biotechnol. 2016*
- [MoNA](https://mona.fiehnlab.ucdavis.edu/) - 质谱开放数据库  
  *Horai et al. J Mass Spectrom. 2010*

## 📜 引用文献

```bibtex
[1] Ru J, Li P, Wang J, et al. TCMSP: a database of systems pharmacology for drug discovery from herbal medicines[J]. J. Cheminf., 2014, 6(1): 13.
[2] Xu H Y, Zhang Y Q, Liu Z M, et al. ETCM: an encyclopaedia of traditional Chinese medicine[J]. Nucleic Acids Res., 2019, 47(D1): D976-D982.
[3] Fang S, Dong L, Liu L, et al. HERB: a high-throughput experiment- and reference-guided database of traditional Chinese medicine[J]. Nucleic Acids Res., 2021, 49(D1): D1197-D1206.
[4] Kim S K, Nam S, Jang H, et al. TM-MC: a database of medicinal materials and chemical compounds in Northeast Asian traditional medicine[J]. BMC Complement. Altern. Med., 2015, 15(1): 218.
[5] Wang M, Carver J J, Phelan V V, et al. Sharing and community curation of mass spectrometry data with Global Natural Products Social Molecular Networking[J]. Nat. Biotechnol., 2016, 34(8): 828-837.
[6] Horai H, Arita M, Kanaya S, et al. MassBank: a public repository for sharing mass spectral data for life sciences[J]. J. Mass Spectrom., 2010, 45(7): 703-714.
