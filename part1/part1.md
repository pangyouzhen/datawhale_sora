1. 技术发展路线

    |文章|提出时间|链接|解决的问题|
    |---|---|----|---|
    |vit|2020|https://arxiv.org/abs/2010.11929||
    |Swintransformers|2021|https://arxiv.org/abs/2103.14030||
    |MAE|2021|https://arxiv.org/abs/2111.06377||
    |CLIP|2021|https://arxiv.org/abs/2103.00020||
    |DallE2|2022|https://arxiv.org/abs/2204.06125||
    |ViLT|2021|https://arxiv.org/abs/2102.03334||
    |BEIT-3|2021|https://arxiv.org/abs/2208.10442||
    |vivit||https://arxiv.org/pdf/2103.15691||
    |Dit||https://arxiv.org/abs/2212.09748|
    |u-net||https://arxiv.org/abs/1505.04597|
    
    <!-- |Donut|2021|https://arxiv.org/abs/2106.08254|| -->
1. 其他
    1. vit transformers, 将图片转为16*16的patchs，将词向量降维，分类任务
    1. vivit , 视频中比图片中增加了时间，分类任务
    1. space time patchs，取样
    1. sora的解决的问题: 1. 连贯性
    1. sora 是怎么解决这个问题的：连贯性是通过 space time d
    1. 马尔科夫链 -> diffsuion -> DDPM -> backbone 从 u-net到transformers
    1. 文本转为条件，视频进行encode， 两个喂进 diffsuion
    1. DiT = VAE ecoder + vit +DDPM +VAE