# 行业数据集白皮书

在本白皮书中，我们从多个角度全方面的分析了开源行业数据集的总体状况，分别从文本数据集、视觉数据集和多模态数据集针对31个行业进行了详细的总结和整理，并针对开源行业大模型的现状囧行了统计和分析。

北京智源人工智能研究院希望通过本白皮书的工作，促进多方合作和机制创新，努力促进行业数据的开放和共享，进而促进大模型在各个行业中的应用和发展。

项目持续收集整理中，也期冀相关从业人员补充！

## 新闻
- [2024/9/25] 发布行业数据集白皮书
- [2024/9/18] 开源IndustryCorpus2.0
- [2024/8/30] 收录整理 84 个开源行业大模型
- [2024/8/18] 收录第一版开源行业数据集，共 332 个数据集，包括 187 个文本数据集，76 个视觉数据集合 69 个多模态数据集
- [2024/6/13] 开源IndustryCorpus1.0


## 目录

- [31-Indsutry-Dataset](#31-indsutry-dataset)
  - [新闻](#新闻)
  - [目录](#目录)
  - [文本数据集](#文本数据集)
  - [视觉数据集](#视觉数据集)
  - [多模态数据集](#多模态数据集)
  - [开源行业大模型](#开源行业大模型)

## 文本数据集

<table border='1' class='dataframe'>
  <thead>
    <tr style='text-align: left;'>
      <th>Industry</th>
      <th>Dataset</th>
      <th>Type</th>
      <th>Language</th>
      <th>Size</th>
      <th>Number</th>
      <th>Publisher</th>
      <th>License</th>
      <th>Paper</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1. 农林牧渔</td>
      <td>IndustryCorpus2.0-农林牧渔</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>56</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://github.com/zhiweihu1103/AgriMa">AgriMa</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>-</td>
      <td>-</td>
      <td>山西大学</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td>IndustryCorpus2.0-汽车</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>13.8</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://www.heywhale.com/mw/dataset/5af144b62bcd9d0197c19272/content">汽车大师问答摘要与推理</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>-</td>
      <td>110k</td>
      <td>复旦大学</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>3. 采矿</td>
      <td>IndustryCorpus2.0-采矿</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>4</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>4. 石油化工</td>
      <td>IndustryCorpus2.0-石油化工</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>15.3</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>4. 石油化工</td>
      <td><a href="https://opendatalab.com/AI4Chem/ChemData700K">ChemData700K</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0.2</td>
      <td>730k</td>
      <td>上海人工智能实验室</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/AI4Chem/ChemData700K">[1]</a></td>
    </tr>
    <tr>
      <td>5. 电力能源</td>
      <td>IndustryCorpus2.0-电力能源</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>34.9</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td>IndustryCorpus2.0-生物医药</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>18.6</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-PubMed_Central">Pile-PubMed Central</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>81.6</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td><a href="https://github.com/xiaopangxia/TCM-Ancient-Books">TCM-Ancient-Books</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0.1</td>
      <td>-</td>
      <td>xiaopangxia</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MedHop">MedHop</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0.5</td>
      <td>4k</td>
      <td>伦敦大学学院</td>
      <td>CC BY-SA 3.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MedHop">[2]</a></td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td><a href="https://huggingface.co/datasets/zjunlp/Mol-Instructions">Mol-Instructions</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0.2</td>
      <td>2M</td>
      <td>浙江大学</td>
      <td>CC BY 4.0</td>
      <td><a href="https://huggingface.co/datasets/zjunlp/Mol-Instructions">[3]</a></td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td><a href="https://huggingface.co/datasets/michaelwzhu/ShenNong_TCM_Dataset">ShenNong_TCM_Dataset</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.1</td>
      <td>112k</td>
      <td>华东师范大学</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td><a href="https://tianchi.aliyun.com/dataset/86895">TCM_Literature_QA</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>13k</td>
      <td>天池小喵萌</td>
      <td>CC BY-NC-SA 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td>IndustryCorpus2.0-航空航天</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>21.3</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=62">UMETRIP-QA</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>4k</td>
      <td>中航信移动科技有限公司</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>8. 其他制造业</td>
      <td>IndustryCorpus2.0-其他制造</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>11.7</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>9.计算机/通信</td>
      <td>IndustryCorpus2.0-计算机_通信</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>49</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>9.计算机/通信</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CoSQL">CoSQL</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>0.1</td>
      <td>-</td>
      <td>密歇根大学</td>
      <td>CC BY-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CoSQL">[4]</a></td>
    </tr>
    <tr>
      <td>9.计算机/通信</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-Ubuntu_IRC">Pile-Ubuntu IRC</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>5.5</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>9.计算机/通信</td>
      <td><a href="https://github.com/HC-Guo/Owl">OWL-Instruct-ops001</a></td>
      <td>SFT</td>
      <td>中文 英文</td>
      <td>0</td>
      <td>-</td>
      <td>北京航空航天大学</td>
      <td>-</td>
      <td><a href="https://github.com/HC-Guo/Owl">[5]</a></td>
    </tr>
    <tr>
      <td>9.计算机/通信</td>
      <td><a href="https://github.com/HC-Guo/Owl/tree/main">OWL-Bench</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>北京航空航天大学</td>
      <td>-</td>
      <td><a href="https://github.com/HC-Guo/Owl/tree/main">[6]</a></td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td>IndustryCorpus2.0-计算机_编程</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>0.9</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://opendatalab.com/OpenDataLab/JuICe">JuICe</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>3.7</td>
      <td>-</td>
      <td>华盛顿大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/JuICe">[7]</a></td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://opendatalab.com/OpenDataLab/the-stack">The Stack</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>56.6</td>
      <td>-</td>
      <td>bigcode</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/the-stack">[8]</a></td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://huggingface.co/datasets/bigcode/starcoderdata">starcoderdata</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>783</td>
      <td>-</td>
      <td>bigcode</td>
      <td>Custom</td>
      <td><a href="https://huggingface.co/datasets/bigcode/starcoderdata">[9]</a></td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://huggingface.co/datasets/codeparrot/github-code">github-code</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>1000</td>
      <td>-</td>
      <td>CodeParrot</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://huggingface.co/datasets/code-search-net/code_search_net">code_search_net</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>5</td>
      <td>-</td>
      <td>CodeSearchNet</td>
      <td>Custom</td>
      <td><a href="https://huggingface.co/datasets/code-search-net/code_search_net">[10]</a></td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://github.com/liangqingyuan/lyra">Lyra</a></td>
      <td>SFT</td>
      <td>中文 英文</td>
      <td>0</td>
      <td>-</td>
      <td>北京大学</td>
      <td>-</td>
      <td><a href="https://github.com/liangqingyuan/lyra">[11]</a></td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://opendatalab.com/OpenDataLab/StaQC">StaQC</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0.1</td>
      <td>268k</td>
      <td>华盛顿大学</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/StaQC">[12]</a></td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://github.com/zxx000728/CodeGPT">CodeGPT</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>32k</td>
      <td>复旦大学</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://github.com/sahil280114/codealpaca">Code_Alpaca_20K</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>20k</td>
      <td>sahil280114</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://github.com/tangqiaoyu/ToolAlpaca">ToolAlpaca</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>421</td>
      <td>中国科学院大学</td>
      <td>-</td>
      <td><a href="https://github.com/tangqiaoyu/ToolAlpaca">[13]</a></td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://huggingface.co/datasets/google-research-datasets/mbpp?row=21">mbpp</a></td>
      <td>Evaluation</td>
      <td>英文</td>
      <td>0</td>
      <td>1k</td>
      <td>Google Research</td>
      <td>CC BY 4.0</td>
      <td><a href="https://huggingface.co/datasets/google-research-datasets/mbpp?row=21">[14]</a></td>
    </tr>
    <tr>
      <td>10.计算机编程</td>
      <td><a href="https://huggingface.co/datasets/openai/openai_humaneval">HumanEval</a></td>
      <td>Evaluation</td>
      <td>英文</td>
      <td>0</td>
      <td>164</td>
      <td>OpenAI</td>
      <td>MIT</td>
      <td><a href="https://huggingface.co/datasets/openai/openai_humaneval">[15]</a></td>
    </tr>
    <tr>
      <td>11. 人工智能</td>
      <td>IndustryCorpus2.0-人工智能</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>2.3</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>12. 其他信息服务</td>
      <td>IndustryCorpus2.0-其他信息服务</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>0.8</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>12. 其他信息服务</td>
      <td><a href="https://github.com/SophonPlus/ChineseNlpCorpus/blob/master/datasets/yf_amazon/intro.ipynb">yf_amazon</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.3</td>
      <td>7M</td>
      <td>亚马逊</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>12. 其他信息服务</td>
      <td><a href="https://github.com/Alibaba-NLP/EcomGPT">EcomGPT</a></td>
      <td>Evaluation</td>
      <td>中文 英文</td>
      <td>0</td>
      <td>6k</td>
      <td>阿里</td>
      <td>-</td>
      <td><a href="https://github.com/Alibaba-NLP/EcomGPT">[16]</a></td>
    </tr>
    <tr>
      <td>13. 房地产/建筑</td>
      <td>IndustryCorpus2.0-房地产_建筑</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>42</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td>IndustryCorpus2.0-交通运输</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>18.4</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://huggingface.co/datasets/DUOMO-Lab/TransGPT-pt?row=99">TransGPT-pt</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>北京交通大学</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://huggingface.co/datasets/DUOMO-Lab/TransGPT-sft/tree/main">TransGPT-sft</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>58k</td>
      <td>北京交通大学</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>15. 水利/海洋</td>
      <td>IndustryCorpus2.0-水利_海洋</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>10.2</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>15. 水利/海洋</td>
      <td><a href="https://huggingface.co/datasets/zjunlp/OceanBench?row=14">OceanBench</a></td>
      <td>Evaluation</td>
      <td>英文</td>
      <td>0</td>
      <td>10k</td>
      <td>浙江大学</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td>IndustryCorpus2.0-数学</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>2.7</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://github.com/THUDM/MathGLM">MathGLM-dataset</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>9.3</td>
      <td>-</td>
      <td>清华大学</td>
      <td>-</td>
      <td><a href="https://github.com/THUDM/MathGLM">[17]</a></td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://github.com/wellecks/naturalproofs#naturalproofs-dataset">NaturalProofs</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>0.1</td>
      <td>-</td>
      <td>纽约大学</td>
      <td>MIT</td>
      <td><a href="https://github.com/wellecks/naturalproofs#naturalproofs-dataset">[18]</a></td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://opendatalab.com/OpenDataLab/mathpile">MathPile</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>21.2</td>
      <td>-</td>
      <td>上海人工智能实验室</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/mathpile">[19]</a></td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://huggingface.co/datasets/EleutherAI/proof-pile-2">Proof-Pile-2</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>205</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>-</td>
      <td><a href="https://huggingface.co/datasets/EleutherAI/proof-pile-2">[20]</a></td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://huggingface.co/datasets/open-web-math/open-web-math">OpenWebMath</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>27.4</td>
      <td>-</td>
      <td>University of Toronto</td>
      <td>ODC-By 1.0</td>
      <td><a href="https://huggingface.co/datasets/open-web-math/open-web-math">[21]</a></td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-DM_Mathematics">Pile-DM_Mathematics</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>8.1</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://github.com/liutiedong/goat">Goat</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0.5</td>
      <td>2M</td>
      <td>新加坡国立大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/liutiedong/goat">[22]</a></td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://huggingface.co/datasets/nvidia/OpenMathInstruct-1">OpenMathInstruct-1</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>2.9</td>
      <td>7M</td>
      <td>NVIDIA</td>
      <td>Custom</td>
      <td><a href="https://huggingface.co/datasets/nvidia/OpenMathInstruct-1">[23]</a></td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://github.com/yongzhuo/LLM-SFT">MWP-Instruct</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>252k</td>
      <td>Macropodus</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://huggingface.co/datasets/BelleGroup/school_math_0.25M?row=6">BELLE_School_Math</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.1</td>
      <td>248k</td>
      <td>BELLE Group</td>
      <td>GPL 3.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://ai.tencent.com/ailab/nlp/dialogue/#datasets">Math23K</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>23k</td>
      <td>腾讯</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://huggingface.co/datasets/deepmind/math_dataset">math_dataset</a></td>
      <td>Evaluation</td>
      <td>英文</td>
      <td>2.2</td>
      <td>-</td>
      <td>Google DeepMind</td>
      <td>Apache 2.0</td>
      <td><a href="https://huggingface.co/datasets/deepmind/math_dataset">[24]</a></td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://huggingface.co/datasets/openai/gsm8k">Gsm8k</a></td>
      <td>Evaluation</td>
      <td>英文</td>
      <td>0</td>
      <td>8k</td>
      <td>OpenAI</td>
      <td>MIT</td>
      <td><a href="https://huggingface.co/datasets/openai/gsm8k">[25]</a></td>
    </tr>
    <tr>
      <td>16.数学</td>
      <td><a href="https://github.com/Chenny0808/ape210k?tab=readme-ov-file">Ape210K</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>210k</td>
      <td>腾讯</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td>IndustryCorpus2.0-学科教育</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>167</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://github.com/ECNU-ICALK/EduChat">Educhat-sft-002-data-osm</a></td>
      <td>SFT</td>
      <td>中文 英文</td>
      <td>5</td>
      <td>4M</td>
      <td>华东师范大学</td>
      <td>CC BY-NC 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://github.com/blcuicall/mcts/tree/main/pseudo_data">MCTS</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.1</td>
      <td>691k</td>
      <td>北京语言大学</td>
      <td>-</td>
      <td><a href="https://github.com/blcuicall/mcts/tree/main/pseudo_data">[26]</a></td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://github.com/HIT-SCIR-SC/QiaoBan/tree/main/data">Child_chat_data</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>哈尔滨工业大学</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EXAMS">EXAMS</a></td>
      <td>SFT</td>
      <td>-</td>
      <td>0.2</td>
      <td>24k</td>
      <td>Sofia University</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EXAMS">[27]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td>IndustryCorpus2.0-科技_科学研究</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>36.6</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://huggingface.co/datasets/togethercomputer/RedPajama-Data-1T">RedPajama-Data-1T</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>5.3</td>
      <td>-</td>
      <td>北京理工大学</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://github.com/allenai/s2orc">S2ORC</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>0</td>
      <td>-</td>
      <td>艾伦人工智能研究所</td>
      <td>ODC-By 1.0</td>
      <td><a href="https://github.com/allenai/s2orc">[28]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0">WanJuan1.0-CN/Patent</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>4.6</td>
      <td>-</td>
      <td>上海人工智能实验室</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0">[29]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://github.com/ydli-ai/CSL">CSL-pt</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>1.5</td>
      <td>-</td>
      <td>中国地质大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/ydli-ai/CSL">[30]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CORD-19">CORD-19</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>17.4</td>
      <td>-</td>
      <td>艾伦人工智能研究所</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CORD-19">[31]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Elsevier_OA_CC-BY">Elsevier OA CC-BY</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>1</td>
      <td>-</td>
      <td>Elsevier</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Elsevier_OA_CC-BY">[32]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-ArXiv">Pile-ArXiv</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>55.5</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-ArXiv">[33]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://huggingface.co/datasets/daven3/geosignal?row=18">GeoSignal</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>40k</td>
      <td>daven3</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://huggingface.co/datasets/DataHammer/scimrc">SciMRC</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>21k</td>
      <td>北京理工大学</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://github.com/ydli-ai/CSL">CSL-sft</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.1</td>
      <td>-</td>
      <td>中国地质大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/ydli-ai/CSL">[34]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CSL">CSL-bench</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>10k</td>
      <td>中国地质大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CSL">[35]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td>IndustryCorpus2.0-医学_健康_心理</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>102</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-PubMed_Abstracts">Pile-PubMed_Abstracts</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>22.4</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-PubMed_Abstracts">[36]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pubmed">Pubmed</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>42.1</td>
      <td>-</td>
      <td>马里兰大学</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/shibing624/medical/blob/main/pretrain/medical_book_zh.json">medical_book_zh</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>shibing624</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/epfl-llm/guidelines">guidelines</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>0.9</td>
      <td>-</td>
      <td>EPFL</td>
      <td>Custom</td>
      <td><a href="https://huggingface.co/datasets/epfl-llm/guidelines">[37]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/McGill-NLP/medal">medal</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>21</td>
      <td>-</td>
      <td>McGill University</td>
      <td>-</td>
      <td><a href="https://huggingface.co/datasets/McGill-NLP/medal">[38]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/Kent0n-Li/ChatDoctor">ChatDoctor</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0.1</td>
      <td>115k</td>
      <td>美国德克萨斯大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/Kent0n-Li/ChatDoctor">[39]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/qiuhuachuan/smile/tree/main/data">MeChat</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>310k</td>
      <td>浙江大学</td>
      <td>-</td>
      <td><a href="https://github.com/qiuhuachuan/smile/tree/main/data">[40]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/Suprit/CMtMedQA">CMtMedQA</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.1</td>
      <td>68k</td>
      <td>郑州大学自然语言处理实验室</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/Flmc/DISC-Med-SFT">DISC-Med-SFT</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.8</td>
      <td>465k</td>
      <td>复旦大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://huggingface.co/datasets/Flmc/DISC-Med-SFT">[41]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/FreedomIntelligence/Huatuo-26M">Huatuo-26M</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>5</td>
      <td>26M</td>
      <td>香港中文大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/FreedomIntelligence/Huatuo-26M">[42]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/FreedomIntelligence/HuatuoGPT-sft-data-v1">HuatuoGPT-sft-data-v1</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.3</td>
      <td>226k</td>
      <td>香港中文大学</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/Toyhom/Chinese-medical-dialogue-data">Chinese medical dialogue data</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.3</td>
      <td>792k</td>
      <td>上海科技大学</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/CMKRG/QiZhenGPT/blob/main/data/train/sft-20k.json">QiZhenGPT-sft-20k</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>20k</td>
      <td>浙江大学</td>
      <td>GPL 3.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/michaelwzhu/ChatMed_Consult_Dataset">ChatMed_Consult_Dataset</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.4</td>
      <td>549k</td>
      <td>中国农业大学</td>
      <td>CC BY 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/shibing624/medical">medical-sft</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>1.3</td>
      <td>2M</td>
      <td>shibing625</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/zhangsheng93/cMedQA2">cMedQA2</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>108k</td>
      <td>国防科技大学</td>
      <td>GPL 3.0</td>
      <td><a href="https://github.com/zhangsheng93/cMedQA2">[43]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/hejunqing/webMedQA">webMedQA</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>63k</td>
      <td>中国科学院</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/hejunqing/webMedQA">[44]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/pubmedqa/pubmedqa?tab=readme-ov-file">PubMedQA</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0.6</td>
      <td>-</td>
      <td>University of Pittsburgh</td>
      <td>MIT</td>
      <td><a href="https://github.com/pubmedqa/pubmedqa?tab=readme-ov-file">[45]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/WENGSYX/CMCQA?tab=readme-ov-file">CMCQA</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>2.8</td>
      <td>-</td>
      <td>中国科学院</td>
      <td>-</td>
      <td><a href="https://github.com/WENGSYX/CMCQA?tab=readme-ov-file">[46]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/UCSD26/medical_dialog">medical_dialog</a></td>
      <td>SFT</td>
      <td>中文 英文</td>
      <td>-</td>
      <td>1M</td>
      <td>University of California</td>
      <td>-</td>
      <td><a href="https://huggingface.co/datasets/UCSD26/medical_dialog">[47]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/abachaa/LiveQA_MedicalTask_TREC2017">LiveQA</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>0.7k</td>
      <td>美国国家医学图书馆</td>
      <td>-</td>
      <td><a href="https://github.com/abachaa/LiveQA_MedicalTask_TREC2017">[48]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://drive.google.com/file/d/1ImYUSLk9JbgHXOemfvyiDiirluZHPeQw/view?usp=sharing">MedQA</a></td>
      <td>SFT</td>
      <td>简中 繁中 英文</td>
      <td>0.3</td>
      <td>61k</td>
      <td>美国麻省理工学院</td>
      <td>MIT</td>
      <td><a href="https://drive.google.com/file/d/1ImYUSLk9JbgHXOemfvyiDiirluZHPeQw/view?usp=sharing">[49]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://drive.google.com/uc?export=download&id=15VkJdq5eyWIkfb_aoD3oS8i4tScbHYky">MedMCQA</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0.1</td>
      <td>192k</td>
      <td>Saama AI Research Institute</td>
      <td>MIT</td>
      <td><a href="https://drive.google.com/uc?export=download&id=15VkJdq5eyWIkfb_aoD3oS8i4tScbHYky">[50]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://static-content.springer.com/esm/art%3A10.1038%2Fs41586-023-06291-2/MediaObjects/41586_2023_6291_MOESM6_ESM.xlsx">HealthSearchQA</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>3k</td>
      <td>Google Research</td>
      <td>-</td>
      <td><a href="https://static-content.springer.com/esm/art%3A10.1038%2Fs41586-023-06291-2/MediaObjects/41586_2023_6291_MOESM6_ESM.xlsx">[51]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/BAAI/AquilaMed-Instruct">AquilaMed-Instruct</a></td>
      <td>SFT</td>
      <td>中文 英文</td>
      <td>0.2</td>
      <td>318k</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td><a href="https://huggingface.co/datasets/BAAI/AquilaMed-Instruct">[52]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/BAAI/AquilaMed-RL">AquilaMed-RL</a></td>
      <td>RLHF/RM</td>
      <td>中文 英文</td>
      <td>-</td>
      <td>13k</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td><a href="https://huggingface.co/datasets/BAAI/AquilaMed-RL">[53]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/SupritYoung/Zhongjing/blob/main/data/rlhf2000_7_31.json">Zhongjing-rlhf-2k</a></td>
      <td>RLHF/RM</td>
      <td>中文</td>
      <td>0</td>
      <td>2k</td>
      <td>郑州大学自然语言处理实验室</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/SupritYoung/Zhongjing/blob/main/data/rlhf2000_7_31.json">[54]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/shibing624/medical">reward-reward</a></td>
      <td>RLHF/RM</td>
      <td>中文</td>
      <td>0</td>
      <td>4k</td>
      <td>shibing626</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/FreedomIntelligence/CMB/blob/main/README_zh.md">CMB</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>11k</td>
      <td>香港中文大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/FreedomIntelligence/CMB/blob/main/README_zh.md">[55]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/CMKRG/QiZhenGPT/blob/main/data/eval/%E8%8D%AF%E5%93%81%E9%80%82%E5%BA%94%E7%97%87%E8%AF%84%E6%B5%8B%E6%95%B0%E6%8D%AE%E9%9B%86.csv">药品适应症评测</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>95</td>
      <td>浙江大学</td>
      <td>GPL 3.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://github.com/williamliujl/CMExam/">CMExam</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>68k</td>
      <td>阿里巴巴</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/williamliujl/CMExam/">[56]</a></td>
    </tr>
    <tr>
      <td>19.医学/健康/心理</td>
      <td><a href="https://medbench.opencompass.org.cn/">MedBench</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>300k</td>
      <td>上海人工智能实验室</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td>IndustryCorpus2.0-法律_司法</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>78</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://opendatalab.com/OpenDataLab/International-Arbitration-Dataset">国际仲裁法律、规则与实践数据集</a></td>
      <td>PT</td>
      <td>-</td>
      <td>0</td>
      <td>-</td>
      <td>大模型语料数据联盟</td>
      <td>CC BY-NC 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-FreeLaw">Pile-FreeLaw</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>50.1</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-FreeLaw">[57]</a></td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://opendatalab.com/ABear/Legal_Legislation">法律法规数据库</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>OpenDataLab</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0/tree/main?source=R2l0aHVi">WanJuan1.0-CN/Law</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>37.9</td>
      <td>-</td>
      <td>上海人工智能实验室</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0/tree/main?source=R2l0aHVi">[58]</a></td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://huggingface.co/datasets/TigerResearch/tigerbot-law-plugin">TigerBot-law</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0</td>
      <td>56k</td>
      <td>Tiger Research</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://github.com/siat-nlp/HanFei?tab=readme-ov-file">HanFei</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.2</td>
      <td>-</td>
      <td>中科院深圳先进院</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://huggingface.co/datasets/ShengbinYue/DISC-Law-SFT?row=0">DISC-Law-SFT</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.4</td>
      <td>295k</td>
      <td>复旦大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://huggingface.co/datasets/ShengbinYue/DISC-Law-SFT?row=0">[59]</a></td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://github.com/LiuHC0428/LAW-GPT">LawGPT_zh</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>144k</td>
      <td>上海交通大学</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://github.com/dengwentao99/SLJA">SLJA</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.2</td>
      <td>-</td>
      <td>山东大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/dengwentao99/SLJA">[60]</a></td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://github.com/Dai-shen/LAiW/blob/main/data/README.md">LAiW</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>11k</td>
      <td>四川大学</td>
      <td>MIT</td>
      <td><a href="https://github.com/Dai-shen/LAiW/blob/main/data/README.md">[61]</a></td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://github.com/FudanDISC/DISC-LawLLM">DISC-Law-Eval-Benchmark</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>复旦大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/FudanDISC/DISC-LawLLM">[62]</a></td>
    </tr>
    <tr>
      <td>20.法律/司法</td>
      <td><a href="https://github.com/open-compass/LawBench">LawBench</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>10k</td>
      <td>上海人工智能实验室</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/open-compass/LawBench">[63]</a></td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td>IndustryCorpus2.0-金融_经济</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>73</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EDT">EDT</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>0.5</td>
      <td>-</td>
      <td>东北大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EDT">[64]</a></td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/ssymmetry/BBT-FinCUGE-Applications">BBT-FinCorpus</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>16</td>
      <td>-</td>
      <td>复旦大学</td>
      <td>-</td>
      <td><a href="https://github.com/ssymmetry/BBT-FinCUGE-Applications">[65]</a></td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://huggingface.co/datasets/Duxiaoman-DI/FinCorpus?row=0">FinCorpus</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>60</td>
      <td>-</td>
      <td>度小满</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/TigerResearch/TigerBot?tab=readme-ov-file#%E5%BC%80%E6%BA%90%E6%95%B0%E6%8D%AE%E9%9B%86">TigerBot</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>1.1</td>
      <td>-</td>
      <td>Tiger Research</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/FudanDISC/DISC-FinLLM/tree/main/data">DISC-Fin-SFT</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>400</td>
      <td>复旦大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/FudanDISC/DISC-FinLLM/tree/main/data">[66]</a></td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=7">DuEE-fin</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>百度</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/AI4Finance-Foundation/FinGPT">FinGPT</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>205k</td>
      <td>University of California</td>
      <td>MIT</td>
      <td><a href="https://github.com/AI4Finance-Foundation/FinGPT">[67]</a></td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://huggingface.co/datasets/Duxiaoman-DI/FinanceIQ">FinanceIQ</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>度小满</td>
      <td>CC BY-NC-SA 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/The-FinAI/PIXIU">FinBen</a></td>
      <td>Evaluation</td>
      <td>中文 英文 西班牙</td>
      <td>0</td>
      <td>7k</td>
      <td>The Fin AI</td>
      <td>Custom</td>
      <td><a href="https://github.com/The-FinAI/PIXIU">[68]</a></td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/SUFE-AIFLM-Lab/FinEval/blob/main/README_zh-CN.md">FinEval</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>8k</td>
      <td>上海财经大学</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://github.com/SUFE-AIFLM-Lab/FinEval/blob/main/README_zh-CN.md">[69]</a></td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/ssymmetry/BBT-FinCUGE-Applications">CFLEB</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>0</td>
      <td>11k</td>
      <td>复旦大学</td>
      <td>-</td>
      <td><a href="https://github.com/ssymmetry/BBT-FinCUGE-Applications">[70]</a></td>
    </tr>
    <tr>
      <td>22. 体育</td>
      <td>IndustryCorpus2.0-体育</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>78.3</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>22. 体育</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=68">K-SportsSum</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>8k</td>
      <td>苏州大学</td>
      <td>-</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=68">[71]</a></td>
    </tr>
    <tr>
      <td>22. 体育</td>
      <td><a href="https://github.com/google-research-datasets/Taskmaster/tree/master/TM-2-2020">Taskmaster-2-phy</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>9k</td>
      <td>Google</td>
      <td>CC BY 4.0</td>
      <td><a href="https://github.com/google-research-datasets/Taskmaster/tree/master/TM-2-2020">[72]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td>IndustryCorpus2.0-影视_娱乐</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>65</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-OpenSubtitles">Pile-OpenSubtitles</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>6.7</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-OpenSubtitles">[73]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/IMDb">IMDb</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>0.9</td>
      <td>-</td>
      <td>斯坦福大学</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://github.com/SophonPlus/ChineseNlpCorpus/blob/master/datasets/ez_douban/intro.ipynb">ez_douban</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.1</td>
      <td>3M</td>
      <td>豆瓣电影</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://github.com/SophonPlus/ChineseNlpCorpus/blob/master/datasets/dmsc_v2/intro.ipynb">dmsc_v2</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.1</td>
      <td>2M</td>
      <td>豆瓣电影</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>24. 游戏</td>
      <td>IndustryCorpus2.0-游戏</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>9.3</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>24. 游戏</td>
      <td><a href="https://huggingface.co/datasets/liwu/MNBVC">MNBVC-game</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>MOP里屋社区</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>25. 时政/政务/行政</td>
      <td>IndustryCorpus2.0-政务</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>141</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>25. 时政/政务/行政</td>
      <td><a href="https://huggingface.co/datasets/liwu/MNBVC">MNBVC-politics</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0.4</td>
      <td>-</td>
      <td>MOP里屋社区</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>25. 时政/政务/行政</td>
      <td><a href="https://opendatalab.com/ABear/Marxist_Literature_CN">中文马克思主义文库</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0</td>
      <td>-</td>
      <td>OpenDataLab</td>
      <td>MBODL-BY-NC-SA 1.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>25. 时政/政务/行政</td>
      <td><a href="https://huggingface.co/datasets/wenge-research/yayi2_pretrain_data">yayi2_pretrain_data</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>-</td>
      <td>-</td>
      <td>中科闻歌</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td>IndustryCorpus2.0-文学_情感</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>33</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/ABear/Classics_Ancient_CN">国学迷-古籍</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>2.7</td>
      <td>-</td>
      <td>OpenDataLab</td>
      <td>MBODL-BY-NC-SA 1.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-PhilPapers">Pile-PhilPapers</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>2.2</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-PhilPapers">[74]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/ahhh/ChineseTraditionalCulture1">古诗词数据集</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0.4</td>
      <td>-</td>
      <td>-</td>
      <td>CC BY 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://github.com/chinese-poetry/chinese-poetry">中华古诗词数据库</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>-</td>
      <td>-</td>
      <td>jackeyGao</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/ABear/Poetry_CN">古诗词</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>7.1</td>
      <td>-</td>
      <td>OpenDataLab</td>
      <td>MBODL-BY-NC-SA 1.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-Gutenberg">Pile-Gutenberg</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>10.5</td>
      <td>-</td>
      <td>EleutherAI</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Pile-Gutenberg">[75]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://github.com/siat-nlp/MAMS-for-ABSA">MAMS</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>-</td>
      <td>中国科学院</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/siat-nlp/MAMS-for-ABSA">[76]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=17">ASAP</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>33k</td>
      <td>美团</td>
      <td>-</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=17">[77]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://github.com/CLUEbenchmark/FewCLUE">EPRSTMT</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>20k</td>
      <td>CLUE team</td>
      <td>MIT</td>
      <td><a href="https://github.com/CLUEbenchmark/FewCLUE">[78]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EmpatheticDialogues">EmpatheticDialogues</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>25k</td>
      <td>华盛顿大学</td>
      <td>CC BY-NC 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EmpatheticDialogues">[79]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Allegro_Reviews">Allegro Reviews</a></td>
      <td>SFT</td>
      <td>波兰语</td>
      <td>0</td>
      <td>12k</td>
      <td>Allegro Machine Learning Research</td>
      <td>CC BY-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Allegro_Reviews">[80]</a></td>
    </tr>
    <tr>
      <td>27. 旅游/地理</td>
      <td>IndustryCorpus2.0-旅游_地理</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>27</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>27. 旅游/地理</td>
      <td><a href="https://modelscope.cn/datasets/damo/GeoGLUE/summary">GeoGLUE</a></td>
      <td>Evaluation</td>
      <td>中文</td>
      <td>-</td>
      <td>250k</td>
      <td>Institute for Intelligent Computing</td>
      <td>CC BY-NC 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td>IndustryCorpus2.0-住宿_餐饮_酒店</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>7.8</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://github.com/Diego999/HotelRec?tab=readme-ov-file">HotelRec</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>13.4</td>
      <td>-</td>
      <td>洛桑联邦理工学院</td>
      <td>Custom</td>
      <td><a href="https://github.com/Diego999/HotelRec?tab=readme-ov-file">[81]</a></td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://snap.stanford.edu/data/web-FineFoods.html">Amazon Fine Foods</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0.1</td>
      <td>568k</td>
      <td>斯坦福大学</td>
      <td>-</td>
      <td><a href="https://snap.stanford.edu/data/web-FineFoods.html">[82]</a></td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://github.com/SophonPlus/ChineseNlpCorpus/blob/master/datasets/ChnSentiCorp_htl_all/intro.ipynb">ChnSentiCorp_htl_all</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>7k</td>
      <td>携程网</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://github.com/SophonPlus/ChineseNlpCorpus/blob/master/datasets/waimai_10k/intro.ipynb">waimai_10k</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>12k</td>
      <td>某外卖平台</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://counterfactual-recipe-generation.github.io/dataset_en.html">XiaChuFang Recipe Corpus</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.6</td>
      <td>2M</td>
      <td>清华大学</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://github.com/SophonPlus/ChineseNlpCorpus/blob/master/datasets/yf_dianping/intro.ipynb">yf_dianping</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0.7</td>
      <td>44k</td>
      <td>大众点评</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://github.com/google-research-datasets/Taskmaster/tree/master/TM-2-2020">Taskmaster-2</a></td>
      <td>SFT</td>
      <td>英文</td>
      <td>0</td>
      <td>6k</td>
      <td>Google</td>
      <td>CC BY 4.0</td>
      <td><a href="https://github.com/google-research-datasets/Taskmaster/tree/master/TM-2-2020">[83]</a></td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td>IndustryCorpus2.0-新闻传媒</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>18.1</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0/tree/main?source=R2l0aHVi">WanJuan1.0-CN/ChinaNews</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>21.5</td>
      <td>-</td>
      <td>上海人工智能实验室</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0/tree/main?source=R2l0aHVi">[84]</a></td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://opendatalab.com/ABear/News_Text">新闻联播文字版</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>0.5</td>
      <td>-</td>
      <td>OpenDataLab</td>
      <td>MBODL-BY-NC-SA 1.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://opendatalab.com/OpenDataLab/RealNews">RealNews</a></td>
      <td>PT</td>
      <td>英文</td>
      <td>46.4</td>
      <td>-</td>
      <td>华盛顿大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/RealNews">[85]</a></td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://opendatalab.com/OpenDataLab/NAIST_COVID">NAIST COVID</a></td>
      <td>PT</td>
      <td>中文 英文 日文</td>
      <td>9.6</td>
      <td>-</td>
      <td>Nara Institute of Science and Technology</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/NAIST_COVID">[86]</a></td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://opendatalab.com/OpenDataLab/OpenNewsArchive">OpenNewsArchive</a></td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>11.7</td>
      <td>-</td>
      <td>大模型语料数据联盟</td>
      <td>CC BY 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://github.com/brightmart/nlp_chinese_corpus">news2016zh</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>9</td>
      <td>-</td>
      <td>CLUEbenchmark</td>
      <td>MIT</td>
      <td>-</td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="http://thuctc.thunlp.org/#%E8%8E%B7%E5%8F%96%E9%93%BE%E6%8E%A5">清华新闻分类语料</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>2.2</td>
      <td>-</td>
      <td>清华大学</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>30. 安全</td>
      <td>IndustryCorpus2.0-安全</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>1.8</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>30. 安全</td>
      <td><a href="https://opendatalab.com/OpenDataLab/cybersac2023">中国网络安全中文基础语料库</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>99.7</td>
      <td>-</td>
      <td>中国网络空间安全协会</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>30. 安全</td>
      <td><a href="https://github.com/Clouditera/secgpt">security-paper-datasets</a></td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>0.7</td>
      <td>-</td>
      <td>云起无垠</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>30. 安全</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=71">食品安全主题数据集</a></td>
      <td>SFT</td>
      <td>中文</td>
      <td>0</td>
      <td>10k</td>
      <td>东北证券</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td>IndustryCorpus2.0-其他</td>
      <td>PT</td>
      <td>中文 英文</td>
      <td>80</td>
      <td>-</td>
      <td>BAAI</td>
      <td>Apache 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://github.com/CLUEbenchmark/CLUECorpus2020">CLUECorpus2020</a></td>
      <td>PT</td>
      <td>中文</td>
      <td>100</td>
      <td>-</td>
      <td>CLUE Organization</td>
      <td>-</td>
      <td><a href="https://github.com/CLUEbenchmark/CLUECorpus2020">[87]</a></td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://huggingface.co/datasets/openai/webgpt_comparisons?row=30">WebGPT</a></td>
      <td>RLHF/RM</td>
      <td>英文</td>
      <td>0.2</td>
      <td>20k</td>
      <td>OpenAI</td>
      <td>-</td>
      <td><a href="https://huggingface.co/datasets/openai/webgpt_comparisons?row=30">[88]</a></td>
    </tr>
  <tbody>
</table>

👆 [<b>BACK to Table of Contents</b> -->](#目录)


## 视觉数据集

<table border='1' class='dataframe'>
    <thead>
      <tr style='text-align: left;'>
        <th>Industry</th>
        <th>Dataset</th>
        <th>Type</th>
        <th>Language</th>
        <th>Size</th>
        <th>Publisher</th>
        <th>License</th>
        <th>Paper</th>
      </tr>
    </thead>
    <tbody>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://tianchi.aliyun.com/dataset/175522">香蕉成熟度分类</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>0.2</td>
      <td>aliyun4949246966</td>
      <td>GPL 2.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CD_and_S">CD&S</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>13.5</td>
      <td>普渡大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CD_and_S">[1]</a></td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://tianchi.aliyun.com/dataset/74952">Barley Remote Sensing</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>4.2</td>
      <td>广州泾渭信息科技</td>
      <td>CC BY-NC-SA 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Global_Wheat">Global Wheat</a></td>
      <td>图像</td>
      <td>-</td>
      <td>15.4</td>
      <td>东京大学</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Global_Wheat">[2]</a></td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://opendatalab.com/OpenDataLab/ACFR_Orchard_Fruit_Dataset">ACFR_Orchard_Fruit</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>3.8</td>
      <td>悉尼大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/ACFR_Orchard_Fruit_Dataset">[3]</a></td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://opendatalab.com/OpenDataLab/PASTIS">PASTIS</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>26.8</td>
      <td>LASTIG, Univ. Gustave Eiffel</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/PASTIS">[4]</a></td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://tianchi.aliyun.com/dataset/160100">PlantVillage Dataset</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>1.7</td>
      <td>游客5lkphlzhcgmho</td>
      <td>CC BY-NC-SA 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset">Stanford Cars Dataset</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>2</td>
      <td>斯坦福大学</td>
      <td>-</td>
      <td><a href="https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset">[5]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDataLab/VisDrone">VisDrone 2021</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>98.4</td>
      <td>天津大学</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/VisDrone">[6]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDataLab/The_Comprehensive_Cars">CompCars</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>1.9</td>
      <td>香港中文大学</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/The_Comprehensive_Cars">[7]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDataLab/COWC">COWC</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>10.4</td>
      <td>Lawrence Livermore National Laboratory</td>
      <td>AGPL 3.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/COWC">[8]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDataLab/RadarScenes">RadarScenes</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>10.7</td>
      <td>Mercedes-Benz AG</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/RadarScenes">[9]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CCPD">CCPD</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>12.6</td>
      <td>中国科学技术大学</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CCPD">[10]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://www.kaggle.com/datasets/yamaerenay/100-images-of-top-50-car-brands">车型分类</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>0</td>
      <td>TU Berlin</td>
      <td>CDLA 1.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>3. 采矿</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>4. 石油化工</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>5. 电力能源</td>
      <td><a href="https://github.com/zae-bayern/elpv-dataset">elpv-dataset</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>0</td>
      <td>Nuremberg Institute of Technology</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://github.com/zae-bayern/elpv-dataset">[11]</a></td>
    </tr>
    <tr>
      <td>5. 电力能源</td>
      <td><a href="https://github.com/InsulatorData/InsulatorDataSet">InsulatorDataSet</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>0.4</td>
      <td>WANG Zi-Hao</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td><a href="https://opendatalab.com/OpenDataLab/AGAR">AGAR</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>31</td>
      <td>University of Wroclaw</td>
      <td>CC BY-NC 2.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/AGAR">[12]</a></td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td><a href="https://opendatalab.com/OpenDataLab/DOTA_V2_dot_0">DOTA v2.0</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>137.5</td>
      <td>武汉大学</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td><a href="https://opendatalab.com/OpenDataLab/LoveDA">LoveDA</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>11.9</td>
      <td>武汉大学</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/LoveDA">[13]</a></td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td><a href="https://opendatalab.com/OpenDataLab/So2Sat_LCZ42">So2Sat LCZ42</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>110.1</td>
      <td>Technical University of Munich</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/So2Sat_LCZ42">[14]</a></td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Aerial_imagery_dataset">Aerial imagery dataset</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>26.5</td>
      <td>武汉大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Aerial_imagery_dataset">[15]</a></td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td><a href="https://opendatalab.com/OpenDataLab/xiong_an_ma_ti_wan_cun_hang_kong_gao_etc">航空高光谱遥感影像</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>1.7</td>
      <td>中国科学院</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/xiong_an_ma_ti_wan_cun_hang_kong_gao_etc">[16]</a></td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td><a href="https://www.cvmart.net/dataSets/detail/853?channel_id=op10&utm_source=cvmartmp&utm_campaign=datasets&utm_medium=article">AeBAD</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>1.5</td>
      <td>西安交通大学</td>
      <td>-</td>
      <td><a href="https://www.cvmart.net/dataSets/detail/853?channel_id=op10&utm_source=cvmartmp&utm_campaign=datasets&utm_medium=article">[17]</a></td>
    </tr>
    <tr>
      <td>8. 其他制造业</td>
      <td><a href="http://faculty.neu.edu.cn/songkechen/zh_CN/zdylm/263270/list/">NEU-CLS</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>0</td>
      <td>东北大学</td>
      <td>-</td>
      <td><a href="http://faculty.neu.edu.cn/songkechen/zh_CN/zdylm/263270/list/">[18]</a></td>
    </tr>
    <tr>
      <td>8. 其他制造业</td>
      <td><a href="https://www.kaggle.com/competitions/severstal-steel-defect-detection/data">Severstal</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>1.7</td>
      <td>Severstal</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>8. 其他制造业</td>
      <td><a href="https://www.vicos.si/resources/kolektorsdd/">KolektorSDD</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>-</td>
      <td>University of Ljubljana</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://www.vicos.si/resources/kolektorsdd/">[19]</a></td>
    </tr>
    <tr>
      <td>8. 其他制造业</td>
      <td><a href="https://tianchi.aliyun.com/dataset/140666">天池铝型材表面瑕疵</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>3</td>
      <td>天池小喵萌</td>
      <td>CC BY-NC 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>9. 计算机/通信</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>10. 计算机编程</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>11. 人工智能</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>12. 其他信息服务</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>13. 房地产/建筑</td>
      <td><a href="https://opendatalab.com/OpenDataLab/BuildingNet">BuildingNet</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>10.8</td>
      <td>UMass Amherst</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/BuildingNet">[20]</a></td>
    </tr>
    <tr>
      <td>13. 房地产/建筑</td>
      <td><a href="https://opendatalab.com/OpenDataLab/FloorPlanCAD">FloorPlanCAD</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>5.4</td>
      <td>阿里巴巴</td>
      <td>CC BY-NC 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/FloorPlanCAD">[21]</a></td>
    </tr>
    <tr>
      <td>13. 房地产/建筑</td>
      <td><a href="https://opendatalab.com/OpenDataLab/xBD">xBD</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>30.5</td>
      <td>Carnegie Mellon University</td>
      <td>BSD 3-Clause</td>
      <td><a href="https://opendatalab.com/OpenDataLab/xBD">[22]</a></td>
    </tr>
    <tr>
      <td>13. 房地产/建筑</td>
      <td><a href="https://opendatalab.com/OpenDataLab/S2Looking">S2Looking</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>11.4</td>
      <td>北京遥感研究所</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/S2Looking">[23]</a></td>
    </tr>
    <tr>
      <td>13. 房地产/建筑</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Houses3K">House3K</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>28.2</td>
      <td>University of the Philippines</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Houses3K">[24]</a></td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Caltech_Pedestrian_Detection_etc">Caltech Pedestrian Detection Benchmark</a></td>
      <td>视频</td>
      <td>英文</td>
      <td>11.3</td>
      <td>California Institute of Technology</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Caltech_Pedestrian_Detection_etc">[25]</a></td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://opendatalab.com/OpenDataLab/LDDRS">LDDRS</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>1.7</td>
      <td>西北工业大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/LDDRS">[26]</a></td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://opendatalab.com/OpenDataLab/FRSign">FRSign</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>590</td>
      <td>Institut de Recherche Technologique SystemX</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/FRSign">[27]</a></td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://opendatalab.com/OpenDataLab/TRANCOS">TRANCOS</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>1.5</td>
      <td>University of Alcalá</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/TRANCOS">[28]</a></td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://opendatalab.com/OpenDataLab/S2TLD">S2TLD</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>1.4</td>
      <td>上海交通大学</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/S2TLD">[29]</a></td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CCD">CCD</a></td>
      <td>视频</td>
      <td>英文</td>
      <td>67.1</td>
      <td>Rochester Institute of Technology</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CCD">[30]</a></td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://github.com/cuilimeng/CrackForest-dataset">CrackForest</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>0</td>
      <td>University of Chinese Academy of Sciences</td>
      <td>Custom</td>
      <td><a href="https://github.com/cuilimeng/CrackForest-dataset">[31]</a></td>
    </tr>
    <tr>
      <td>15. 水利/海洋</td>
      <td><a href="https://zenodo.org/records/5151941">MARIDA</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>1.2</td>
      <td>National Technical University of Athens</td>
      <td>CC BY 4.0</td>
      <td><a href="https://zenodo.org/records/5151941">[32]</a></td>
    </tr>
    <tr>
      <td>15. 水利/海洋</td>
      <td><a href="https://opendatalab.com/OpenDataLab/SUIM">SUIM</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>0.2</td>
      <td>University of Minnesota</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/SUIM">[33]</a></td>
    </tr>
    <tr>
      <td>16. 数学</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.com/OpenDataLab/HRSC2016">HRSC2016</a></td>
      <td>图像</td>
      <td>-</td>
      <td>3.5</td>
      <td>西北工业大学</td>
      <td>ODbl 1.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Chikusei_Dataset">Chikusei Dataset</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>2.3</td>
      <td>东京大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Chikusei_Dataset">[34]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/OpenGVLab/SAM-Med2D">SA-Med2D-20M</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>328.6</td>
      <td>上海人工智能实验室</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/OpenGVLab/SAM-Med2D">[35]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/IXI">IXI</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>27.4</td>
      <td>University of Bucharest</td>
      <td>CC BY-SA 3.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/IXI">[36]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/LoDoPaB-CT">LoDoPaB-CT</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>51.5</td>
      <td>University of Bremen</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/LoDoPaB-CT">[37]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MedFMC">MedFMC</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>38.4</td>
      <td>opendatalab</td>
      <td>CC BY-SA 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CHAOS">CHAOS</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>2.7</td>
      <td>Dokuz Eylul University</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CHAOS">[38]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/IntrA">IntrA</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>2.3</td>
      <td>东京大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/IntrA">[39]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/jiyuanmedical/HS-CMU">宫腔镜图像良恶性病变</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>0.4</td>
      <td>北京朝阳医院</td>
      <td>CC BY-NC-SA 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/HC18">HC18</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>0.3</td>
      <td>Radboud University Medical Center</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/HC18">[40]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/staryu/BUSI">Breast Ultrasound Images Dataset</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>0.2</td>
      <td>Faculty of Computer and Artificial Intelligence</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/staryu/BUSI">[41]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://vios-s.github.io/multiscale-adversarial-attention-gates/data">ACDC Scribbles</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>0</td>
      <td>University of Edinburgh</td>
      <td>-</td>
      <td><a href="https://vios-s.github.io/multiscale-adversarial-attention-gates/data">[42]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Medical_Segmentation_Decathlon">Medical Segmentation Decathlon</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>72.5</td>
      <td>MONAI Development Team</td>
      <td>CC BY-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Medical_Segmentation_Decathlon">[43]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/LIDC-IDRI">LIDC-IDRI</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>61.5</td>
      <td>The University of Chicago</td>
      <td>CC BY 3.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/LIDC-IDRI">[44]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/openmedlab/Awesome-Medical-Dataset">Medical Imaging</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>22. 体育</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/DeepScores">DeepScores</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>76.8</td>
      <td>ZHAW Datalab & USI</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/DeepScores">[45]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/UCO-LAEO">UCO-LAEO</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>4.7</td>
      <td>University of Cordoba</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/UCO-LAEO">[46]</a></td>
    </tr>
    <tr>
      <td>24. 游戏</td>
      <td><a href="https://opendatalab.com/OpenDataLab/GLIB_image_dataset">GLIB: image dataset</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>10.2</td>
      <td>Fuxi AI Lab in Netease</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/GLIB_image_dataset">[47]</a></td>
    </tr>
    <tr>
      <td>24. 游戏</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CocoDoom">CocoDoom</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>14.7</td>
      <td>牛津大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CocoDoom">[48]</a></td>
    </tr>
    <tr>
      <td>25. 时政/政务/行政</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>27. 旅游/地理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/European_Flood_2013_Dataset">European Flood 2013</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>11.6</td>
      <td>Friedrich Schiller University Jena</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/European_Flood_2013_Dataset">[49]</a></td>
    </tr>
    <tr>
      <td>27. 旅游/地理</td>
      <td><a href="https://phototour.cs.washington.edu/datasets/">Notre Dame</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>1.8</td>
      <td>Photo Tourism group</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>27. 旅游/地理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/OmniCity">OmniCity</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>14.4</td>
      <td>中山大学</td>
      <td>CC BY-NC 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/OmniCity">[50]</a></td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Hotels-50K">Hotels-50K</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>3.1</td>
      <td>George Washington University</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Hotels-50K">[51]</a></td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0/tree/main?source=R2l0aHVi">WanJuan1.0-video</a></td>
      <td>视频</td>
      <td>中文</td>
      <td>916.7</td>
      <td>上海人工智能实验室</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0/tree/main?source=R2l0aHVi">[52]</a></td>
    </tr>
    <tr>
      <td>30. 安全</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MovingFashion">MovingFashion</a></td>
      <td>视频</td>
      <td>英文</td>
      <td>24.1</td>
      <td>University of Verona</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MovingFashion">[53]</a></td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://opendatalab.com/OpenDataLab/VegFru">VegFru</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>13.1</td>
      <td>中国科学技术大学</td>
      <td>Apache 2.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/VegFru">[54]</a></td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://github.com/switchablenorms/DeepFashion2">DeepFashion2</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>14.7</td>
      <td>香港中文大学</td>
      <td>-</td>
      <td><a href="https://github.com/switchablenorms/DeepFashion2">[55]</a></td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://github.com/Charmve/Surface-Defect-Detection/tree/master/DeepPCB">DeepPCB</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>-</td>
      <td>上海交通大学</td>
      <td>-</td>
      <td><a href="https://github.com/Charmve/Surface-Defect-Detection/tree/master/DeepPCB">[56]</a></td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://hci.iwr.uni-heidelberg.de/content/weakly-supervised-learning-industrial-optical-inspection">DAGM 2007</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>2.9</td>
      <td>Robert Bosch Corporate Research department</td>
      <td>CC BY 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://github.com/Charmve/Surface-Defect-Detection/tree/master/Magnetic-Tile-Defect">磁瓦缺陷</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>-</td>
      <td>University of Chinese Academy of Sciences</td>
      <td>-</td>
      <td><a href="https://github.com/Charmve/Surface-Defect-Detection/tree/master/Magnetic-Tile-Defect">[57]</a></td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://user.it.uu.se/~gusky180/texture/">Kylberg Texture Dataset v. 1.0</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>11.6</td>
      <td>Swedish University of Agricultural Sciences and Uppsala University</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://aistudio.baidu.com/datasetdetail/44820">手扶电梯梯级缺陷</a></td>
      <td>图像</td>
      <td>中文</td>
      <td>0</td>
      <td>LJY0031</td>
      <td>CC0 1.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://github.com/2Obe/BSData">BSData</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>-</td>
      <td>sungsy</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://www.cvmart.net/dataSets/detail/855?channel_id=op10&utm_source=cvmartmp&utm_campaign=datasets&utm_medium=article">BeanTech</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>1.1</td>
      <td>University of Udine</td>
      <td>CC BY-SA 4.0</td>
      <td><a href="https://www.cvmart.net/dataSets/detail/855?channel_id=op10&utm_source=cvmartmp&utm_campaign=datasets&utm_medium=article">[58]</a></td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://www.mvtec.com/company/research/datasets/mvtec-ad">MVTec异常检测</a></td>
      <td>图像</td>
      <td>英文</td>
      <td>-</td>
      <td>Technical University of Munich</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://www.mvtec.com/company/research/datasets/mvtec-ad">[59]</a></td>
    </tr>
  <tbody>
</table>

👆 [<b>BACK to Table of Contents</b> -->](#目录)


## 多模态数据集

<table border='1' class='dataframe'>
    <thead>
      <tr style='text-align: left;'>
        <th>Industry</th>
        <th>Dataset</th>
        <th>Type</th>
        <th>Language</th>
        <th>Size</th>
        <th>Publisher</th>
        <th>License</th>
        <th>Paper</th>
      </tr>
    </thead>
    <tbody>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://tianchi.aliyun.com/dataset/141337">Pigs4YOLO</a></td>
      <td>图像-文本</td>
      <td>中文</td>
      <td>0.1</td>
      <td>zhengvh</td>
      <td>CC BY-NC-SA 4.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Lincolnbeet">Lincolnbeet</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>26.6</td>
      <td>University of Lincoln</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Lincolnbeet">[1]</a></td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://opendatalab.com/OpenDataLab/A_Dataset_of_Multispectral_etc">Multispectral_etc</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.7</td>
      <td>University of Idaho</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/A_Dataset_of_Multispectral_etc">[2]</a></td>
    </tr>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EuroCrops">EuroCrops</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>2</td>
      <td>Technical University of Munich (TUM)</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EuroCrops">[3]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Lyft_Level_5_Prediction">Lyft Level 5 Prediction</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>19.8</td>
      <td>Lyft Level 5</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Lyft_Level_5_Prediction">[4]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDataLab/nuScenes">nuScenes</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>346.5</td>
      <td>APTIV Company</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/nuScenes">[5]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDataLab/DDAD">DDAD</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>269</td>
      <td>Toyota Research Institute</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/DDAD">[6]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://github.com/OpenDriveLab/OpenLane">OpenLane</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>122.5</td>
      <td>上海人工智能实验室</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://github.com/OpenDriveLab/OpenLane">[7]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDriveLab/OpenLane-V2">OpenLane-V2</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>193.3</td>
      <td>上海人工智能实验室</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDriveLab/OpenLane-V2">[8]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://opendatalab.com/OpenDataLab/ONCE">ONCE</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>1917.4</td>
      <td>华为</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/ONCE">[9]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://github.com/OpenDriveLab/OpenScene">OpenScen</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>3739.6</td>
      <td>上海人工智能实验室</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://github.com/OpenDriveLab/OpenScene">[10]</a></td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://www.kaggle.com/datasets/andrewmvd/car-plate-detection">Car License Plate Detection</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.2</td>
      <td>Hospital Israelita Albert Einstein</td>
      <td>CC0 1.0</td>
      <td>-</td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td><a href="https://tianchi.aliyun.com/dataset/95516">CVPR 2018 WAD</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>103</td>
      <td>CVPR 2018 WAD</td>
      <td>Custom</td>
      <td>-</td>
    </tr>
    <tr>
      <td>3. 采矿</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>4. 石油化工</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>5. 电力能源</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td><a href="https://opendatalab.com/OpenDataLab/RSICD">RSICD</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.6</td>
      <td>中国科学院</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/RSICD">[11]</a></td>
    </tr>
    <tr>
      <td>8. 其他制造业</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>9. 计算机/通信</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>10. 计算机编程</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>11. 人工智能</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>12. 其他信息服务</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>13. 房地产/建筑</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Reasonable_Crowd">Reasonable Crowd</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>27.5</td>
      <td>Motional. Boston, MA</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Reasonable_Crowd">[12]</a></td>
    </tr>
    <tr>
      <td>15. 水利/海洋</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>16. 数学</td>
      <td><a href="https://github.com/opendatalab/UniMERNet">UniMERNet</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>2</td>
      <td>上海人工智能实验室</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/opendatalab/UniMERNet">[13]</a></td>
    </tr>
    <tr>
      <td>16. 数学</td>
      <td><a href="https://huggingface.co/datasets/AI4Math/MathVista?row=2">MathVista</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.9</td>
      <td>University of California</td>
      <td>CC BY-SA 4.0</td>
      <td><a href="https://huggingface.co/datasets/AI4Math/MathVista?row=2">[14]</a></td>
    </tr>
    <tr>
      <td>16. 数学</td>
      <td><a href="https://huggingface.co/datasets/dali-does/clevr-math?row=23">clevr-math</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>19</td>
      <td>Umeå university</td>
      <td>CC BY 4.0</td>
      <td><a href="https://huggingface.co/datasets/dali-does/clevr-math?row=23">[15]</a></td>
    </tr>
    <tr>
      <td>16. 数学</td>
      <td><a href="https://opendatalab.com/OpenDataLab/GeoQA">GeoQA</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.4</td>
      <td>中山大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/GeoQA">[16]</a></td>
    </tr>
    <tr>
      <td>16. 数学</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Geometry3K">Geometry3K</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.3</td>
      <td>University of California</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Geometry3K">[17]</a></td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Visual_Question_Answering">Visual Question Answering</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>42.2</td>
      <td>Virginia Tech</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Visual_Question_Answering">[18]</a></td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://huggingface.co/datasets/derek-thomas/ScienceQA?row=11">ScienceQA</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.6</td>
      <td>University of California</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://huggingface.co/datasets/derek-thomas/ScienceQA?row=11">[19]</a></td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://opendatalab.com/OpenDataLab/DVQA">DVQA</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>5.3</td>
      <td>Rochester Institute of Technology</td>
      <td>CC BY-NC 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/DVQA">[20]</a></td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://opendatalab.com/OpenDataLab/AI2D">AI2D</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>1.7</td>
      <td>Allen Institute for Artificial Intelligence</td>
      <td>CC BY-SA 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/AI2D">[21]</a></td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://opendatalab.com/OpenDataLab/TextVQA">TextVQA</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>8.6</td>
      <td>Facebook AI Research</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/TextVQA">[22]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.com/OpenDataLab/QASPER">QASPER</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.6</td>
      <td>Allen Institute for AI</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/QASPER">[23]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.com/OpenDataLab/THCHS-30">THCHS-30</a></td>
      <td>语音-文本</td>
      <td>中文</td>
      <td>7.9</td>
      <td>清华大学</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/THCHS-30">[24]</a></td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://opendatalab.com/OpenDataLab/AISHELL-1">AISHELL-1</a></td>
      <td>语音-文本</td>
      <td>中文</td>
      <td>14.5</td>
      <td>Beijing Shell Shell Technology Co. Ltd</td>
      <td>Apache 2.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/AISHELL-1">[25]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MedVidQA">MedVidQA</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>3.6</td>
      <td>National Institutes of Health, USA</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MedVidQA">[26]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Kvasir">Kvasir</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>3.6</td>
      <td>University of Oslo</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Kvasir">[27]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/BAAI-DCAI/M3D?tab=readme-ov-file#data">M3D-Data</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>1208</td>
      <td>BAAI，港中文</td>
      <td>Apache 2.0</td>
      <td><a href="https://github.com/BAAI-DCAI/M3D?tab=readme-ov-file#data">[28]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/WangRongsheng/XrayGLM/tree/main">OpenI-zh</a></td>
      <td>图像-文本</td>
      <td>中文 英文</td>
      <td>0.1</td>
      <td>澳门理工大学</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://osf.io/89kps/files/osfstorage">VQA-RAD</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0</td>
      <td>National Library of Medicine, USA</td>
      <td>-</td>
      <td><a href="https://osf.io/89kps/files/osfstorage">[29]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/abachaa/VQA-Med-2019">ImageClef-2019-VQA-Med</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.1</td>
      <td>National Library of Medicine, USA</td>
      <td>-</td>
      <td><a href="https://github.com/abachaa/VQA-Med-2019">[30]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/allenai/medicat">MedICaT</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>106</td>
      <td>Allen Institute for AI</td>
      <td>-</td>
      <td><a href="https://github.com/allenai/medicat">[31]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://www.med-vqa.com/slake/">SLAKE</a></td>
      <td>图像-文本</td>
      <td>中文 英文</td>
      <td>0.2</td>
      <td>香港理工大学</td>
      <td>-</td>
      <td><a href="https://www.med-vqa.com/slake/">[32]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#tuberculosis-image-data-sets">Montgomery County CXR Set</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.5</td>
      <td>National Institutes of Health, USA</td>
      <td>-</td>
      <td><a href="https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#tuberculosis-image-data-sets">[33]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/MMMU/MMMU">MMMU</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.3</td>
      <td>IN.AI Research</td>
      <td>CC BY 4.0</td>
      <td><a href="https://huggingface.co/datasets/MMMU/MMMU">[34]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://weixionglin.github.io/PMC-CLIP/">PMC-OA</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>24.6</td>
      <td>上海交通大学</td>
      <td>-</td>
      <td><a href="https://weixionglin.github.io/PMC-CLIP/">[35]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://quilt1m.github.io/">Quilt-1M</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>36</td>
      <td>University of Washington</td>
      <td>-</td>
      <td><a href="https://quilt1m.github.io/">[36]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://zenodo.org/records/8333645">ROCOV2</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>6.4</td>
      <td>University of Applied Sciences and Arts Dortmund (FHDO)</td>
      <td>-</td>
      <td><a href="https://zenodo.org/records/8333645">[37]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://chaoyi-wu.github.io/RadFM/">RP3D-Caption</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>500</td>
      <td>上海交通大学</td>
      <td>-</td>
      <td><a href="https://chaoyi-wu.github.io/RadFM/">[38]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://huggingface.co/datasets/ibrahimhamamci/CT-RATE">CT-RATE</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>-</td>
      <td>University of Zurich</td>
      <td>CC BY-NC-SA 4.0</td>
      <td><a href="https://huggingface.co/datasets/ibrahimhamamci/CT-RATE">[39]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://pathvqachallenge.grand-challenge.org/">PathVQA</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>1.7</td>
      <td>University of California San Diego</td>
      <td>-</td>
      <td><a href="https://pathvqachallenge.grand-challenge.org/">[40]</a></td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://opendatalab.com/OpenDataLab/COUGHVID">COUGHVID</a></td>
      <td>语音-文本</td>
      <td>英文</td>
      <td>1.2</td>
      <td>EPFL</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/COUGHVID">[41]</a></td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>22. 体育</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MovieNet">MovieNet</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>161.8</td>
      <td>Chinese University of Hong Kong</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MovieNet">[42]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/VidSitu">VidSitu</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>50</td>
      <td>University of Southern California</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/VidSitu">[43]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Violin">Violin</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>16.6</td>
      <td>Carnegie Mellon University</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Violin">[44]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/M-VAD_Names">M-VAD Names</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>0.2</td>
      <td>University of Modena and Reggio Emilia</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/M-VAD_Names">[45]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MovieShots">MovieShots</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>17</td>
      <td>Chinese University of Hong Kong</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MovieShots">[46]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://github.com/m-bain/CondensedMovies">CMD</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>-</td>
      <td>University of Oxford</td>
      <td>CC BY 4.0</td>
      <td><a href="https://github.com/m-bain/CondensedMovies">[47]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/NES-MDB">NES-MDB</a></td>
      <td>语音-文本</td>
      <td>英文</td>
      <td>0.2</td>
      <td>UC San Diego</td>
      <td>MIT</td>
      <td><a href="https://opendatalab.com/OpenDataLab/NES-MDB">[48]</a></td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MagnaTagATune">MagnaTagATune</a></td>
      <td>语音-文本</td>
      <td>英文</td>
      <td>3.1</td>
      <td>CMU</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/MagnaTagATune">[49]</a></td>
    </tr>
    <tr>
      <td>24. 游戏</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Atari_2600_Video_Pinball">Atari 2600 Video Pinball</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>2.5</td>
      <td>University of Alberta</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Atari_2600_Video_Pinball">[50]</a></td>
    </tr>
    <tr>
      <td>24. 游戏</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Atari_Grand_Challenge">Atari Grand Challenge</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>24.9</td>
      <td>RWTH Aachen University</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Atari_Grand_Challenge">[51]</a></td>
    </tr>
    <tr>
      <td>25. 时政/政务/行政</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=21">DuVideoSenti</a></td>
      <td>图像-文本</td>
      <td>中文</td>
      <td>11.1</td>
      <td>百度</td>
      <td>-</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=21">[52]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CREMA-D">CREMA-D</a></td>
      <td>语音-文本</td>
      <td>英文</td>
      <td>7.5</td>
      <td>University of Pennsylvania</td>
      <td>DbCL 1.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/CREMA-D">[53]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EMOVIE">EMOVIE</a></td>
      <td>语音-文本</td>
      <td>中文</td>
      <td>0.6</td>
      <td>浙江大学</td>
      <td>CC BY-NC-SA 2.0</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EMOVIE">[54]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EmoFilm">EmoFilm</a></td>
      <td>语音-文本</td>
      <td>英文 意大利 西班牙</td>
      <td>-</td>
      <td>University of Augsburg</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/EmoFilm">[55]</a></td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Acted_Emotional_Speech_Dynamic_Database">AESDD</a></td>
      <td>语音-文本</td>
      <td>希腊语</td>
      <td>0.4</td>
      <td>Aristotle University of Thessaloniki</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://opendatalab.com/OpenDataLab/ESD">ESD</a></td>
      <td>语音-文本</td>
      <td>中文 英文</td>
      <td>2.3</td>
      <td>National University of Singapore</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/ESD">[56]</a></td>
    </tr>
    <tr>
      <td>27. 旅游/地理</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://opendatalab.com/OpenDataLab/YouCook2">YouCook2</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>70.2</td>
      <td>University of Michigan</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/YouCook2">[57]</a></td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://opendatalab.com/OpenDataLab/YouCook">YouCook</a></td>
      <td>视频-文本</td>
      <td>英文</td>
      <td>3.4</td>
      <td>SUNY at Buffalo</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/YouCook">[58]</a></td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td><a href="https://opendatalab.com/OpenDataLab/RecipeQA">RecipeQA</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>2.8</td>
      <td>Hacettepe University</td>
      <td>Custom</td>
      <td><a href="https://opendatalab.com/OpenDataLab/RecipeQA">[59]</a></td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0/tree/main?source=R2l0aHVi">WanJuan-Media News</a></td>
      <td>图像-文本</td>
      <td>中文</td>
      <td>118</td>
      <td>上海人工智能实验室</td>
      <td>CC BY 4.0</td>
      <td><a href="https://opendatalab.org.cn/OpenDataLab/WanJuan1_dot_0/tree/main?source=R2l0aHVi">[60]</a></td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Fakeddit">Fakeddit</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>0.4</td>
      <td>Laguna Blanca School</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Fakeddit">[61]</a></td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Cross-Modal_Comments_Dataset">Cross-Modal Comments</a></td>
      <td>图像-文本</td>
      <td>中文</td>
      <td>1.6</td>
      <td>北京大学</td>
      <td>-</td>
      <td><a href="https://opendatalab.com/OpenDataLab/Cross-Modal_Comments_Dataset">[62]</a></td>
    </tr>
    <tr>
      <td>30. 安全</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=51">MMChat</a></td>
      <td>图像-文本</td>
      <td>中文</td>
      <td>1.1</td>
      <td>阿里巴巴</td>
      <td>-</td>
      <td><a href="https://www.luge.ai/#/luge/dataDetail?id=51">[63]</a></td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://huggingface.co/datasets/zzliang/GRIT?row=18">GRIT</a></td>
      <td>图像-文本</td>
      <td>英文</td>
      <td>6.6</td>
      <td>Microsoft Research</td>
      <td>ms-pl</td>
      <td><a href="https://huggingface.co/datasets/zzliang/GRIT?row=18">[64]</a></td>
    </tr>
  <tbody>
</table>

👆 [<b>BACK to Table of Contents</b> -->](#目录)

## 开源行业大模型


<table border='1' class='dataframe'>
  <thead>
    <tr style='text-align: left;'>
      <th>Industry</th>
      <th>Model</th>
      <th>Language</th>
      <th>Multimodal</th>
      <th>Size</th>
      <th>Base Model</th>
      <th>Publisher</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1. 农林牧渔</td>
      <td><a href="https://github.com/AgriGPTs/AgriGPTs">AgriGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B, 13B</td>
      <td>ChatGLM2, Baichuan2</td>
      <td>哈尔滨工业大学</td>
    </tr>
    <tr>
      <td>2. 汽车</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>3. 采矿</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>4. 石油化工</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>5. 电力能源</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td><a href="https://github.com/PharMolix/OpenBioMed">OpenBioMed</a></td>
      <td>英文</td>
      <td>×</td>
      <td>7B, 10B</td>
      <td>LLaMA2</td>
      <td>水木分子</td>
    </tr>
    <tr>
      <td>6. 生物医药</td>
      <td><a href="https://github.com/DUTIR-BioNLP/Taiyi-LLM">Taiyi-LLM</a></td>
      <td>中文 英文</td>
      <td>×</td>
      <td>7B</td>
      <td>Qwen</td>
      <td>大连理工大学</td>
    </tr>
    <tr>
      <td>7. 航空航天</td>
      <td><a href="https://github.com/Yu-Yang-Li/StarWhisper">StarWhisper</a></td>
      <td>中文</td>
      <td>√</td>
      <td>14B</td>
      <td>-</td>
      <td>中国科学院大学</td>
    </tr>
    <tr>
      <td>8. 其他制造业</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>9. 计算机/通信</td>
      <td><a href="https://github.com/codefuse-ai/CodeFuse-DevOps-Model">DevOps-Model</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B, 14B</td>
      <td>Qwen</td>
      <td>蚂蚁集团</td>
    </tr>
    <tr>
      <td>10. 计算机编程</td>
      <td><a href="https://github.com/deepseek-ai/DeepSeek-Coder">Deepseek Coder</a></td>
      <td>中文 英文</td>
      <td>×</td>
      <td>1B, 5.7B, 6.7B, 33B</td>
      <td>预训练</td>
      <td>深度求索</td>
    </tr>
    <tr>
      <td>10. 计算机编程</td>
      <td><a href="https://github.com/WisdomShell/codeshell">CodeShell</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>预训练</td>
      <td>北京大学</td>
    </tr>
    <tr>
      <td>11. 人工智能</td>
      <td><a href="https://github.com/codefuse-ai/Test-Agent">TestGPT-7B</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>CodeLlama</td>
      <td>蚂蚁集团</td>
    </tr>
    <tr>
      <td>12. 其他信息服务</td>
      <td><a href="https://github.com/Alibaba-NLP/EcomGPT">EcomGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>bloomz</td>
      <td>阿里</td>
    </tr>
    <tr>
      <td>13. 房地产/建筑</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>14. 交通运输/邮政</td>
      <td><a href="https://github.com/DUOMO/TransGPT">致远-TransGPT</a></td>
      <td>中文</td>
      <td>√</td>
      <td>6B, 7B</td>
      <td>LLaMA, VisualGLM</td>
      <td>北京交通大学</td>
    </tr>
    <tr>
      <td>15. 水利/海洋</td>
      <td><a href="https://github.com/hkust-vgd/MarineGPT">MarineGPT</a></td>
      <td>英文</td>
      <td>√</td>
      <td>2B, 7B, 13B</td>
      <td>Vicuna V0, GEMMA</td>
      <td>香港科技大学</td>
    </tr>
    <tr>
      <td>15. 水利/海洋</td>
      <td><a href="https://huggingface.co/zjunlp">OceanGPT</a></td>
      <td>中文 英文</td>
      <td>×</td>
      <td>7B, 14B</td>
      <td>Qwen2, Qwen1.5</td>
      <td>浙江大学</td>
    </tr>
    <tr>
      <td>16. 数学</td>
      <td><a href="https://github.com/yongzhuo/chatglm-maths">chatglm-maths</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM</td>
      <td>yongzhuo</td>
    </tr>
    <tr>
      <td>16. 数学</td>
      <td><a href="https://github.com/THUDM/MathGLM">MathGLM</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B, 10B</td>
      <td>ChatGLM, ChatGLM2, GLM-zh</td>
      <td>THUDM</td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://github.com/blcuicall/taoli">Taoli</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>Chinese-LLaMA</td>
      <td>北京语言大学</td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://github.com/icalk-nlp/EduChat">EduChat</a></td>
      <td>中文</td>
      <td>×</td>
      <td>1.8B, 14B, 32B, 13B</td>
      <td>Baichuan, LLaMA, Qwen1.5</td>
      <td>华东师范大学</td>
    </tr>
    <tr>
      <td>17. 学科教育</td>
      <td><a href="https://github.com/zhihaiLLM/wisdomBot">智海-三乐</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>Qwen</td>
      <td>浙江大学</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://github.com/neukg/TechGPT">TechGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>LLaMA</td>
      <td>东北大学</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://github.com/gmftbyGMFTBY/science-llm">Mozi</a></td>
      <td>中文 英文</td>
      <td>×</td>
      <td>7B</td>
      <td>LLaMA, Baichuan</td>
      <td>北京理工大学</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://github.com/PKU-YuanGroup/Chat-UniVi">Chat-UniVi</a></td>
      <td>中文 英文</td>
      <td>√</td>
      <td>7B</td>
      <td>Vicuna-v1.5, CLIP ViT-L/14</td>
      <td>北京大学</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://github.com/tingxueronghua/ChartLlama-code">ChartLlama</a></td>
      <td>英文</td>
      <td>√</td>
      <td>13B</td>
      <td>LLaVA-1.5</td>
      <td>腾讯</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://github.com/rshaojimmy/JiuTian">九天</a></td>
      <td>英文</td>
      <td>√</td>
      <td>12B</td>
      <td>FlanT5-XXL, EVA-G</td>
      <td>哈尔滨工业大学</td>
    </tr>
    <tr>
      <td>18. 科技/科学研究</td>
      <td><a href="https://github.com/ZJU-M3/TableGPT-techreport">TabelGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>Phoenix</td>
      <td>浙江大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/xionghonglin/DoctorGLM">DoctorGLM</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM</td>
      <td>上海科技大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese">BenTsao</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>Huozi1.0, Bloom, Alpaca-Chinese, LLaMA</td>
      <td>哈尔滨工业大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/scutcyr/BianQue">BianQue</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ClueAI/ChatYuan-large-v2, ChatGLM, </td>
      <td>华南理工大学未来技术学院</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/FreedomIntelligence/HuatuoGPT">HuatuoGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B, 13B</td>
      <td>Baichuan, Ziya-LLaMA</td>
      <td>港中文深圳</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/SCIR-HI/Med-ChatGLM">Med-ChatGLM</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM</td>
      <td>哈尔滨工业大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/CMKRG/QiZhenGPT">QiZhenGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B, 7B, 13B</td>
      <td>ChatGLM, Chinese-LLaMA-Plus, CaMA</td>
      <td>浙江大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/michael-wzhu/ChatMed">ChatMed</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>LLaMA</td>
      <td>中国农业大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/michael-wzhu/ShenNong-TCM-LLM">ShenNong-TCM-LLM</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>LLaMA</td>
      <td>中国农业大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/WangRongsheng/XrayGLM">XrayGLM</a></td>
      <td>中文</td>
      <td>√</td>
      <td>6B</td>
      <td>VisualGLM</td>
      <td>澳门理工大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/shibing624/MedicalGPT">MedicalGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>8B, 13B</td>
      <td>Ziya-LLaMA, Baichuan, Llama3</td>
      <td>腾讯</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/thomas-yanxin/Sunsimiao">Sunsimiao</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>Baichuan</td>
      <td>华东理工大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/WangRongsheng/CareGPT">CareGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B, 13B, 14B, 20B</td>
      <td>LLaMA1/2, Baichuan1/2, Qwen, InternLM, </td>
      <td>澳门理工大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/FudanDISC/DISC-MedLLM">DISC-MedLLM</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B</td>
      <td>Baichuan</td>
      <td>复旦大学DISC</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/winninghealth/WiNGPT2">WiNGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B, 8B, 14B</td>
      <td>Qwen, Llama3</td>
      <td>卫宁健康人工智能实验室</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/synlp/ChiMed-GPT">ChiMed-GPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B</td>
      <td>Ziya2</td>
      <td>中国科学技术大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/XZhang97666/AlpaCare">AlpaCare</a></td>
      <td>英文</td>
      <td>×</td>
      <td>7B, 13B</td>
      <td>LLaMA, LLaMA2</td>
      <td>University of California, Santa Barbara</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/EmoCareAI/ChatPsychiatrist">ChatPsychiatrist</a></td>
      <td>英文</td>
      <td>×</td>
      <td>7B</td>
      <td>LLaMA</td>
      <td>香港大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/SupritYoung/Zhongjing">Zhongjing-LLaMA</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B</td>
      <td>Ziya-LLaMA</td>
      <td>郑州大学自然语言处理实验室</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/chaoyi-wu/PMC-LLaMA">PMC-LLaMA</a></td>
      <td>英文</td>
      <td>×</td>
      <td>7B, 8B, 13B</td>
      <td>LLaMA, LLaMA3</td>
      <td>上海交通大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/Kent0n-Li/ChatDoctor">ChatDoctor</a></td>
      <td>英文</td>
      <td>×</td>
      <td>7B</td>
      <td>LLaMA</td>
      <td>美国德克萨斯大学西南医学中心</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/189569400/MedicalGPT-zh">MING</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>bloomz</td>
      <td>上海交通大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/WangRongsheng/IvyGPT">IvyGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>33B</td>
      <td>LLaMA</td>
      <td>澳门理工大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/openmedlab/PULSE">PULSE</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B, 20B</td>
      <td>bloomz, InternLM</td>
      <td>OpenMEDLab</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/Zlasejd/HuangDI">HuangDI</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B</td>
      <td>Ziya-LLaMA</td>
      <td>南京大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/pariskang/CMLM-ZhongJing">ZhongJing</a></td>
      <td>中文</td>
      <td>×</td>
      <td>1.8B</td>
      <td>Qwen1.5</td>
      <td>复旦大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/2020MEAI/TCMLLM">TCMLLM</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM</td>
      <td>北京交通大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/scutcyr/SoulChat">SoulChat</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM</td>
      <td>华南理工大学未来技术学院</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/X-D-Lab/MindChat">MindChat</a></td>
      <td>中文</td>
      <td>×</td>
      <td>0.5B, 1.8B, 4B, 7B, 14B</td>
      <td>Qwen, Qwen2, InternLM2</td>
      <td>华东理工大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/SteveKGYang/MentalLLaMA">MentalLLaMA</a></td>
      <td>英文</td>
      <td>×</td>
      <td>7B, 13B, 33B</td>
      <td>LLaMA2, Vicuna</td>
      <td>National Centre for Text Mining</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/qiuhuachuan/smile">MeChat</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM2</td>
      <td>浙江大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/NEU-DataMining/PICA">PICA</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM2</td>
      <td>东北大学</td>
    </tr>
    <tr>
      <td>19. 医学/健康/心理</td>
      <td><a href="https://github.com/HIT-SCIR-SC/QiaoBan">QiaoBan</a></td>
      <td>中文</td>
      <td>-</td>
      <td>7B</td>
      <td>Baichuan</td>
      <td>哈尔滨工业大学</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/LiuHC0428/LAW-GPT">LawGPT_zh</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM</td>
      <td>上海交通大学</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/pengxiao-song/LaWGPT">LaWGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>Chinese-LLaMA, Chinese-alpaca-plus</td>
      <td>南京大学</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/CSHaitao/LexiLaw">LexiLaw</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM-6B</td>
      <td>清华大学</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/AndrewZhe/lawyer-llama">Lawyer LLaMA</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B</td>
      <td>Chinese-LLaMA,</td>
      <td>北京大学</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/siat-nlp/HanFei">HanFei</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>预训练</td>
      <td>中科院深圳先进院</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/PKU-YuanGroup/ChatLaw">ChatLaw</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B, 33B</td>
      <td>Ziya-LLaMA, Anima</td>
      <td>北京大学</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/davidpig/lychee_law">lychee_law</a></td>
      <td>中文</td>
      <td>×</td>
      <td>10B</td>
      <td>GLM</td>
      <td>南京大学</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/zhihaiLLM/wisdomInterrogatory">wisdomInterrogatory</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>Baichuan</td>
      <td>浙江大学</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/irlab-sdu/fuzi.mingcha">fuzi-mingcha</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM</td>
      <td>山东大学</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/FudanDISC/DISC-LawLLM">DISC-LawLLM</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B</td>
      <td>Baichuan</td>
      <td>复旦大学DISC</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/seudl/JurisLMs">JurisLMs</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B</td>
      <td>Chinese-LLaMA-Alpaca</td>
      <td>seudl</td>
    </tr>
    <tr>
      <td>20. 法律/司法</td>
      <td><a href="https://github.com/DUTIR-LegalIntelligence/Tailing">TaiLing</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>Qwen</td>
      <td>大连理工大学</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/jerry1993-tech/Cornucopia-LLaMA-Fin-Chinese">Cornucopia</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>LLaMA, Chinese-LLaMA</td>
      <td>中科院成都计算机应用研究所</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/ssymmetry/BBT-FinCUGE-Applications">BBT-FinCUGE-Applications</a></td>
      <td>中文</td>
      <td>×</td>
      <td>0.2B, 1B</td>
      <td>T5-v1.1</td>
      <td>复旦大学</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/Duxiaoman-DI/XuanYuan">XuanYuan</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B, 13B, 70B, 176B</td>
      <td>LLaMA2, bloom</td>
      <td>度小满</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/AI4Finance-Foundation/FinGPT">FinGPT</a></td>
      <td>英文</td>
      <td>×</td>
      <td>7B, 13B</td>
      <td>LLaMA2, falcon, bloom, mpt, ChatGLM, Qwen</td>
      <td>Columbia University</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/FudanDISC/DISC-FinLLM">DISC-FinLLM</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B</td>
      <td>Baichuan-13B-Chat</td>
      <td>复旦大学DISC</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://modelscope.cn/models/TongyiFinance/Tongyi-Finance-14B">Tongyi-Finance</a></td>
      <td>中文</td>
      <td>×</td>
      <td>14B</td>
      <td>Qwen-14B</td>
      <td>阿里云</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/AbaciNLP/InvestLM">InvestLM</a></td>
      <td>英文</td>
      <td>×</td>
      <td>65B</td>
      <td>LLaMA-65B</td>
      <td>香港科技大学</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/MetaGLM/FinGLM">FinGLM</a></td>
      <td>中文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM2-6B</td>
      <td>MetaGLM</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/ant-research/fin_domain_llm">WeaverBird</a></td>
      <td>中文 英文</td>
      <td>×</td>
      <td>6B</td>
      <td>ChatGLM2-6B</td>
      <td>蚂蚁集团</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/chancefocus/PIXIU">PIXIU</a></td>
      <td>英文</td>
      <td>×</td>
      <td>7B</td>
      <td>LLaMA-7B</td>
      <td>The Fin AI</td>
    </tr>
    <tr>
      <td>21. 金融/经济</td>
      <td><a href="https://github.com/TigerResearch/TigerBot">TigerBot</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B, 13B, 70B, 180B</td>
      <td>bloom, LLaMA2</td>
      <td>虎博科技</td>
    </tr>
    <tr>
      <td>22. 体育</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>23. 影视/娱乐</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>24. 游戏</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>25. 时政/政务/行政</td>
      <td><a href="https://github.com/wenge-research/YaYi">YaYi</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B, 13B, 30B</td>
      <td>LLaMA2</td>
      <td>中科闻歌</td>
    </tr>
    <tr>
      <td>26. 文学/情感</td>
      <td><a href="https://github.com/Xunzi-LLM-of-Chinese-classics/XunziALLM">Xunzi</a></td>
      <td>中文</td>
      <td>×</td>
      <td>4B, 6B, 7B, 14B</td>
      <td>Qwen, ChatGLM3, Xunzi-Qwen1.5, Baichuan2</td>
      <td>南京农业大学</td>
    </tr>
    <tr>
      <td>27. 旅游/地理</td>
      <td><a href="https://github.com/davendw49/k2">k2</a></td>
      <td>英文</td>
      <td>×</td>
      <td>7B</td>
      <td>LLaMA</td>
      <td>上海交通大学</td>
    </tr>
    <tr>
      <td>28. 住宿/餐饮/酒店</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>29. 新闻传媒</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>30. 网络安全</td>
      <td><a href="https://github.com/Clouditera/secgpt">SecGPT</a></td>
      <td>中文</td>
      <td>×</td>
      <td>13B</td>
      <td>Baichuan</td>
      <td>云起无垠</td>
    </tr>
    <tr>
      <td>30. 网络安全</td>
      <td><a href="https://github.com/ddzipp/AutoAudit">AutoAudit</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B</td>
      <td>Alpaca-Lora</td>
      <td>山东大学</td>
    </tr>
    <tr>
      <td>31. 其他</td>
      <td><a href="https://github.com/lyogavin/Anima">Anima</a></td>
      <td>中文</td>
      <td>×</td>
      <td>7B, 33B</td>
      <td>LLaMA2</td>
      <td>艾写科技</td>
    </tr>
  <tbody>
</table>

👆 [<b>BACK to Table of Contents</b> -->](#目录)


## 项目参与者

本项目由北京智源人工智能研究院大模型行业应用组发起和主导

项目主要贡献人员：赵璐璐，代永富，史晓峰，周华
