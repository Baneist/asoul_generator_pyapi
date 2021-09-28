# asoul_generator_pyapi
鼠鼠们的小作文生成器 整合自https://github.com/infinityedge01/ASOUL-Generator-Backend
### 下载模型
https://disk.pku.edu.cn/#/link/88F0D3C9839329210503C7E50634AAFE

需要将文件夹内的两个文件(pytorch_model.bin 和 config.json) 放入 asoul_cpm 文件夹下。
### 安装依赖
``` powershell
pip install -r requirements.txt
```
### 食用方法
from asoulgenerator import asoulgenerate

prefix,generated = asoulgenerate.process(str)
