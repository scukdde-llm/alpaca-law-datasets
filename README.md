# Alpaca-LAW-Datasets
使用 CovScript 将原始的 CrimeKgAssitantCleaned 转换成通用性更强的 Alpaca 格式

HuggingFace Hub: https://huggingface.co/datasets/scu-kdde/alpaca-law
## Setup
请先[安装 CovScript](https://unicov.cn/covscript/) 
```bash
cspkg -i ecs_bootstrap --yes
```
## Run
```bash
cd CrimeKgAssitant
ecs gen_alpaca.ecs
```
## Citations
```
@misc{LAWGPT-zh,
  author={Hongcheng Liu, Yusheng Liao, Yutong Meng, Yuhao Wang},
  title = {LawGPT：中文法律对话语言模型},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/LiuHC0428/LAW_GPT}},
}
@misc{CrimeKgAssitant,
  author={HUanyong Liu},
  title = {CrimeKgAssitant：罪名法务智能项目},
  year = {2018},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/liuhuanyong/CrimeKgAssitant}},
}
@misc{CovScript,
  author={Dengchun Li},
  title = {CovScript 编程语言},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/covscript/covscript}},
}
```
