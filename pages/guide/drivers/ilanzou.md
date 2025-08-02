---
title:
  en: iLanZou
  zh-CN: 蓝奏云优享版
icon: iconfont icon-state
# This control sidebar order
top: 380
# A page can have multiple categories
categories:
  - guide
  - drivers
# A page can have multiple tags
tag:
  - Storage
  - Guide
  - '302'
# this page is sticky in article list
sticky: true
# this page will appear in starred articles
star: true
---

**https://ilanzou.com**

<!--@include: @/snippets/reverse-tip.md-->

## Root folder ID { lang="en" }

## 根文件夹ID { lang="zh-CN" }

::: en
root folder ID the default is `0`，Other directory ID View the figure below obtaining method
![LanZoufolder_id](/img/drivers/lanzou/ilanzou_folder.png)
:::
::: zh-CN
根目录ID，默认为`0`，其它目录ID查看下图获取方式
![LanZoufolder_id](/img/drivers/lanzou/ilanzou_folder.png)
:::

## username、password { lang="en" }

## 账户、密码 { lang="zh-CN" }

::: en
Just fill in your own NewLanzou Cloud Account Password
:::
::: zh-CN
填写自己的蓝奏云优享版帐号密码
:::

### The default download method used { lang="en" }

### 默认使用的下载方式 { lang="zh-CN" }

::: en

```mermaid
---
title: Which download method is used by default?
---
flowchart TB
    style a1 fill:#bbf,stroke:#f66,stroke-width:2px,color:#fff
    style a2 fill:#ff7575,stroke:#333,stroke-width:4px
    subgraph ide1 [ ]
    a1
    end
    a1[302]:::someclass====|default|a2[user equipment]
    classDef someclass fill:#f96
    c1[local proxy]-.alternative.->a2[user equipment]
    b1[Download proxy URL]-.alternative.->a2[user equipment]
    click a1 "../drivers/common.html#webdav-policy"
    click b1 "../drivers/common.html#webdav-policy"
    click c1 "../drivers/common.html#webdav-policy"
```

:::
::: zh-CN

```mermaid
---
title: 默认使用的哪种下载方式？
---
flowchart TB
    style a1 fill:#bbf,stroke:#f66,stroke-width:2px,color:#fff
    style a2 fill:#ff7575,stroke:#333,stroke-width:4px
    subgraph ide1 [ ]
    a1
    end
    a1[302]:::someclass====|默认|a2[用户设备]
    classDef someclass fill:#f96
    c1[本机代理]-.备选.->a2[用户设备]
    b1[代理URL]-.备选.->a2[用户设备]
    click a1 "../drivers/common.html#webdav-策略"
    click b1 "../drivers/common.html#webdav-策略"
    click c1 "../drivers/common.html#webdav-策略"
```

:::
