# Large and Multi-modality Satellite Datasets
**A Summary for Large-Scale and Multi-modality Remote Sensing Datasets.**

With the continuous enrichment of remote sensing data and the rapid advancement of large model technologies, numerous large-scale remote sensing datasets for tasks such as **pre-training and image generation** have been successively released. To facilitate **a better understanding and utilization of these datasets**, we compile and summarize the currently available resources, with a particular focus on **globally distributed and multi-modal datasets**.

The content is currently being updated progressively. As this compilation is based on **personal study and summarization**, omissions may be inevitable. **If any datasets are not mentioned, readers are welcome to contact the author via email**[(gaohuaming23@mails.ucas.ac.cn)](). Upon verification, relevant updates will be incorporated in a timely manner.

## DATA TABLE

| Dataset Name  | TASK             | Time Range | Cover  Range | Modality          |          DATA SOURCE           | Volume                    | Resolution | Link                                                         |
| ------------- | ---------------- | ---------- | ------------ | ----------------- | :----------------------------: | ------------------------- | ---------- | ------------------------------------------------------------ |
| BigEarthNet   | LULC             | 2017-2018  | 欧洲         | 光学/SAR          |             S1/S2              | 100GB                     | 10m        | https://bigearth.net/                                        |
| SEN12MS-CR-TS | 去云             | 2018       | 全球         | 光学/SAR          |             S1/S2              | 2TB                       | 10m        | https://patricktum.github.io/cloud_removal/sen12mscrts/      |
| MMRS-1M       | VQA              |            |              | 多光谱/SAR/文本   |                                |                           |            | https://pan.baidu.com/s/1sK9I862tuQfiiFbHBvOOpw?pwd=mycu     |
| RapidAI4EO    | LULC             | 2018-2020  | 欧洲         | 光学              |        S2/Planet Fusion        |                           | 3-10m      | https://rapidai4eo.source.coop/                              |
| fMoW          | LULC             | 2002-2017  | 全球         | 多光谱            | QuickBird-2/GeoEye-1/WorldView | 3.5TB                     | 0.3-10m    | fMoW-full:  s3://spacenet-dataset/Hosted-Datasets/fmow/fmow-full     fMoW-rgb: s3://spacenet-dataset/Hosted-Datasets/fmow/fmow-rgb |
| Satlas        | 生成             |            | 全球         | 多光谱            |               S2               |                           | 10m        | [allenai/satlas-pretrain · Hugging Face](https://huggingface.co/allenai/satlas-pretrain) |
| GAIA          | 视觉语言对齐     | 1998-2024  | 全球         | 文本/光学         |                                | 205,150 image-text  pairs | 0.3-10m    | [azavras/GAIA · Datasets at Hugging Face](https://huggingface.co/datasets/azavras/GAIA) |
| Major-TOM     | LULC             |            | 全球         | 光学/SAR          |             S1/S2              | 64TB                      | 10m        | [Major-TOM   (Major TOM)](https://huggingface.co/Major-TOM)  |
| AnySat        | 视觉多模态预训练 |            | 全球         | 多光谱/SAR        | aerial/spot  /s2/alos/l8/modis |                           | 0.2-250m   | [gastruc/AnySat](https://github.com/gastruc/AnySat?tab=readme-ov-file) |
| Global-Scale  | 道路提取         |            | 全球         | 光学              |        Google 静态地图         | 32GB                      | 1m         | [Global-Scale_免费高速下载\|百度网盘-分享无限制](https://pan.baidu.com/s/18HFMWV1VESFxZg25nCH4kw?pwd=fnku#list/path=%2F&parentPath=%2Fsharelink1101928448319-214626418379406) |
| M3LEO         | 视觉多模态预训练 |            | 全球         | 多光谱/SAR        |                                |                           |            |                                                              |
| EarthView     | 自监督预训练     | 2017-2022  | 全球         | 高光谱/多光谱/SAR |    NEON/Sentinel/Satellogic    |                           | 0.1m-10m   | [satellogic/EarthView · Datasets at Hugging Face](https://huggingface.co/datasets/satellogic/EarthView) |
