---
description: 您可以使用“重新生成索引”来更新网站的索引，而无需重新爬网站。
solution: Target
subtopic: Regenerate Index
title: 关于重新生成索引
topic-legacy: Index,Site search and merchandising
uuid: 9d1f1d88-0453-4422-a625-a348febbf224
exl-id: 4155a52c-33f6-4f54-b69b-2a092530f7aa
translation-type: tm+mt
source-git-commit: 7559f5f7437d46e3510d4659772308666425ec96
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 1%

---

# 关于重新生成索引{#about-regenerate-index}

您可以使用[!DNL Regenerate Index]更新网站的索引，无需重新爬网站。

## 使用重新生成索引{#concept_6CBE6B8D18EF47D293091CBA542245FA}

只要您更改了以下帐户选项，就可以使用此选项：

* 文字和语言
* 排除的单词
* 同义词
* 元数据设置，例如删除元数据字段时，更改字段名称、数据类型、日期格式、排序顺序、最小或最大排名值、默认排名值、列表类型或列表分隔符。

更新的帐户选项信息用于生成新的站点索引。 通过“重新生成”，您可以快速、高效地更改网站索引。

默认情况下，索引中不包括任何新网站内容或更改的网站内容。 要包含此类内容，请运行完整或增量索引。

另请参阅[运行实时或分阶段网站的完整索引……](../c-about-index-menu/c-about-full-index.md#task_F7FE04D8A1654A7787FCCA31B45EB42D)。

另请参阅[运行实时网站或分阶段网站的增量索引……](../c-about-index-menu/c-about-incremental-index.md#task_9BFB6157F3884B2FAECB7E0E9CA318CB)。

## 重新生成实时或分阶段网站{#task_B28DE40C0E9A475ABCBCBC4FF993AACD}的索引

您可以使用[!DNL Regenerate Index]更新网站的索引，而无需重新整理网站。

**要重新生成实时网站或分阶段网站的索引，请执行以下操作**

1. 在“产品”菜单中，执行下列操作之一：

   * 单击 **[!UICONTROL Index]** > **[!UICONTROL Regenerate Index]** > **[!UICONTROL Live Regenerate]**.

   * 单击 **[!UICONTROL Index]** > **[!UICONTROL Regenerate Index]** > **[!UICONTROL Staged Regenerate]**.

1. 在[!DNL Regenerate]页面上，单击&#x200B;**[!UICONTROL Regenerate Index Now]**。
1. （可选）执行下列任一操作：

   * 如果选择运行&#x200B;**[!UICONTROL Live Regenerate]**，请单击&#x200B;**[!UICONTROL View Last Crawl]**&#x200B;查看上次执行的实时索引再生的性能统计信息。

   * 索引再生时，单击&#x200B;**[!UICONTROL Stop Regenerate Now]**&#x200B;以停止索引再生过程。
   * 在重新生成索引时，单击&#x200B;**[!UICONTROL Restart Regenerate Now]**&#x200B;从头开始重新开始索引重新生成过程。
   * 如果在分阶段重新生成后出现索引错误，请单击&#x200B;**[!UICONTROL View Errors]**&#x200B;以视图关联的日志。

## 查看实时或分阶段网站{#task_61CE8F9E7BF84BA89A8D482B2106BB15}的已重新生成索引日志

当实时索引重新生成或分阶段索引重新生成完成时，您可以视图其关联日志以排除发生的任何错误。

您无法导出日志，也无法保存它们。 但是，在新索引出现之前，日志仍可供查看。

**视图实时网站或分阶段网站的重新生成索引日志**

1. 在“产品”菜单中，执行下列操作之一：

   * 单击 **[!UICONTROL Index]** > **[!UICONTROL Regenerate Index]** > **[!UICONTROL Live Log]**.

   * 单击 **[!UICONTROL Index]** > **[!UICONTROL Regenerate Index]** > **[!UICONTROL Staged Log]**.

1. 在日志页面顶部或底部，执行下列任一操作：

   * 使用导航选项&#x200B;**[!UICONTROL First]**、**[!UICONTROL Prev]**、**[!UICONTROL Next]**、**[!UICONTROL Last]**&#x200B;或&#x200B;**[!UICONTROL Go to line]**&#x200B;在日志中移动。

   * 使用显示选项&#x200B;**[!UICONTROL Errors only]**、**[!UICONTROL Wrap line]**&#x200B;或&#x200B;**[!UICONTROL Show]**&#x200B;细化您所看到的内容。
