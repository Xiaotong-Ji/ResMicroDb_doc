# Home

# ResMicroDb

![image-20250212163536991](./assets/image-20250212163536991.png?lastModify=1740380019)

1. Logo:figure/logo.png

2. ResMicroDb对应颜色：#ECB35D，#82BAE4，#A7C9A7

3. 呼吸道部位图对应figure/body_sites.png

4. 部位-疾病健康分布对应data/body_site_distribution.tsv。case代表疾病disease，control代表健康health

   鼠标移到body_site的bar上面，显示对应疾病健康的样本个数，以nasopharynx为例

   ```
    nasopharynx
    health samples:9,580
    disease samples:3,614
   ```

   点击链接到`Browse-body-sites`。颜色对应

   ```R
    body2col <- c(
      "nasal" = "#1f77b4",       
      "nasopharynx" = "#377eb8",
      "oropharynx" = "#6baed6",
      "pharynx" = "#9ecae1",
      "sputum" = "#ff7f0e",      
      "trachea" = "#fd8d3c",
      "bronchus" = "#fdae6b",
      "BALF" = "#fdd0a2",
      "lung" = "#feedde"
    )
   ```

5. 数字分别对应metadata的Phenotype、Run、SRAStudy列的非重复个数(除去NA)。Publication对应data/publication.tsv的行数）。图标分别对应figure/phenotypes.png、figure/samples.png、figure/studies.png、figure/publications.png。

   链接到Browse对应页面，Browse-phenotypes, Browse-samples, Browse-studies,Browse-publications。

6. 蓝色部分分别链接到Search#8AB1D0（筛选框为Taxa name或Phenotype）、Browse#BDBBD8(Browse-samples, browse-studies)、Analysis#F2B176(Analysis-microbiome-composition,Analysis-case-control-analysis )对应页面

# Data Summary

![image-20250208210009557](./assets/image-20250208210009557.png?lastModify=1740380019)

1. 有两个表data/country.tsv（国家、频数），data/country_location.tsv（国家、地区、经纬度，频数）。
2. 对应表data/top10countries.tsv
3. 对应metadata的Sequencing_Type列
4. 对应data/top10phe.tsv的Phenotype列
5. 对应metadata的Age_Group列，注意顺序为c("0-3", "3-18", "18-30", "30-50", "50-70", "70-100")。

# ciation and contact

![image-20250208210112619](./assets/image-20250208210112619.png?lastModify=1740380019)

Relate links对应的链接

| Name                     | Link                                                         |
| :----------------------- | ------------------------------------------------------------ |
| pubmed                   | https://pubmed.ncbi.nlm.nih.gov/                             |
| NCBI Taxonomy            | https://www.ncbi.nlm.nih.gov/taxonomy/                       |
| BugSigDB                 | https://bugsigdb.org/Main_Page                               |
| gutMDisorder             | http://bio-annotation.cn/gutMDisorder                        |
| GMRepo                   | https://gmrepo.humangut.info/home                            |
| mBodyMap                 | https://mbodymap.microbiome.cloud/                           |
| MAMI                     | https://bioinfo.biols.ac.cn/mami/                            |
| HOMD                     | https://www.homd.org/                                        |
| 人间传染的病原微生物目录 | http://www.nhc.gov.cn/qjjys/s7948/202308/b6b51d792d394fbea175e4c8094dc87e.shtml |
| CZ ID                    | https://czid.org/pathogen_list                               |
| Karius                   | https://kariusdx.com/karius-test/pathogens                   |