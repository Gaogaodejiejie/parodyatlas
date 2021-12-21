# parodyatlas
这是生物信息学1801实训作业
* **甲方**: 胡德华
* **乙方**: 杨子奕｜黄海盛｜李阿鹏｜张彦哲｜巫肇曦｜郑思悦
## 甲方要求(无书面要求，描述不全)
* 仿制[ProteinAtlas](https://www.proteinatlas.org/)
* 使用TCGA(tumer arrays)、GEO(mt-DNA/RNA)、proteomics，并整合
* 能器官水平显示各类组学数据
* 拥有非常炫酷的数据可视化和交互功能，包含搜索功能
## 甲方设计工作流
* 要求**2021.11.14**前给出设计方案(未落实)
* 要求自**2021.11.08**日起，到**2022.01.23**结束，期间每日**08:00-17:00**待在后栋219进行开发工作(未落实)
* 要求**2022.01.23**前完成肝癌或者小细胞癌的案例，具体甲方未阐释
* 要求19级继续开发其他disease
## 乙方设计思路
### page草图  
![design](design/QQ20211221-0.png)
### 类关系图
```mermaid
{
    class待添加{
        pass
    }
}
```

### 前端框架
设计`杨子亦`  
```html
{
    Home:search
    Members
    xxxx cancer page
    Instructions
}
```
分工：`巫肇曦`,`黄海盛`
### GEO/TCGA组学数据集结构
`data.json`文件相关说明  
```js
{
    "name":"GEO",
    "params":{
        ...
    }
}
```
search word->spyder->parser->`.json`  
分工：`张彦哲`  

## 巧妇难为无米之炊
* 假后台：预爬去数据（代表性数据集） 
* 静态前端  
## 定位人群
入门xxx癌症的研究生新生  
## 功能
1. 整合不同组学数据链接合集  
2. 代表类型(citation高)的数据的概览: 火山图(`郑思悦`)  