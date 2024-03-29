---
description: 您可以覆盖搜索查询结果的扩展。
solution: Target
title: 关于查询扩展优先
topic-legacy: Linguistics,Site search and merchandising
uuid: dfe18004-b8fd-4889-b01c-72a3b0c82b9c
exl-id: 6157ffcb-e696-419a-acb5-2076c12a6763
translation-type: tm+mt
source-git-commit: 7559f5f7437d46e3510d4659772308666425ec96
workflow-type: tm+mt
source-wordcount: '652'
ht-degree: 0%

---

# 关于查询扩展覆盖{#about-query-expansion-overrides}

您可以覆盖搜索查询结果的扩展。

## 使用查询扩展覆盖{#concept_6895B469B0E044299E93361BFA06B554}

配置查询扩展覆盖时，您将创建一组“规则”。 每个规则实质上都说，“在搜索时不要将`<this>`扩展到`<that>`中”，其中`<this>`是简单的文本词或短语，而`<that>`是文本词或短语或分类。

>[!NOTE]
>
>默认情况下，此功能未在Search&amp;Promote中启用。 请联系技术支持以激活该功能以供您使用。 启用“查询扩展覆盖”功能后，您必须在用户界面中“打开”它。

**查询扩展覆盖的工作方式**

当在“查询扩展覆盖添加”页中指定了“文本”和“术语”值时，代码将对特定对进行操作。 当将分类类型指定为术语(如字典或备用单词Forms)时，“不扩展”值不会转换为由指示的分类创建的任何形式。

例如，假设您有以下定义：

`Do Not Expand = "dog"`

`Type = Text`

`Term = "dogs"`

搜索“狗”的查询将不包括“狗”。

但是，如果定义如下：

`Do Not Expand = "dog"`

`Type = Alternate Word Forms`

查询不包括“狗”或“狗”(“狗”的替代词Forms)。

您可以指定多个术语、多个分类或同时指定两者。 但是，如果选择“全部”作为“类型”，则任何多词列表都将折叠为单个“全部”条目。

如果文本条目和分类条目在任何规则中混合，则在用户界面中重新组织它们以首先显示文本值。 但是，这并不暗示或影响在搜索时的评估顺序。

文本术语经过验证以删除无意义的引用。 即，将术语与“不扩展”值进行比较，如果存在匹配项，则删除该术语。 此外，重复术语值（文本或分类）也会被删除。

如果在复制早期定义时添加了具有“不扩展”值的新规则，则新定义的“条款”将添加到原始定义中。

## 配置查询扩展覆盖{#task_A087354A509D4997BA275186C224160E}

在Search&amp;Promote中定义和添加查询扩展覆盖。

<!-- 

t_configuring_query_expansion_overrides.xml

 -->

>[!NOTE]
默认情况下，此功能未在Search&amp;Promote中启用。 请联系技术支持以激活该功能以供您使用。 启用“查询扩展覆盖”功能后，您必须在用户界面中“打开”它。 下面的前几步概括了如何做到这一点。

**配置查询扩展覆盖**

1. 在Search&amp;Promote中，单击&#x200B;**设置** > **用户** > **视图角色**。
1. 在“视图角色”页的表的“操作”列中，单击“语言学”菜单上要授予其访问查询扩展覆盖权限的角色右侧的&#x200B;**编辑**。
1. 在“编辑角色”页面上，展开“语言学”树。
1. 选中&#x200B;**查询扩展覆盖**，然后单击&#x200B;**保存更改**。
1. 单击&#x200B;**语言** > **查询扩展覆盖**。
1. 单击&#x200B;**添加查询扩展覆盖**。
1. 在“查询扩展覆盖添加”页中，设置所需的选项。

   <!-- 
   
   r_query_expansion_override_definitions.xml
   
   -->

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>选项 </p> </th> 
      <th colname="col2" class="entry"> <p>描述 </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>不扩展 </p> </td> 
      <td colname="col2"> <p>指定您不希望展开的单词或短语。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>类型 </p> </td> 
      <td colname="col2"> <p>选择<b>文本</b>以指定特定单词或短语配对。 或者，选择一个分类以指定“不扩展”字词或短语不会通过所选分类进行转换。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>术语 </p> </td> 
      <td colname="col2"> <p>仅当您选择<b>Text</b>作为Type时可用。 指定要从搜索扩展中排除的单词或短语。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>操作 </p> </td> 
      <td colname="col2"> <p> 单击<b>+</b>或<b>-</b>可分别向定义中添加或删除术语。 </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. 完成后，单击&#x200B;**添加**。

   在“查询扩展覆盖定义”页中，您可以编辑或删除已添加的定义。
1. 要预览添加的结果，请单击蓝框中的&#x200B;**重新生成分阶段站点索引**&#x200B;以快速重建分阶段网站索引。
1. （可选）执行下列操作之一：

   * 单击&#x200B;**Live**。

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)

   * 单击&#x200B;**实时推送**。

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)
