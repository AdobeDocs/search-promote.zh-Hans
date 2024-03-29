---
description: 使用“搜索”菜单设置排除的单词、集合、限制、预览和框架。
solution: Target
subtopic: Searching
title: 关于搜索菜单
topic-legacy: Settings,Site search and merchandising
uuid: 072111fc-a32b-4acb-8337-cb21bcdb5542
exl-id: 4cb70240-051b-4bf3-ae2a-b151acc7cba1
translation-type: tm+mt
source-git-commit: 7559f5f7437d46e3510d4659772308666425ec96
workflow-type: tm+mt
source-wordcount: '11165'
ht-degree: 1%

---

# 关于“搜索”菜单{#about-the-searching-menu}

使用“搜索”菜单设置排除的单词、集合、限制、预览和框架。

## 关于搜索{#concept_207105CF26B1448F8A3D223787C56AB8}

您可以使用“搜索”来定义和自定义您的演示文稿模板可以引用的命名搜索。

<!-- 

c_about_searches.xml

 -->

在演示文稿模板中，您可以引用在“搜索”模块中定义的任何已命名搜索。 这反过来又可让您轻松自定义为一组给定模板执行的搜索类型。

要从搜索结果中排除常用短语和常用词，请参阅[配置被排除词](../c-about-linguistics-menu/c-about-excluded-words.md#task_60BF6BB7A66C48479D2BBB32C0F38CDE)。

要定义网站的特定可搜索区域，请参阅[添加集合](../c-about-settings-menu/c-about-searching-menu.md#task_07732D0F00104E59AD421297A704B2F6)。

要为搜索结果链接指定目标帧，请参阅[将帧与表单一起使用](../c-appendices/c-searchforms.md#reference_82CDDDA1E37042E4849EBF7EA05407C5)。

要限制基于HTTP推荐人、IP地址或请求方案（HTTP或HTTPS）的搜索，请参阅在预览](../c-about-settings-menu/c-about-searching-menu.md#task_CE267A0FF621474E80AB43B67B1C28D7)中设置值。[

## 搜索提示{#section_22F0E2BCF259459FA5F49FBCC0F09A7C}

要获取更具体的搜索结果，可使用以下搜索提示。

<table> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>搜索提示 </p> </th> 
   <th colname="col2" class="entry"> <p>描述 </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>检查拼写 </p> </td> 
   <td colname="col2"> <p>确保搜索词拼写正确。 如果在<span class="uicontrol">语言学</span> &gt; <span class="uicontrol">词语和语言</span>中启用<span class="uicontrol">相似音效匹配</span>，则搜索引擎将尝试查找与搜索词发音相似的词。 但是，最好始终尝试正确拼写搜索词。 </p> <p>请参阅<a href="../c-about-linguistics-menu/c-about-words-and-language.md#concept_CEB4B9576F3C4E2EB87B352EEC738D79" type="concept" format="dita" scope="local">关于单词和语言</a>。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用多个词 </p> </td> 
   <td colname="col2"> <p>示例: 
     <code>
       our free product 
     </code> </p> <p>与单词查询相比，多字查询可返回更精美的结果。 </p> <p>例如， 
     与仅 
     <code>
       product 
     </code>。<code>
       our free product 
     </code> </p> <p>请记住，即使相关结果不包含所有查询词，也会返回相关结果。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用类似词 </p> </td> 
   <td colname="col2"> <p>示例: 
     <code>
       safe secure privacy security 
     </code> </p> <p>在搜索查询中使用的词语越相似，搜索结果就越相关。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用适当的大写 </p> </td> 
   <td colname="col2"> <p>示例: 
     <code>
       Search Template Reference 
     </code> </p> <p>大写专有名词。 如果使用小写字，则搜索引擎将匹配该字的任何大小写。 </p> <p>例如，如果您键入 
     <code>
       search 
     </code>，搜索引擎将返回包含“search”、“Search”和“SEARCH”等词的所有文档。 但是，如果您键入 
     <code>
       Search 
     </code>，搜索引擎返回只包含大写字词的文档。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用引号 </p> </td> 
   <td colname="col2"> <p>示例: 
     <code>
       "our pledge to you" 
     </code> </p> <p>使用引号查找必须彼此相邻的词，如"我们向你保证"。 如果没有引号，搜索结果中将包含“our”、“pretit”、“to”和“you”等词，但不一定按顺序排列。 相反，这些词可能以任意顺序出现在文档中。 </p> <p> 如果您正在使用“高级搜索表单”，其中<span class="uicontrol">任意</span>、<span class="uicontrol">所有</span>和<span class="uicontrol">短语</span>的单选按钮，则只有在选择<span class="uicontrol">任意</span>时才能使用引号。 如果选择了<span class="uicontrol">所有</span>或<span class="uicontrol">短语</span>，则忽略引号。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用+（加号）或 — （减号） </p> </td> 
   <td colname="col2"> <p>示例: 
     <code>
       +"template language" 
     </code> </p> <p>使用+可指示搜索词或短语必须显示在搜索结果中。 </p> <p>使用 — 指示搜索词或短语必须在搜索结果中缺失。 </p> <p>您必须在引号中包含短语。 如上例所示，加号或减号与搜索词之间不留空格。 </p> <p> 如果您正在使用“高级搜索表单”，其中<span class="uicontrol">任意</span>、<span class="uicontrol">所有</span>和<span class="uicontrol">短语</span>的单选按钮，则只有在选择<span class="uicontrol">任意</span>时才能使用引号。 如果选择了</span>或<span class="uicontrol">短语</span>，则忽略加号和减号修饰符。<span class="uicontrol"> </span></p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用字段搜索 </p> </td> 
   <td colname="col2"> <p>示例： </p> <p> 
     <ul id="ul_F7CFF7652894402E8D19D6BA49792530"> 
      <li id="li_27492EF933C5437CB2C499746EC8CF39"> 
       <code>
         title:about 
       </code> </li> 
      <li id="li_BD21505122104FD0B16A4DAD777811DA"> 
       <code>
         desc:"Our Team" 
       </code> </li> 
      <li id="li_8264630F8B3D46BF872EFEB1D69DB6BE"> 
       <code>
         keys:login 
       </code> </li> 
      <li id="li_EBB81CBFC6DA45E99A524890DCD56E9F"> 
       <code>
         body:security 
       </code> </li> 
      <li id="li_6A852E35D6984A2C94144AB6C6D2DFA0"> 
       <code>
         alt:"join now" 
       </code> </li> 
      <li id="li_F4C5699360484D12ACD62BBFB84A7904"> 
       <code>
         url:help 
       </code> </li> 
      <li id="li_B2DBBA2239E74D98868D92B3EDEF5B51"> 
       <code>
         target:Adobe 
       </code> </li> 
     </ul> </p> <p>字段搜索允许您针对在文档的特定部分中显示的词创建特定搜索。 </p> <p>您可以对正文文本(body:)、标题文本(title:)、替代文本(alt:)、元描述(desc:)、元关键字(keys:)、URL(url:)或元目标关键字(目标:)执行字段搜索。 对字段名称使用小写，后跟冒号。 冒号和搜索词之间没有空格。 </p> <p>字段搜索后面只有一个词或短语。 词组必须包含在引号中。 </p> <p>如果您正在使用带有字段名称列表框的高级搜索表单，则只能在<span class="uicontrol">任何</span>被选中时，在单词或短语前输入字段名称。 如果在列表框中选择了任何其他高级搜索表单字段，则忽略特定字段名称。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用通配符 </p> </td> 
   <td colname="col2"> <p>示例： </p> <p> 
     <ul id="ul_D8E3867EB15641B0A6E55AD546CCB4DD"> 
      <li id="li_CB8B8FC15EB14B13BB33BB69F5206303"> 
       <code>
         wh* 
       </code> </li> 
      <li id="li_5350A934648C4C81BD6C0875061B426B"> 
       <code>
         "wh* are" 
       </code> </li> 
      <li id="li_7965A2F7186F40039D2F0736299D11B1"> 
       <code>
         415-*-* 
       </code> </li> 
     </ul> </p> <p>通配符搜索会扩展特定请求的匹配数。 *字符用作通配符。 </p> <p>例如，搜索 
     <code>
       wh* 
     </code>会找到“what”、“why”、“when”、“whever”和与“wh”开始的任何其他单词。 搜索*her*时，会发现“here”、“where”、“where”、“toghere”、“gathering”以及任何在单词中任何位置包含“her”的其他单词。 </p> <p>您可以将通配符与+和 — 修饰符、短语的引号以及字段搜索说明符组合。 </p> <p>搜索 
     <code>
       +wh* -se*ch 
     </code>会查找所有页面，其中包含一个词，该词用“wh”开始，且不包含一个词，该词用“se”开始，以“ch”结尾。 </p> <p>搜索 
     <code>
       "wh* are" 
     </code>查找短语“where are”、“what are”、“why are”等。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 添加新的搜索定义{#task_98D3A168AB5D4F30A1ADB6E0D48AB648}

您可以使用[!DNL GS Add Search]面板在表示层中为“向导式搜索”组件（如facet、痕迹导航、页面导航、菜单和最近的搜索）配置和添加新的搜索定义。

<!-- 

t_adding_a_new_definition.xml

 -->

添加新搜索定义后，请确保在演示文稿模板中引用该定义，以便显示该定义。

请参阅[关于模板](../c-about-design-menu/c-about-templates.md#concept_06EB481B14864E18A8AE2BCD1D6EF0B5)。

**添加新搜索定义**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Searches]**。
1. 在[!DNL Searches]页面上，单击&#x200B;**[!UICONTROL Add New Search]**。
1. 在&#x200B;**[!UICONTROL GS Add Search]**&#x200B;页面上，设置所需的选项。

   <!-- 
   
   r_gs_search_options.xml
   
   -->

   请注意，选择演示文稿模板的处理规则可以覆盖其中一些选项。

   请参阅[添加新的搜索定义](../c-about-settings-menu/c-about-searching-menu.md#task_98D3A168AB5D4F30A1ADB6E0D48AB648)或[编辑搜索定义](../c-about-settings-menu/c-about-searching-menu.md#task_AF1FFB1AEF874C13AB359C28F74BF461)。

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>选项 </p> </th> 
      <th colname="col2" class="entry"> <p>描述 </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>搜索名称 </p> </td> 
      <td colname="col2"> <p>标识定义的搜索的名称。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>来源 </p> </td> 
      <td colname="col2"> <p>允许您选择要使用的后端搜索。 您可以从<span class="wintitle"> SiteSearch </span>或<span class="wintitle"> Merchandising </span>中进行选择。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>帐户 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源时，此选项才可用。 </p> <p>允许您选择要搜索的网站搜索/促销帐户。 通常，搜索会在您当前使用的帐户中搜索。 但是，您的演示文稿模板可以对任何其他帐户使用后端搜索。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>服务器名/IP </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">促销</span>作为源时，此选项才可用。 </p> <p>指定<span class="wintitle">促销</span>搜索应访问的<span class="wintitle">促销</span>服务器的全名。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>服务器端口 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">促销</span>作为源时，此选项才可用。 </p> <p>指定<span class="wintitle">促销</span>服务器端口号。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>金字塔 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">促销</span>作为源时，此选项才可用。 </p> <p>指定<span class="wintitle">促销</span>服务器中的金字塔。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>结果数 </p> </td> 
      <td colname="col2"> <p>指定要返回的搜索结果数。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>首页结果数（如果不同） </p> </td> 
      <td colname="col2"> <p>指定在第一页返回的结果数。 如果需要使此选项与其他页面不同，请使用此选项。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>列数 </p> </td> 
      <td colname="col2"> <p>指定将搜索结果拆分到的列数。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>搜索类型 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源时，此选项才可用。 </p> <p>允许您从以下三种类型的搜索中进行选择。 </p> <p> 
        <ul id="ul_2F6FA9EFD8DB49EEAB866C3D070E2644"> 
          <li id="li_ECFEBEDD86FF4DE2BB768423B3B91B5E"> <span class="uicontrol"> 全部 </span> <p>搜索包含查询字符串中所有单词的文档。 </p> <p>在禁用搜索词并忽略这些字符之前，使用"+"和"-"。 </p> </li> 
          <li id="li_62EB215BDDE74DF0BF76B3BD5B96776F"> <span class="uicontrol"> 任何 </span> <p>允许使用"+"和"-"字前缀。 </p> </li> 
          <li id="li_3D71982C0BBA41AFA353069AF3F2F6D8"> <span class="uicontrol"> 短语  </span> <p>查询字符串被视为带引号的短语，所有用户类型的引号都会被忽略。 </p> <p>在禁用搜索词并忽略这些字符之前，使用"+"和"-"。 </p> </li> 
        </ul> </p> <p> 如果希望查询中的每个单词都可能选择facet值，则主搜索应始终使用<span class="uicontrol">所有</span>。 </p> <p>您可以查看有关在搜索查询中使用+和 — 修饰符的搜索提示。 </p> <p>请参阅<a href="../c-about-settings-menu/c-about-searching-menu.md#concept_207105CF26B1448F8A3D223787C56AB8" type="concept" format="dita" scope="local">关于搜索</a>。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>收藏集 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源时，此选项才可用。 </p> <p>标识索引中要搜索的集合。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Promosearch </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源时，此选项才可用。 </p> <p>允许您根据您指定的<span class="uicontrol">结果数</span>使用搜索结果中的随机选择。 </p> <p>Promosearch是一个旧概念。 因此，我们建议您在网站搜索/促销中使用新的横幅管理系统。 </p> <p>请参阅<a href="../c-about-design-menu/c-about-banners.md#concept_5BBE01FEC6134393B43CC917C8CC64DA" type="concept" format="dita" scope="local">关于横幅</a>。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>应用彩块化参数 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源，并且选择了<span class="uicontrol"> Promosearch </span>时，此选项才可用。 </p> <p>指定促销搜索使用选定的彩块化来缩小促销范围。 大多数促销搜索帐户不使用此选项。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>如果没有匹配的促销，请提供默认促销 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源，并且选择了<span class="uicontrol"> Promosearch </span>时，此选项才可用。 </p> <p>指定如果促销的初始搜索未找到任何内容，则进行促销的另一次搜索。 第二次搜索促销时会删除关键字。 相反，它会查找任何将“is_default”元数据字段设置为“yes”的促销。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>高亮搜索 </p> </td> 
      <td colname="col2"> <p>从主搜索中提取要在“hero-zone”中突出显示的选定数量的结果。 </p> <p>通常，高亮搜索具有与主搜索相似的搜索标准，但使用不同的排名机制来高亮显示某些结果。 软件将从主搜索中删除重复。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>基本搜索 </p> </td> 
      <td colname="col2"> <p>仅当您选择了<span class="uicontrol">高亮搜索</span>时，此选项才可用。 </p> <p>允许您选择包含突出显示结果的结果的搜索。 重复将从此搜索中删除。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>重复数据消除优先级 </p> </td> 
      <td colname="col2"> <p>仅当您选择了<span class="uicontrol">高亮搜索</span>时，此选项才可用。 </p> <p>允许您进行多次高亮搜索。 </p> <p>当您有多个高亮搜索时，您需要指定重复数据消除的优先级，其中“1”是最高优先级。 </p> <p>例如，假设您有两个高亮搜索：畅销书和新产品。 理论上是。 卖得最好的也是新产品。 在这种情况下，您希望从新产品和主搜索中删除重复。 因此，您将畅销书的优先级设置为1，将新产品的优先级设置为2。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>参数 </p> </td> 
      <td colname="col2"> <p>允许您向搜索中添加CGI参数。 </p> <p>请参阅<a scope="local" href="../c-appendices/c-cgiparameters.md#reference_582E85C3886740C98FE88CA9DF7918E8" type="reference" format="dita">后端搜索CGI参数</a>。 </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. 单击 **[!UICONTROL Add]**.
1. （可选）在[!DNL Searches]页面上，执行下列任一操作：

   * 单击&#x200B;**[!UICONTROL History]**&#x200B;可还原您所做的任何更改。

      请参阅[使用历史记录选项](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)。

   * 单击 **[!UICONTROL Live]**.

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)。

   * 单击 **[!UICONTROL Push Live]**.

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)。

## 编辑搜索定义{#task_AF1FFB1AEF874C13AB359C28F74BF461}

您可以使用[!DNL Staged GS Edit Search]面板重新配置“向导式搜索”表示层的现有搜索定义。

<!-- 

t_editing_a_search_definition.xml

 -->

编辑搜索定义后，请确保在演示文稿模板中已引用该定义，以便显示该定义。

请参阅[关于模板](../c-about-design-menu/c-about-templates.md#concept_06EB481B14864E18A8AE2BCD1D6EF0B5)。

**编辑搜索定义**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Searches]**。
1. 在[!DNL Searches]页面的表格中，单击要更改的定义行中的&#x200B;**[!UICONTROL Edit]**。
1. 在&#x200B;**[!UICONTROL GS Edit Search]**&#x200B;页面上，设置所需的选项。

   <!-- 
   
   r_gs_search_options.xml
   
   -->

   请注意，选择演示文稿模板的处理规则可以覆盖其中一些选项。

   请参阅[添加新的搜索定义](../c-about-settings-menu/c-about-searching-menu.md#task_98D3A168AB5D4F30A1ADB6E0D48AB648)或[编辑搜索定义](../c-about-settings-menu/c-about-searching-menu.md#task_AF1FFB1AEF874C13AB359C28F74BF461)。

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>选项 </p> </th> 
      <th colname="col2" class="entry"> <p>描述 </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>搜索名称 </p> </td> 
      <td colname="col2"> <p>标识定义的搜索的名称。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>来源 </p> </td> 
      <td colname="col2"> <p>允许您选择要使用的后端搜索。 您可以从<span class="wintitle"> SiteSearch </span>或<span class="wintitle"> Merchandising </span>中进行选择。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>帐户 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源时，此选项才可用。 </p> <p>允许您选择要搜索的网站搜索/促销帐户。 通常，搜索会在您当前使用的帐户中搜索。 但是，您的演示文稿模板可以对任何其他帐户使用后端搜索。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>服务器名/IP </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">促销</span>作为源时，此选项才可用。 </p> <p>指定<span class="wintitle">促销</span>搜索应访问的<span class="wintitle">促销</span>服务器的全名。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>服务器端口 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">促销</span>作为源时，此选项才可用。 </p> <p>指定<span class="wintitle">促销</span>服务器端口号。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>金字塔 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">促销</span>作为源时，此选项才可用。 </p> <p>指定<span class="wintitle">促销</span>服务器中的金字塔。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>结果数 </p> </td> 
      <td colname="col2"> <p>指定要返回的搜索结果数。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>首页结果数（如果不同） </p> </td> 
      <td colname="col2"> <p>指定在第一页返回的结果数。 如果需要使此选项与其他页面不同，请使用此选项。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>列数 </p> </td> 
      <td colname="col2"> <p>指定将搜索结果拆分到的列数。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>搜索类型 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源时，此选项才可用。 </p> <p>允许您从以下三种类型的搜索中进行选择。 </p> <p> 
        <ul id="ul_E1D8B3DE9DB24DE4813D53F6298A03A6"> 
          <li id="li_C3DD7AA7699B477A9EE0731CFC012630"> <span class="uicontrol"> 全部 </span> <p>搜索包含查询字符串中所有单词的文档。 </p> <p>在禁用搜索词并忽略这些字符之前，使用"+"和"-"。 </p> </li> 
          <li id="li_4C66B9EFEFA042908A4D3730F9F54EB0"> <span class="uicontrol"> 任何 </span> <p>允许使用"+"和"-"字前缀。 </p> </li> 
          <li id="li_37E9AD42A61C4E31A0816DFB8E71118D"> <span class="uicontrol"> 短语  </span> <p>查询字符串被视为带引号的短语，所有用户类型的引号都会被忽略。 </p> <p>在禁用搜索词并忽略这些字符之前，使用"+"和"-"。 </p> </li> 
        </ul> </p> <p> 如果希望查询中的每个单词都可能选择facet值，则主搜索应始终使用<span class="uicontrol">所有</span>。 </p> <p>您可以查看有关在搜索查询中使用+和 — 修饰符的搜索提示。 </p> <p>请参阅<a href="../c-about-settings-menu/c-about-searching-menu.md#concept_207105CF26B1448F8A3D223787C56AB8" type="concept" format="dita" scope="local">关于搜索</a>。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>收藏集 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源时，此选项才可用。 </p> <p>标识索引中要搜索的集合。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Promosearch </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源时，此选项才可用。 </p> <p>允许您根据您指定的<span class="uicontrol">结果数</span>使用搜索结果中的随机选择。 </p> <p>Promosearch是一个旧概念。 因此，我们建议您在网站搜索/促销中使用新的横幅管理系统。 </p> <p>请参阅<a href="../c-about-design-menu/c-about-banners.md#concept_5BBE01FEC6134393B43CC917C8CC64DA" type="concept" format="dita" scope="local">关于横幅</a>。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>应用彩块化参数 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源，并且选择了<span class="uicontrol"> Promosearch </span>时，此选项才可用。 </p> <p>指定促销搜索使用选定的彩块化来缩小促销范围。 大多数促销搜索帐户不使用此选项。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>如果没有匹配的促销，请提供默认促销 </p> </td> 
      <td colname="col2"> <p>仅当您选择<span class="uicontrol">Search&amp;Promote</span>作为源，并且选择了<span class="uicontrol"> Promosearch </span>时，此选项才可用。 </p> <p>指定如果促销的初始搜索未找到任何内容，则进行促销的另一次搜索。 第二次搜索促销时会删除关键字。 相反，它会查找任何将“is_default”元数据字段设置为“yes”的促销。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>高亮搜索 </p> </td> 
      <td colname="col2"> <p>从主搜索中提取要在“hero-zone”中突出显示的选定数量的结果。 </p> <p>通常，高亮搜索具有与主搜索相似的搜索标准，但使用不同的排名机制来高亮显示某些结果。 软件将从主搜索中删除重复。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>基本搜索 </p> </td> 
      <td colname="col2"> <p>仅当您选择了<span class="uicontrol">高亮搜索</span>时，此选项才可用。 </p> <p>允许您选择包含突出显示结果的结果的搜索。 重复将从此搜索中删除。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>重复数据消除优先级 </p> </td> 
      <td colname="col2"> <p>仅当您选择了<span class="uicontrol">高亮搜索</span>时，此选项才可用。 </p> <p>允许您进行多次高亮搜索。 </p> <p>当您有多个高亮搜索时，您需要指定重复数据消除的优先级，其中“1”是最高优先级。 </p> <p>例如，假设您有两个高亮搜索：畅销书和新产品。 理论上是。 卖得最好的也是新产品。 在这种情况下，您希望从新产品和主搜索中删除重复。 因此，您将畅销书的优先级设置为1，将新产品的优先级设置为2。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>参数 </p> </td> 
      <td colname="col2"> <p>允许您向搜索中添加CGI参数。 </p> <p>请参阅<a scope="local" href="../c-appendices/c-cgiparameters.md#reference_582E85C3886740C98FE88CA9DF7918E8" type="reference" format="dita">后端搜索CGI参数</a>。 </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. 单击 **[!UICONTROL Save Changes]**.
1. （可选）在[!DNL Searches]页面上，执行下列任一操作：

   * 单击&#x200B;**[!UICONTROL History]**&#x200B;可还原您所做的任何更改。

      请参阅[使用历史记录选项](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)。

   * 单击 **[!UICONTROL Live]**.

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)。

   * 单击 **[!UICONTROL Push Live]**.

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)。

## 删除搜索定义{#task_1D8E991E4C4146B7A7311FAE5DAA3742}

您可以删除不再需要或使用的指南搜索定义。

<!-- 

t_deleting_a_search_definition.xml

 -->

请参阅[关于模板](../c-about-design-menu/c-about-templates.md#concept_06EB481B14864E18A8AE2BCD1D6EF0B5)。

**删除搜索定义**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Searches]**。
1. 在[!DNL Searches]页面的表格中，单击要删除的定义行中的&#x200B;**[!UICONTROL Delete]**。
1. 在[!DNL Confirmation]对话框中，单击&#x200B;**[!UICONTROL OK]**。
1. （可选）在[!DNL Searches]页面上，执行下列任一操作：

   * 单击&#x200B;**[!UICONTROL History]**&#x200B;可还原您所做的任何更改。

      请参阅[使用历史记录选项](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)。

   * 单击 **[!UICONTROL Live]**.

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)。

   * 单击 **[!UICONTROL Push Live]**.

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)。

## 关于固定结果关键字管理器{#concept_0C5F152C029C485D8872C6795CBCD7C7}

您可以手动将搜索结果固定到特定位置。 这些固定结果与特定搜索查询或关键字相关联。 可以使用[!DNL Pinned Result Keyword Manager]管理具有固定结果的所有关键字。

<!-- 

c_about_pinned_results_keyword_manager.xml

 -->

## 要遵循的关键字搜索规则{#section_ED67A24BE884468286F34FA5DFF826D7}

您在面板中输入的搜索查询具有以下规则：

* 前导和尾随空格将从查询中删除。
* 不允许使用特殊搜索字符，例如：

   * 与星号(*)匹配的通配符。
   * 没有必要或必须使用加号或减号（+或 — ）。
   * 没有带冒号字符(:)的字段说明符。
   * 没有逗号或多次引号（或“）。

* 允许在查询中使用空格分隔的多个术语或单词。
* 大写字母将转换为小写字母。

搜索词会按原样记忆；您必须再次使用完全相同的搜索词才能获得完全相同的结果。

固定结果不支持区分大小写。 所有关键字的大写字母都转换为小写字母。

## 重新排列搜索结果{#section_46FBE5279C7740A09D6DC9F54FE104AA}

在[!DNL Stage Add New Keyword]面板或[!DNL Staged Edit Keyword]面板中搜索关键字时，搜索结果将反映下一个索引操作后可能发生的情况。 可以使用三种不同方法之一对表中的搜索结果重新排序。

第一种方法是使用&#x200B;**[!UICONTROL Pinned]**&#x200B;复选框。 此复选框用于将结果固定到特定位置。 选中此复选框时，此复选框上方的所有搜索结果也会固定。 此功能可确保该复选框上方的所有结果按特定顺序显示。 取消固定搜索结果会使其降至所有当前固定结果之下。

第二种方法是使用表格中的拖放操作。 您可以通过拖放将结果移动到新位置。 将结果拖动到新位置后，新位置上方的所有结果都将固定下来。 此自动固定可确保其余结果显示在最近拖动的结果上方。

第三种方法是通过在“#”列中输入特定位置来设置固定结果的顺序。 与拖放操作不同，仅当您下次打开[!DNL Staged Edit Keyword]面板时，模拟搜索结果的顺序才是显而易见的。 设置当前未固定行的订单编号可确保至少有多个项目被固定。 设置当前固定行的顺序编号可设置当前固定项目内该项目的顺序。 但是，它不会增加固定项目的数量。

在保存搜索结果时，可以通过在“关键字”字段中输入完全相同的查询，再次视图结果。

## 关于固定的搜索结果{#section_46780B7812F249F3B45503161C4FBDEE}

搜索结果通常按相关性得分排序。 但是，固定搜索结果忽略相关性分数并尝试用其预定位置覆盖自然顺序。 通过确保结果保持相对原样，必须固定其上的其他已知搜索结果。

面板中显示的搜索结果将模拟下一个索引后显示的内容。 但是，从原始文档更改或会员中心中的特定配置更改可能会产生不一致的结果。 例如，更改文档的内容直到索引之后才知晓。

固定结果在索引后以相似或相同的顺序显示，因为它们忽略了相关性。 未固定结果在指数后回落至其自然位置；未固定结果的顺序不保证。

## 添加新关键字{#task_8CED128DADD34D0DAD2C64B64D0D6B06}

您可以添加新关键字及其固定结果。

<!-- 

t_adding_a_new_keyword.xml

 -->

在添加新关键字时，您可以对搜索结果重新排序并将其固定到特定位置。

**添加新关键字**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Pinned Results]**。
1. 在[!DNL Pinned Keyword Results Manager]页面上，单击&#x200B;**[!UICONTROL Add New Keyword]**。
1. 在[!DNL Add New Keyword]页面的&#x200B;**[!UICONTROL Keyword]**&#x200B;字段中，输入搜索查询，然后单击&#x200B;**[!UICONTROL Search Keyword]**。

   <!-- 
   
   r_keyword_options.xml
   
   -->

   可以使用“编辑表”按钮调整视图搜索结果表的方式。 例如，您可以使用列的列表显示或隐藏特定列。 您还可以使用拖放重新排列列的顺序。

   下表描述了表编辑器中的列属性。

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>列 </p> </th> 
      <th colname="col2" class="entry"> <p>描述 </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>订购 </p> </td> 
      <td colname="col2"> <p>指定列外观的数值顺序。 您可以拖放列以自动更新顺序。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>字段名称 </p> </td> 
      <td colname="col2"> <p>标识在<span class="wintitle">分阶段添加新关键字</span>面板和<span class="wintitle">分阶段编辑关键字</span>面板的<span class="wintitle">模拟搜索结果</span>表中显示的列标题的名称。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>包含 </p> </td> 
      <td colname="col2"> <p>如果选中该框，则列将显示在“固定结果表”中。 如果该框为空或取消选中，该列将从表中消失。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>将URL显示为图像 </p> </td> 
      <td colname="col2"> <p>如果分配给此列的meta字段具有图形或图片的URL，选中此框会在其周围放置HTML图像标记，并显示图片。 缺少图片或错误链接为空。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>字段长度 </p> </td> 
      <td colname="col2"> <p>允许您输入显示文本的最大长度，然后用省略号(...)截断。 如果将列设置为将URL显示为图像，则此字段不起作用。 </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. （可选）执行下列任一操作：

   * 重新排序搜索结果。
   * 单击&#x200B;**[!UICONTROL Edit Table]**&#x200B;以调整[!DNL Simulated Search Results]表的视图。 完成后，单击&#x200B;**[!UICONTROL Save Changes]**&#x200B;返回至[!DNL Add New Keyword]面板。

1. 单击 **[!UICONTROL Save Search Results]**.
1. （可选）如果要预览结果，请重新构建分阶段站点索引。

   请参阅[配置分阶段网站的增量索引](../c-about-index-menu/c-about-incremental-index.md#task_46A367B0786C4C90BFFA5D3F95FD86C0)。
1. （可选）在[!DNL Pinned Results Keyword Manager]页面上，执行下列任一操作：

   * 单击&#x200B;**[!UICONTROL History]**&#x200B;可还原您所做的任何更改。

      请参阅[使用历史记录选项](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)。

   * 单击 **[!UICONTROL Live]**.

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)。

   * 单击 **[!UICONTROL Push Live]**.

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)。

## 编辑关键字{#task_30C550A7350B4394B5B43536368A84B1}

您可以编辑现有关键字及其固定结果。

<!-- 

t_editing_a_keyword.xml

 -->

在编辑关键字时，您可以对搜索结果重新排序并将其固定到特定位置。

**编辑关键字**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Pinned Results]**。
1. 在[!DNL Pinned Keyword Results Manager]页面的表格中，单击要更改的关键字行中的&#x200B;**[!UICONTROL Edit]**。
1. 在[!DNL Edit Keyword]页面的&#x200B;**[!UICONTROL Keyword]**&#x200B;字段中，输入搜索查询，然后单击&#x200B;**[!UICONTROL Search Keyword]**。

   请务必遵循关键字搜索规则。

   <!-- 
   
   r_keyword_options.xml
   
   -->

   可以使用“编辑表”按钮调整视图搜索结果表的方式。 例如，您可以使用列的列表显示或隐藏特定列。 您还可以使用拖放重新排列列的顺序。

   下表描述了表编辑器中的列属性。

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>列 </p> </th> 
      <th colname="col2" class="entry"> <p>描述 </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>订购 </p> </td> 
      <td colname="col2"> <p>指定列外观的数值顺序。 您可以拖放列以自动更新顺序。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>字段名称 </p> </td> 
      <td colname="col2"> <p>标识在<span class="wintitle">分阶段添加新关键字</span>面板和<span class="wintitle">分阶段编辑关键字</span>面板的<span class="wintitle">模拟搜索结果</span>表中显示的列标题的名称。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>包含 </p> </td> 
      <td colname="col2"> <p>如果选中该框，则列将显示在“固定结果表”中。 如果该框为空或取消选中，该列将从表中消失。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>将URL显示为图像 </p> </td> 
      <td colname="col2"> <p>如果分配给此列的meta字段具有图形或图片的URL，选中此框会在其周围放置HTML图像标记，并显示图片。 缺少图片或错误链接为空。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>字段长度 </p> </td> 
      <td colname="col2"> <p>允许您输入显示文本的最大长度，然后用省略号(...)截断。 如果将列设置为将URL显示为图像，则此字段不起作用。 </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. （可选）执行下列任一操作：

   * 重新排序搜索结果。
   * 单击&#x200B;**[!UICONTROL Edit Table]**&#x200B;以调整[!DNL Simulated Search Results]表的视图。

      请参阅[添加新关键字](../c-about-settings-menu/c-about-searching-menu.md#task_8CED128DADD34D0DAD2C64B64D0D6B06)。

      完成后，单击&#x200B;**[!UICONTROL Save Changes]**&#x200B;返回至[!DNL Add New Keyword]面板。

1. 单击 **[!UICONTROL Save Search Results]**.
1. （可选）如果要预览结果，请重新构建分阶段站点索引。

   请参阅[配置分阶段网站的增量索引](../c-about-index-menu/c-about-incremental-index.md#task_46A367B0786C4C90BFFA5D3F95FD86C0)。
1. （可选）在[!DNL Pinned Results Keyword Manager]页面上，执行下列任一操作：

   * 单击&#x200B;**[!UICONTROL History]**&#x200B;可还原您所做的任何更改。

      请参阅[使用历史记录选项](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)。

   * 单击 **[!UICONTROL Live]**.

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)。

   * 单击 **[!UICONTROL Push Live]**.

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)。

## 删除关键字{#task_F17D6357D6DD416495E6D4117899D81D}

您可以删除不再需要或使用的关键字。

<!-- 

t_deleting_a_keyword.xml

 -->

在添加新关键字时，您可以对搜索结果重新排序并将其固定到特定位置。

**删除关键字**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Pinned Results]**。
1. 在[!DNL Pinned Keyword Results Manager]页面的表格中，单击要删除的关键字行中的&#x200B;**[!UICONTROL Delete]**。
1. 在[!DNL Delete Keyword]页面上，单击&#x200B;**[!UICONTROL Delete]**。
1. （可选）如果要预览结果，请重新构建分阶段站点索引。

   请参阅[配置分阶段网站的增量索引](../c-about-index-menu/c-about-incremental-index.md#task_46A367B0786C4C90BFFA5D3F95FD86C0)。
1. （可选）在[!DNL Pinned Results Keyword Manager]页面上，执行下列任一操作：

   * 单击&#x200B;**[!UICONTROL History]**&#x200B;可还原您所做的任何更改。

      请参阅[使用历史记录选项](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)。

   * 单击 **[!UICONTROL Live]**.

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)。

   * 单击 **[!UICONTROL Push Live]**.

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)。

## 关于集合{#concept_62E42ACE53D54EEE9273433B86259127}

您可以使用集合来允许客户搜索网站的特定区域，以便他们快速找到所寻找的内容。

<!-- 

c_about_collections.xml

 -->

请参阅[关于搜索](../c-about-settings-menu/c-about-searching-menu.md#concept_207105CF26B1448F8A3D223787C56AB8)。

请参阅[在搜索表单中使用集合](../c-appendices/c-searchforms.md#reference_5A079AEEEFB84457892EF0870D0605C3)。

例如，客户可以搜索与产品销售或支持服务相关的URL集合。 在客户可以使用您指定的收藏集之前，请确保在“搜索表单”菜单下更新您的搜索表单。

在“集合”设置的效果对客户可见之前，请重新构建您的站点索引。

您可以通过在可选的&#x200B;**[!UICONTROL Test Collections]**&#x200B;字段中输入您的网站URL之一，然后单击&#x200B;**[!UICONTROL Test]**&#x200B;来测试您的集合。 将返回指定页面所属的集合。

每个集合都在具有名称和URL掩码的单行上指定。 URL掩码可以由以下组成：

* 完整路径，如`https://www.mydomain.com/products.html`
* 部分路径，如`https://www.mydomain.com/products`
* 常表达式

   要使蒙版成为常规表达式，请在集合名称和URL蒙版之间插入关键字`regexp`。

   请参阅[常规表达式](../c-appendices/r-regular-expressions.md#reference_B5BA7D61D82E4109A01D2A2D964E3A6A)。

“集合”字段中的每一行只能包含一个URL蒙版。 但是，您可以在不同行上为同一集合名称指定多个URL蒙版。 以下示例包含四个不同的集合名称和五个URL蒙版：

```
Company Info https://www.yoursite.com/company 
Products https://www.yoursite.com/products 
FAQs regexp ^.*/faqs 
Support https://www.yoursite.com/email_support/ 
Support https://www.yoursite.com/phone_support/
```

在此示例中，在您更新了搜索表单以包含这些收藏集后，客户可以单独选择和搜索每个定义的收藏集。 `Support`集合包含与URL蒙版匹配的文件，因此在选择此集合时，会搜索`www.yoursite.com/email_support/`和`www.yoursite.com/phone_support`中的文件。

## 添加集合{#task_07732D0F00104E59AD421297A704B2F6}

您可以添加集合，使客户能够搜索网站的特定区域，以便他们快速找到所寻找的内容。

<!-- 

t_adding_collections.xml

 -->

请确保重新构建网站索引，以便您的客户能够看到URL蒙版的结果。

请参阅[配置分阶段网站的增量索引](../c-about-index-menu/c-about-incremental-index.md#task_46A367B0786C4C90BFFA5D3F95FD86C0)。

**要添加收藏集，请执行以下操作**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Collections]**。
1. 在[!DNL Collections]字段中，输入集合名称和URL掩码地址（每行一个）。
1. （可选）在[!DNL Collections]页面的&#x200B;**[!UICONTROL Test Collections]**&#x200B;字段中，输入网站中的测试URL掩码，然后单击&#x200B;**[!UICONTROL Test]**。

   将显示测试集合输出窗口，其中显示URL和集合的名称。
1. 添加完集合后，单击&#x200B;**[!UICONTROL Save Changes]**。
1. （可选）如果要预览结果，请重新构建分阶段站点索引。

   请参阅[配置分阶段网站的增量索引](../c-about-index-menu/c-about-incremental-index.md#task_46A367B0786C4C90BFFA5D3F95FD86C0)。
1. （可选）在[!DNL Collections]页面上，执行下列任一操作：

   * 单击&#x200B;**[!UICONTROL History]**&#x200B;可还原您所做的任何更改。

      请参阅[使用历史记录选项](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)。

   * 单击 **[!UICONTROL Live]**.

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)。

   * 单击 **[!UICONTROL Push Live]**.

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)。

## 关于限制{#concept_B5B527E04EBF4E9AB5956EEF881DDBF1}

在执行搜索之前，检查引荐URL和IP地址以确定是否可以从该位置进行搜索。 您在[!DNL Restrictions]中指定的内容将决定是否允许搜索。 如果不允许搜索，则向请求者返回通用错误页。

<!-- 

c_about_restrictions.xml

 -->

可以将限制设置指定为推荐人URL掩码或IP地址掩码。 这两种限制都包括允许搜索的蒙版，并排除蒙版以拒绝它们。

如果同时通过推荐人URL和IP地址限制条件，则允许搜索。 如果任一设置不允许搜索，则无论允许搜索的其他限制如何，搜索都将失败。

例如，如果搜索请求的“HTTP推荐人”字段与“exclude”推荐人URL掩码匹配，则即使请求的IP地址与“include” IP地址掩码匹配，搜索也会失败。 如果没有与推荐人URL或IP地址匹配的掩码，则默认情况下将包含该位置。

在单行上输入每个包含蒙版或排除蒙版。

## 添加推荐人URL掩码或IP地址掩码限制{#task_E6FF2DD83E8D4B00A0E2809DC13A56C9}

您可以将限制设置指定为“推荐人URL掩码”或“IP地址掩码”。 这两种限制都包括允许搜索的蒙版，并排除蒙版以拒绝它们。 如果同时通过推荐人URL和IP地址限制条件，则允许搜索。

<!-- 

t_adding_url_mask_or_jp_address_restrictions.xml

 -->

**添加推荐人URL掩码或IP地址掩码限制**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Restrictions]**。
1. 在[!DNL Restrictions]页面上，设置所需的限制选项。 输入推荐人URL掩码地址、IP地址掩码地址，或者（可选）输入自定义网页的URL地址，该地址显示给不允许搜索您网站的客户。

   <!-- 
   
   r_restriction_options.xml
   
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
      <td colname="col1"> <p>推荐人URL蒙版 </p> </td> 
      <td colname="col2"> <p>将读取HTTP推荐人头中的推荐人URL。 与推荐人URL匹配的第一个蒙版决定是否允许搜索（如果蒙版是包含蒙版）。 或者，如果蒙版是排除蒙版，则该蒙版将决定是否禁止搜索。 如果没有与推荐人URL匹配的蒙版，则包含该URL并允许搜索。 </p> <p> 如果您的搜索模板包含新的搜索表单，或者您的搜索模板可包含“下一个10”、“上一个10”或“隐藏摘要”等链接，则您可以将搜索结果模板列表为“包含”蒙版。 执行此操作的最简单方法是使用常规表达式，如下例所示： </p> <p> <span class="codeph"> 包括regexp ^https?://[^/]*\.atomz\.com/。*[?&amp;]sp_a=sp1000130e.*$ </span> </p> <p>下面的示例包含五个不同的推荐人URL蒙版： </p> <p> <code> include&nbsp;https://www.mydomain.com/search/ 
          include&nbsp;https://search.mydomain.com/ 
          include&nbsp;regexp&nbsp;^https://www.mydomain.com/help/.*/search/ 
          include&nbsp;regexp&nbsp;^https?://[^/]*\.atomz\.com/.*[?&amp;]sp_a=sp1000130e.*$ 
          exclude&nbsp;* </code> </p> <p>如果推荐人URL蒙版为： </p> <p> <code> https://www.mydomain.com/search/searchpage.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;allowed] 
          https://search.mydomain.com/advanced/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;allowed] 
          https://www.mydomain.com/help/products/search/advanced/&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;allowed] 
          https://www.mydomain.com/help/products/&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;disallowed] 
          https://www.anotherdomain.com/&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;disallowed] 
          blank&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;disallowed] </code> </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>IP地址掩码 </p> </td> 
      <td colname="col2"> <p>如果掩码是包含掩码，则匹配IP地址的第一个掩码决定是否允许搜索。 或者，如果蒙版是排除蒙版，则它决定是否允许搜索。 如果没有掩码与请求的IP地址匹配，则包括该IP地址，并允许搜索。 </p> <p>以下示例显示了四个不同的IP地址掩码。 </p> <p> <code> include&nbsp;64.128.192.* 
          include&nbsp;192.168. 
          include&nbsp;regexp&nbsp;^209\.42\.97\.[1-5]+ 
          exclude&nbsp;* </code> </p> <p>如果引用IP地址掩码如下： </p> <p> <code> 64.128.192.10&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;allowed] 
          192.168.10.127&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;allowed] 
          209.42.97.14&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;allowed] 
          64.128.193.10&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;disallowed] 
          192.169.10.14&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;disallowed] 
          209.42.97.68&nbsp;&nbsp;&nbsp;&nbsp;[then&nbsp;search&nbsp;is&nbsp;disallowed] </code> </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>仅允许使用HTTPS的搜索 </p> </td> 
      <td colname="col2"> <p>将搜索限制为HTTPS。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>应将不允许的请求发送到的URL </p> </td> 
      <td colname="col2"> <p> 受限用户将被重定向到您在此处输入的URL。 此选项可让您制作自己的自定义错误页面，以显示给不允许搜索您网站的客户。 </p> <p>如果未指定URL，则当受限用户尝试搜索您的站点时，将返回一个通用错误页。 </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. 单击 **[!UICONTROL Save Changes]**.
1. （可选）执行下列任一操作：

   * 单击&#x200B;**[!UICONTROL History]**&#x200B;可还原您所做的任何更改。

      请参阅[使用历史记录选项](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)。

   * 单击 **[!UICONTROL Live]**.

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)。

   * 单击 **[!UICONTROL Push Live]**.

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)。

## 关于预览{#concept_DF293FD3B02C467F8842C8C21D62F294}

您在[!DNL Preview]中设置的查询字符串和参数在软件中测试或预览搜索表单时随时使用。

<!-- 

c_about_preview.xml

 -->

另请参阅[关于搜索](../c-about-settings-menu/c-about-searching-menu.md#concept_207105CF26B1448F8A3D223787C56AB8)。

## 在预览{#task_CE267A0FF621474E80AB43B67B1C28D7}中设置值

在软件中测试或预览搜索表单时，会随时使用您设置的预览值。

<!-- 

t_setting_values_in_preview.xml

 -->

**在预览中设置值**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Preview]**。
1. 在[!DNL Preview]页面上，设置所需的选项。

   <!-- 
   
   r_preview_options.xml
   
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
      <td colname="col1"> <p>查询 </p> </td> 
      <td colname="col2"> <p>默认情况下，查询字符串设置为<span class="codeph"> * </span>，这通常会返回结果。 但是，您可以指定更具体于网站内容的查询。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>参数 </p> </td> 
      <td colname="col2"> <p>参数设置有名称和值。 您可以根据需要指定任意数量的其他参数。 例如，可以使用<span class="codeph"> sp_q_1 </span>和<span class="codeph"> sp_x_1 </span>参数指定其他搜索条件。 参数值<span class="codeph"> sp_q_1=windows&amp;sp_x_1=platform </span>创建预览搜索，该搜索在搜索页面的“platform”meta标签中查找值“windows”，此外还创建主查询。 </p> <p>请参阅<a href="../c-appendices/c-cgiparameters.md#reference_582E85C3886740C98FE88CA9DF7918E8" type="reference" format="dita" scope="local">后端搜索CGI参数</a>。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>主机 </p> </td> 
      <td colname="col2"> <p>如果您的网站使用专用域标签，请设置正确的主机名以准确预览您的搜索结果。 </p> <p>有关专用域标签的信息，请与客户支持联系。 </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. 单击 **[!UICONTROL Save Changes]**.
1. （可选）执行下列任一操作：

   * 单击&#x200B;**[!UICONTROL History]**&#x200B;可还原您所做的任何更改。

      请参阅[使用历史记录选项](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)。

   * 单击 **[!UICONTROL Live]**.

      请参阅[查看实时设置](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)。

   * 单击 **[!UICONTROL Push Live]**.

      请参阅[实时推送舞台设置](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)。

## 关于源{#concept_FEBFEE51A3AB49F88CBA0D16E2AD6916}

搜索索引将被视为您网站的大型数据库。 如果有来自正确元标签的足够信息，信息就会被收集和组织，或整合到数据馈送中。 您可以将这些数据馈送提交到其他服务，如第三方收件人。

<!-- 

c_about_feeds.xml

 -->

在您的网站被爬网和索引后，您可以生成自动源并将其提交到第三方有机搜索引擎和购物引擎。 您可以创建以下流源：

<table> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>源类型 </p> </th> 
   <th colname="col2" class="entry"> <p>描述 </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Adobe Recommendations </p> </td> 
   <td colname="col2"> <p>Recommendations feeds通过Adobe Recommendations提供数据整合功能。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>通用信息源 </p> </td> 
   <td colname="col2"> <p>您可以使用“通用源”类型实现许多源。 将根据网站的索引生成自定义搜索查询。 通过自定义的搜索模板返回数据，使用相同的模板语言显示搜索结果。 这种灵活性意味着您可以向更多供应商提交源，而不仅仅是特定的源类型。 </p> <p>您可以使用以下帮助主题中的说明添加传输（搜索）模板： </p> <p>请参阅<a href="../c-about-design-menu/c-about-templates.md#task_73199757B6E748CAA604902FF913F012" type="task" format="dita" scope="local">添加新演示文稿或传输模板文件</a>。 </p> <p> 添加模板后，使用搜索模板标记对其进行编辑以定义要包括的搜索元数据字段及其格式。 </p> <p>请参阅<a href="../c-about-design-menu/c-about-templates.md#task_800E0E2265C34C028C92FEB5A1243EC3" type="task" format="dita" scope="local">编辑演示文稿或传输模板</a>。 </p> <p>请参阅<a href="../c-appendices/c-templates.md#reference_F7AA3FF602314E42842BBC740D2CA1A4" type="reference" format="dita" scope="local">搜索模板标记</a>。 </p> <p>请确保记住传输模板文件的名称。 在指定源的条件时，可以使用名称将通用源绑定到模板。 </p> <p>如果您之前曾使用其他源，请记住，您将源字段映射到搜索元数据字段。 在<span class="uicontrol">创建源</span>向导中，常规源没有此特定步骤。 相反，模板会指定元数据和元数据的格式。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Google Merchant </p> </td> 
   <td colname="col2"> <p>Google Merchant Center允许人们通过多种Google服务销售产品。 它有一个数据整合组件，您可以在其中定期提交可销售产品的列表。 </p> <p>与任何第三方源供应商一样，Google Merchant Center在他们认为该源合法之前，有您满足的特定标准。 有关详细信息，请联系您的客户代表并访问Google Merchant文档。 以下是Google商家中心在验证源时所考虑内容的快速摘要： </p> 
    <ul id="ul_3D84D4A6A4BF4C08860F86403F8F9CD6"> 
     <li id="li_5B6516CC7BC7493B8B8E8AFB454E573F">每个产品都有一个产品页面；专用URL。 </li> 
     <li id="li_5A6D5AD5E1B54A94B224D19E888B5443"> 每个产品变体在Feed中都有一个单独的条目。 </li> 
     <li id="li_89748D3241B34A4493576DAC38681988"> 每个产品都有一个图像URL，最好是从您的服务器发出。 产品变体具有显示其实际变体的特定图像。 换句话说，不同的鞋色不应共享相同的图像。 </li> 
     <li id="li_A594AD19480F41EAA72181355F28447B"> 每个产品都包含特定信息，如可用性、条件、说明、类别和价格。 </li> 
     <li id="li_0955B3A6ED2746D2B7CB42DC8AB27D3A">通常，每个产品都有一个唯一标识符，如ISBN、UPC、JAN或EAN等。 </li> 
     <li id="li_2C371653F1C5471FA638F3A3818ABC17">通常，每个产品都按谷歌的产品分类分类。 </li> 
     <li id="li_6EB392A5A0BE490FAED5BC5E83228E32"> 服装产品具有其他必填字段，如性别、年龄组、颜色和大小。 </li> 
     <li id="li_44B91FA9A95F4172A2F03F8206E9081E"> 税和运费在Google Merchant Center中指定为帐户设置，或在此源中按产品逐项指定。 </li> 
     <li id="li_71A63E9905B840C0A04F6CDAA23C9AB0"> 定制产品和某些服装产品可以免除某些规则，但您必须联系Google获取许可，并了解这些免除的详细信息。 </li> 
    </ul> <p>有许多用于控制源验证的详细信息。 有关信息源管理的信息，请参阅Google Merchant文档。 Google经常对规范进行更改，因此请经常查阅文档。 </p> <p>与Google Merchant Center关联的源通常称为Google产品搜索源。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Google站点地图 </p> </td> 
   <td colname="col2"> <p>Google站点地图为您提供了一种影响Google对您网站的爬网方式的方法。 将定期向Google Sitemap提交协同数据源（本例中为Sitemap）。 Sitemap包含可访问Internet的URL，并可与每个URL关联特定信息（如上次修改日期或页面优先级）。 向谷歌提供此类信息，可以增加特定页面被爬网和索引的频率和几率。 在某些情况下，Sitemap用于播发链接列表，在正常情况下，其Crawler无法访问这些链接。 </p> <p>如果您有兴趣使用我们的源功能创建Google Sitemap，请联系您的客户代表。 Google已将其Google Sitemap服务向公众提供，并在其Google Webmaster Tools页面提供文档。 </p> <p> <b>创建Google Sitemap源的要求</b> </p> <p>要创建Google Sitemap源，请确保已设置Google Sitemap的Google Webmaster Tools帐户。 有关设置Google Sitemap的信息，请参阅Google Webmaster工具文档。 </p> <p>您还需要确定如何传送Sitemap文件。 通常，Sitemap文件来自您的域，尤其是网站的根。 简单的模型是通过FTP将文件传送到您的服务器。 另一种解决方案是将Sitemap文件的请求重定向到网站搜索/促销内容网络。 请联系您的咨询代表，了解如何协调和设置Sitemap源的投放。 </p> </td> 
  </tr> 
 </tbody> 
</table>

如果您对自动源感兴趣，请联系专业服务部门以获得帮助。 每个源在数据质量和文件传输方面都有严格的要求。

您选择的源类型影响使用&#x200B;**[!UICONTROL Create Feed]**&#x200B;向导构建字段时显示的选项。 每种类型的源都有不同的数据格式。 请务必遵循正确的数据格式，以避免源收件人拒绝源或向客户发布不当数据。 除数据格式外，供应商通常有一种或多种接收数据的首选方式。 请查阅供应商的文档，了解其源。

创建源的一个挑战是匹配网站搜索/促销和源之间的数据。 通常，从索引搜索检索到的数据格式错误或缺少。 以下是一列表问题，它们可以帮助您在创建信息源时专注于要查找的内容。

* 您与源收件人有哪种业务关系？
* 您是否必须注册并使用源收件人创建帐户？
* 谁将监控和处理与供应商相关的信息源中出现的问题？ 一般而言，您有责任管理供应商的帐户。 例如，Google Sitemap需要一个WebMaster帐户和一个人来监视Sitemap的运行状况。
* 该源的数据格式是什么？
* 您的索引是否与源的字符编码匹配？ 当您的数据包含制表符或逗号时，制表符分隔和逗号分隔的数据格式会成为问题。
* 当您的数据中包含制表符或逗号时，您会怎么做？
* 索引中是否有包含空数据的页面？
* 源收件人是否接受空数据？ 您可以通过编辑软件检索数据的标准来解析空数据。
* 数据格式是否与源收件人需要的内容一致？ 例如，某些源收件人具体说明了如何显示价格和货币。
* 供应商是否有最多可接受的项目数？ 您可以通过使用搜索条件限制结果来解决此潜在问题。
* 供应商希望如何接收源？ 支持FTP提交和HTTP托管。

## 创建源{#task_63179C1FC359497483CD6CE13FD1C250}

您可以创建一个或多个数据馈送。

<!-- 

t_creating_a_feed.xml

 -->

**创建源**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Feeds]**。
1. 在[!DNL Feeds]页面上，从&#x200B;**[!UICONTROL Create Feed]**&#x200B;下拉列表中选择源类型。
1. 根据您选择的源类型，在[!DNL Create Feed]对话框中，设置在向导的每个面板中标识的选项。

   <!-- 
   
   r_feed_options.xml
   
   -->

   根据您创建或编辑的源类型，可用选项略有不同。

   **Adobe 推荐**

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>面板 </p> </th> 
      <th colname="col2" class="entry"> <p>向导面板名称 </p> </th> 
      <th colname="col3" class="entry"> <p>描述 </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>1 </p> </td> 
      <td colname="col2"> <p>馈送名称 </p> </td> 
      <td colname="col3"> <p>指定源的名称。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>2 </p> </td> 
      <td colname="col2"> <p>字段映射 </p> </td> 
      <td colname="col3"> <p>允许您将特定于供应商的源字段映射到站点搜索/销售元数据字段。 向导中的此映射步骤很重要，因为它允许源关联索引中的字段与源数据中的字段之间的信息。 在大多数情况下，除<span class="wintitle">通用源</span>之外，关联将保存在动态生成的搜索模板中。 </p> <p><span class="wintitle">字段映射</span>表中的每一行都表示字段映射。 在表的“添加/删除”列中，单击<span class="uicontrol"> + </span>以添加新字段映射行；单击<span class="uicontrol"> - </span>从表中删除当前选定的字段映射行。 要将源字段与网站搜索/促销元数据字段关联，请使用相应的下拉列表选择所需的字段。 </p> <p> <b>Adobe Recommendations的字段映射</b> </p> <p>推荐数据馈送是一个CSV文件，数据列之间用逗号分隔。 每个映射在“字段映射”表上的外观顺序很重要，因为它们决定了CSV源文件中各列的顺序。 按以下顺序创建映射行 — 每行都是必填项： </p> <p> 
        <ol id="ol_49C739D04DD340168DC6C1F794544C35"> 
          <li id="li_A95D9C5A353746A3A0D38F200AC2EEA2"> ID </li> 
          <li id="li_044763D4C7054CEB948C94590735D74F"> name </li> 
          <li id="li_832F07CA0E3F4E10A4AE30171F3E8541"> categoryId </li> 
          <li id="li_2A33FB42F7E942ED881BA1F478542C4D"> message </li> 
          <li id="li_A76E66B2366845B0B63ED5C200531ADD"> thumbnailUrl </li> 
          <li id="li_518CCD5E7E404521AB8199981BA86F76"> value </li> 
          <li id="li_14A0A8FCC2B34B758E1FBB98E3F2DFB2"> pageUrl </li> 
          <li id="li_36D22F1603394AF89E0C7ADB18AAAAB7"> inventory </li> 
          <li id="li_ABDB9C762BBC4F27B82FEA4425A8DDC4"> margin </li> 
        </ol> </p> <p> <b>高级使用</b> </p> <p>在您映射了上述前九个必需的源字段后，您可以创建自己的自定义字段。 在<span class="wintitle">源字段</span>下拉列表中，单击<span class="uicontrol">自定义</span>。 在关联的文本字段中，输入该字段的自定义标记名称。 如果源需要特定于供应商的特殊字段，则此自定义选项很有用。 </p> <p> <p>注意： 尽管建议源规范规定每个字段名称必须前缀为“entity”，但在本例中不必。 </p> </p> <p>您还可以创建自定义元数据字段。 在<span class="wintitle">元数据字段</span>下拉列表中，单击<span class="uicontrol">自定义</span>。 在关联的文本字段中，输入自定义元数据字段值。 该值将插入预生成的模板中，并且还可用于插入自定义搜索模板标记。 </p> <p>请参阅<a href="../c-appendices/c-templates.md#reference_F7AA3FF602314E42842BBC740D2CA1A4" type="reference" format="dita" scope="local">搜索模板标记</a>。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>3 </p> </td> 
      <td colname="col2"> <p>搜索条件 </p> </td> 
      <td colname="col3"> <p>当生成源文件时，使用搜索查询来过滤数据。 您可以在此面板中定义用于搜索查询的过滤器。 </p> 
        <ul id="ul_799ECF61C03A44878C7182F8B88CC3AD"> 
        <li id="li_0763F600A4FB4650ACC28BF337EB50AF"> <span class="uicontrol"> 元字段  </span> <p>定义要筛选的元数据字段。 </p> <p> <b>高级使用</b> </p> <p>由于筛选系统是标准的搜索查询，您可以从下拉列表中选择<span class="uicontrol">自由格式</span>以输入CGI搜索参数及其值。 需要URL转义。 将忽略搜索参数<span class="codeph"> sp_q </span>。 您可以创建多行自由表单文本框。 在每行之间，参数将自动用&amp;'s分隔。 </p> <p>请参阅<a href="../c-appendices/c-cgiparameters.md#reference_DA27A8B0728246DA94994885E1353890" type="reference" format="dita" scope="local">搜索CGI参数</a>。 </p> </li> 
        <li id="li_756B776902AE4A0E95524442D663343E"> <span class="uicontrol"> 标准 </span> <p>定义筛选操作。 您从下拉列表中选择的筛选器操作将应用在第三列中输入的常量值。 </p> </li> 
        <li id="li_7ADEDB8747B241D78AC50F1AC75AE695"> <span class="uicontrol"> 值 </span> <p>常量值。 </p> </li> 
        <li id="li_4039A9BC2F74460B83BFF662B58DAA1B"> <span class="uicontrol"> 操作 </span> <p>添加新的字段映射行，或删除当前突出显示的行。 </p> </li> 
        </ul> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>4 </p> </td> 
      <td colname="col2"> <p>文件提交 </p> </td> 
      <td colname="col3"> <p>允许您配置提交源文件的计划，并设置要用于上传文件的方法。 </p> 
        <ul id="ul_55E253F83BDA46BAABF2BE38F0918E80"> 
        <li id="li_877A376B5B30422FAC816E31D50EA508"> <span class="uicontrol"> 计划 </span> <p>设置提交源的最大频率。 选择<span class="uicontrol">从不</span>将关闭源。 其他值定义了馈送在再次提交之前等待的时段。 在每个索引上决定何时提交源。 换句话说，在索引的末尾，将检查源以查看它是否已过期，并且需要由供应商更新和提交。 此外，它还用作防止帐户过度提交给供应商的方法。 某些供应商针对上传频率过高的数据源制定了策略。 请务必检查数据馈送供应商有关提交频率的策略。 
          <!--The time of the last upload and the status of the upload feed is displayed here. If any other feeds are currently running, their status appears here instead. Each account processes one feed at a time. --> 
          <!--ick <uicontrol>Manual Upload</uicontrol> to generate the feed and push the files to the final destination. Any schedule restrictions that you have already set are ignored. --> </p> <p> 
          <!--If <uicontrol>Manual Upload</uicontrol> is dimmed (inactive), the account is currently processing this feed or another feed. An account only works with one feed at a time. --> </p> </li> 
        <li id="li_760F5068D3ED46C582AE41392A2CA342"> <span class="uicontrol"> 上载方法  </span> <p>大多数源有两种分发文件的方式：FTP和托管内容网络。 </p> 
          <ul id="ul_666759EDDD034537AA7C0ED936A2F315"> 
          <li id="li_B4AD5CEEBB7B41C0B8DC291B95DC5F83"> <span class="uicontrol">FTP</span> <p>网站搜索/销售服务器使用被动式FTP。 </p> <p>FTP是将文件推送到另一台服务器的唯一方式。 </p> <p> <span class="uicontrol"> FTP服 </span> 务器 — 指定FTP服务器的名称。请勿包含协议或“ftp://”之前的内容。 </p> <p> <span class="uicontrol"> FTP用户名 </span>  — 指定FTP帐户的名称。 </p> <p> <span class="uicontrol"> FTP密 </span> 码 — 指定FTP帐户的密码。 </p> <p> <span class="uicontrol"> FTP文件名 </span>  — 指定要传输的文件的名称。如果源生成多个文件，则此名称是模板，通常在名称末尾但扩展之前递增一个数字。 例如：basename.xml， basename1.xml， basename2.xml，.., basename-Nth.xml </p> <p> <span class="uicontrol"> FTP目 </span> 录 — 如果需要特定目录路径，请在此处输入。不要在路径中包含文件名。 </p> </li> 
          <li id="li_C082D3993C6C469B9067F207703BE619"> <span class="uicontrol"> 托管内容网络  </span> <p>“内容网络”是从网站搜索/销售的Web服务器提供文件的方式。 源的收件人使用HTTP请求将其从Web服务器中提取。 设置此设置的唯一信息是<span class="uicontrol">内容网络文件名</span>。 文件名是所提供文件的基名。 仅使用文件扩展名的文件名。 根据源的不同，文件名是多个文件的模板，其中源可以生成以下格式的多个文件：basename.xml、basename1.xml、basename2.xml、...、basename-Nth.xml。 </p> <p>输入基本文件名并成功保存源后，向导的“验证”面板上将显示“内容网络”文件的URL。 URL在源成功处理后变为活动状态。 供应商可以从此URL获取源数据。 多个文件使用相同的URL路径。 但是，请确保根据明细列表方案替换或更改文件名。 </p> </li> 
          </ul> </li> 
        </ul> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>5 </p> </td> 
      <td colname="col2"> <p>验证 </p> </td> 
      <td colname="col3"> <p>当您进入<span class="wintitle">验证</span>面板时，将保存您的源。 但是，实际的源文件直到以后才会保存。 </p> <p>通过<span class="wintitle">验证</span>面板，可以执行以下操作： </p> 
        <ul id="ul_0C6EFB38E06F401696084863D85CBD0D"> 
        <li id="li_07FC9F04C7F640048546F9DC5D91DA1D"> <span class="uicontrol"> 数据视图  </span> <p>允许您单击链接，通过表格中显示的数据视图检查源输出。 数据视图还可以帮助您排除故障，方法是显示选择了哪些元字段，以及向导中<span class="wintitle">搜索条件</span>面板中的任何指定搜索条件如何影响源输出。 数据视图是动态生成的，因此始终可用。 </p> </li> 
        <li id="li_67046A56D08C48298E5A3E1F9C4A8AF3"> <span class="uicontrol"> 源文件  </span> <p>在站点搜索/促销服务器生成源文件后，您可以使用<span class="uicontrol">源文件</span>下拉列表从服务器视图文件。 将显示新的浏览器选项卡或新的浏览器窗口，其中包含源的内容。 此方法有助于解决格式问题的源。 请注意，您不会从最终目标或供应商自己视图文件。 </p> <p> 如果源是新的，则下拉列表为空，直到您生成源文件。 </p> </li> 
        <li id="li_99D66C7AD87A475CB3D831D514DB78A0"> <span class="uicontrol"> 内容网络链接  </span> <p>如果在向导的<span class="wintitle">文件提交</span>面板中选择<span class="uicontrol">托管内容网络</span>作为上传方法，则此处将显示URL。 如果尚未生成任何源文件，则在成功生成源之前，URL无效。 </p> </li> 
        </ul> </td> 
      </tr> 
    </tbody> 
    </table>

   **通用信息源**

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>面板 </p> </th> 
      <th colname="col2" class="entry"> <p>向导面板名称 </p> </th> 
      <th colname="col3" class="entry"> <p>描述 </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>1 </p> </td> 
      <td colname="col2"> <p>馈送名称 </p> </td> 
      <td colname="col3"> <p>指定源的名称。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>2 </p> </td> 
      <td colname="col2"> <p>搜索条件 </p> </td> 
      <td colname="col3"> <p>当生成源文件时，使用搜索查询来过滤数据。 您可以在此面板中定义用于搜索查询的过滤器。 </p> 
        <ul id="ul_C750687E69A647D0A4440FF1B6CC7E05"> 
        <li id="li_B5C3B8523D71472E9508A04E23AC0211"> <span class="uicontrol"> 元字段  </span> <p>定义要筛选的元数据字段。 </p> <p> <b>高级使用</b> </p> <p>由于筛选系统是标准的搜索查询，您可以从下拉列表中选择<span class="uicontrol">自由格式</span>以输入CGI搜索参数及其值。 需要URL转义。 将忽略搜索参数<span class="codeph"> sp_q </span>。 您可以创建多行自由表单文本框。 在每行之间，参数将自动用&amp;'s分隔。 </p> <p>请参阅<a href="../c-appendices/c-cgiparameters.md#reference_DA27A8B0728246DA94994885E1353890" type="reference" format="dita" scope="local">搜索CGI参数</a>。 </p> </li> 
        <li id="li_D1E49834BBEA42CC8C49AE7D72037C53"> <span class="uicontrol"> 标准 </span> <p>定义筛选操作。 您从下拉列表中选择的筛选器操作将应用在第三列中输入的常量值。 </p> </li> 
        <li id="li_D5F0651B834F4EACAD15A2D154A0737B"> <span class="uicontrol"> 值 </span> <p>常量值。 </p> </li> 
        <li id="li_FC8F382BD20C4518BC2230D4B4954591"> <span class="uicontrol"> 操作 </span> <p>添加新的字段映射行，或删除当前突出显示的行。 </p> </li> 
        </ul> <p>通用源需要指定特殊的CGI参数。 要绑定与此源关联的特殊模板，请定义<span class="codeph"> sp_t </span>参数。 将<span class="codeph"> sp_t </span>的值设置为传输模板文件的名称。 例如，如果您添加了名为<span class="codeph"> super_feed.tpl </span>的传输模板文件，则会创建一个自定义CGI搜索参数，作为<span class="codeph"> sp_t=super_feed </span>。 在您从<span class="wintitle">元字段</span>下拉列表中选择<span class="uicontrol">自由格式</span>之前，不会显示用于输入<span class="codeph"> sp_t </span>的文本框。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>1 </p> </td> 
      <td colname="col2"> <p>文件提交 </p> </td> 
      <td colname="col3"> <p>允许您配置提交源文件的计划，并设置要用于上传文件的方法。 </p> 
        <ul id="ul_30E830C41F6A4526822AF1FD3083075A"> 
        <li id="li_79EAFDBD2B9F411EA985CAEC1BAF3926"> <span class="uicontrol"> 计划 </span> <p>设置提交源的最大频率。 选择<span class="uicontrol">从不</span>将关闭源。 其他值定义了馈送在再次提交之前等待的时段。 在每个索引上决定何时提交源。 换句话说，在索引的末尾，将检查源以查看它是否已过期，并且需要由供应商更新和提交。 此外，它还用作防止帐户过度提交给供应商的方法。 某些供应商针对上传频率过高的数据源制定了策略。 请务必检查供应商有关提交频率的政策。 
          <!--he time of the last upload and the status of the upload feed is displayed here. If any other feeds are currently running, their status appears here instead. Each account processes one feed at a time. --> 
          <!--<uicontrol>Manual Upload</uicontrol> to generate the feed and push the files to the final destination. Any schedule restrictions that you have already set are ignored. --> </p> <p> 
          <!--If <uicontrol>Manual Upload</uicontrol> is dimmed (inactive), the account is currently processing this feed or another feed. An account only works with one feed at a time. --> </p> </li> 
        <li id="li_20BF70A19E7E45BA91CD972E2FCE0EA4"> <span class="uicontrol"> 上载方法  </span> <p>大多数源有两种分发文件的方式：FTP和托管内容网络。 </p> 
          <ul id="ul_5888C2E9097645CE89938EE09F8CB4F1"> 
          <li id="li_EA9ED19F3BEA4BEAB1A9F2C2FAFF85F7"> <span class="uicontrol">FTP</span> <p>网站搜索/销售服务器使用被动式FTP。 </p> <p>FTP是将文件推送到另一台服务器的唯一方式。 </p> <p> <span class="uicontrol"> FTP服 </span> 务器 — 指定FTP服务器的名称。请勿包含协议或“ftp://”之前的内容。 </p> <p> <span class="uicontrol"> FTP用户名 </span>  — 指定FTP帐户的名称。 </p> <p> <span class="uicontrol"> FTP密 </span> 码 — 指定FTP帐户的密码。 </p> <p> <span class="uicontrol"> FTP文件名 </span>  — 指定要传输的文件的名称。如果源生成多个文件，则此名称是模板，通常在名称末尾但扩展之前递增一个数字。 例如：basename.xml， basename1.xml， basename2.xml，.., basename-Nth.xml </p> <p> <span class="uicontrol"> FTP目 </span> 录 — 如果需要特定目录路径，请在此处输入。不要在路径中包含文件名。 </p> </li> 
          <li id="li_181268A7EE40456CA1DB768E8C66EEB9"> <span class="uicontrol"> 托管内容网络  </span> <p>托管内容网络是从网站搜索/销售的Web服务器提供文件的方式。 源的收件人使用HTTP请求将其从Web服务器中提取。 设置此设置的唯一信息是<span class="uicontrol">内容网络文件名</span>。 文件名是所提供文件的基名。 仅使用文件扩展名的文件名。 
            <!--Depending on the feed, the file name is a template for multiple files where the feed might generate multiple files in the following format: basename.xml, basename1.xml, basename2.xml, ..., basename-Nth.xml. --> </p> <p>输入基本文件名并成功保存源后，向导的“验证”面板上将显示“内容网络”文件的URL。 URL在源成功处理后变为活动状态。 供应商可以从此URL获取源数据。 </p> </li> 
          </ul> </li> 
        <li id="li_4DF56FA607A7479296CDA042A63C5A2C"> <p> <b>保留选项卡？</b> </p> <p>在信息源中保持制表符字符。 </p> </li> 
        </ul> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>4 </p> </td> 
      <td colname="col2"> <p>验证 </p> </td> 
      <td colname="col3"> <p>当您进入<span class="wintitle">验证</span>面板时，将保存您的源。 但是，实际的源文件直到以后才会保存。 </p> <p>通过<span class="wintitle">验证</span>面板，可以执行以下操作： </p> 
        <ul id="ul_7420C415987448A796DD979CF5FA2EB6"> 
        <li id="li_AF02E8609B7B4F20A01AF4E010308E15"> <span class="uicontrol"> 数据视图  </span> <p>允许您单击链接，通过表格中显示的数据视图检查源输出。 数据视图还可以帮助您排除故障，方法是显示选择了哪些元字段，以及向导中<span class="wintitle">搜索条件</span>面板中的任何指定搜索条件如何影响源输出。 数据视图是动态生成的，因此始终可用。 </p> </li> 
        <li id="li_32CEB8885C184354BFA1773BA66DB7A7"> <span class="uicontrol"> 源文件  </span> <p>在站点搜索/促销服务器生成源文件后，您可以使用<span class="uicontrol">源文件</span>下拉列表从服务器视图文件。 将显示新的浏览器选项卡或新的浏览器窗口，其中包含源的内容。 此方法有助于解决格式问题的源。 请注意，您不会从最终目标或供应商自己视图文件。 </p> <p> 如果源是新的，则下拉列表为空，直到您生成源文件。 </p> </li> 
        <li id="li_8D1B876B0EC2455C8654EC573EC53FA9"> <span class="uicontrol"> 内容网络链接  </span> <p>如果在向导的<span class="wintitle">文件提交</span>面板中选择<span class="uicontrol">托管内容网络</span>作为上传方法，则此处将显示URL。 如果尚未生成任何源文件，则在成功生成源之前，URL无效。 </p> </li> 
        </ul> </td> 
      </tr> 
    </tbody> 
    </table>

   **Google Merchant Center**

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>面板 </p> </th> 
      <th colname="col2" class="entry"> <p>向导面板名称 </p> </th> 
      <th colname="col3" class="entry"> <p>描述 </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>1 </p> </td> 
      <td colname="col2"> <p>馈送名称 </p> </td> 
      <td colname="col3"> <p>指定源的名称。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>2 </p> </td> 
      <td colname="col2"> <p>字段映射 </p> </td> 
      <td colname="col3"> <p>允许您将特定于供应商的源字段映射到站点搜索/销售元数据字段。 向导中的此映射步骤很重要，因为它允许源关联索引中的字段与源数据中的字段之间的信息。 在大多数情况下，除<span class="wintitle">通用源</span>之外，关联将保存在动态生成的搜索模板中。 </p> <p>“字段映射”表中的每一行都表示字段映射。 在表的<span class="wintitle">添加/删除</span>列中，单击<span class="uicontrol"> + </span>以添加新字段映射行；单击<span class="uicontrol"> - </span>从表中删除当前选定的字段映射行。 要将源字段与网站搜索/促销元数据字段关联，请使用相应的下拉列表选择所需的字段。 </p> <p> <b>高级使用</b> </p> <p>您可以创建自己的自定义字段。 在<span class="wintitle">源字段</span>下拉列表中，单击<span class="uicontrol">自定义</span>。 在关联的文本字段中，输入该字段的自定义标记名称。 如果源需要特定于供应商的特殊字段，则此自定义选项很有用。 </p> <p>您还可以创建自定义元数据字段。 在<span class="wintitle">元数据字段</span>下拉列表中，单击<span class="uicontrol">自定义</span>。 在关联的文本字段中，输入自定义元数据字段值。 该值将插入预生成的模板中，并且还可用于插入自定义搜索模板标记。 </p> <p>请参阅<a href="../c-appendices/c-templates.md#reference_F7AA3FF602314E42842BBC740D2CA1A4" type="reference" format="dita" scope="local">搜索模板标记</a>。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>3 </p> </td> 
      <td colname="col2"> <p>搜索条件 </p> </td> 
      <td colname="col3"> <p>当生成源文件时，使用搜索查询来过滤数据。 您可以在此面板中定义用于搜索查询的过滤器。 </p> 
        <ul id="ul_8179321A58BB4C72B0CDB2B2BEC58FE4"> 
        <li id="li_9F8008A2398A4667B106BC49C94E5E3E"> <span class="uicontrol"> 元字段  </span> <p>定义要筛选的元数据字段。 </p> <p> <b>高级使用</b> </p> <p>由于筛选系统是标准的搜索查询，您可以从下拉列表中选择<span class="uicontrol">自由格式</span>以输入CGI搜索参数及其值。 需要URL转义。 将忽略搜索参数<span class="codeph"> sp_q </span>。 您可以创建多行自由表单文本框。 在每行之间，参数将自动用&amp;'s分隔。 </p> <p>请参阅<a href="../c-appendices/c-cgiparameters.md#reference_DA27A8B0728246DA94994885E1353890" type="reference" format="dita" scope="local">搜索CGI参数</a>。 </p> </li> 
        <li id="li_50C9CE59E9E5418895F8C1A070560063"> <span class="uicontrol"> 标准 </span> <p>定义筛选操作。 您从下拉列表中选择的筛选器操作将应用在第三列中输入的常量值。 </p> </li> 
        <li id="li_9F86D0F5010046A4A9F93DBA5FB158B3"> <span class="uicontrol"> 值 </span> <p>常量值。 </p> </li> 
        <li id="li_1051AFD5AEA447D0AF5FAB305E1D1E64"> <span class="uicontrol"> 操作 </span> <p>添加新的字段映射行，或删除当前突出显示的行。 </p> </li> 
        </ul> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>4 </p> </td> 
      <td colname="col2"> <p>文件提交 </p> </td> 
      <td colname="col3"> <p>允许您配置提交源文件的计划，并设置要用于上传文件的方法。 </p> 
        <ul id="ul_A6A3C333AADD4438B835BF3E16E2AEFF"> 
        <li id="li_FCC4DAF198E149278B5CFB870CB6218C"> <span class="uicontrol"> 计划 </span> <p>设置提交源的最大频率。 选择<span class="uicontrol">从不</span>将关闭源。 其他值定义了馈送在再次提交之前等待的时段。 在每个索引上决定何时提交源。 换句话说，在索引的末尾，将检查源以查看它是否已过期，并且需要由供应商更新和提交。 此外，它还用作防止帐户过度提交给供应商的方法。 某些供应商针对上传频率过高的数据源制定了策略。 请务必检查供应商有关提交频率的政策。 </p> <p> 
          <!--The time of the last upload and the status of the upload feed is displayed here. If any other feeds are currently running, their status appears here instead. Each account processes one feed at a time. --> </p> <p> 
          <!--Click <uicontrol>Manual Upload</uicontrol> to generate the feed and push the files to the final destination. Any schedule restrictions that you have already set are ignored. --> </p> <p> 
          <!--If <uicontrol>Manual Upload</uicontrol> is dimmed (inactive), the account is currently processing this feed or another feed. An account only works with one feed at a time. --> </p> </li> 
        <li id="li_2D9ECAFB8E8544D39B486F7BC3DCE589"> <span class="uicontrol"> 上载方法  </span> <p>大多数源有两种分发文件的方式：FTP和托管内容网络。 </p> <p>用于提交数据馈送的建议上载方法是<span class="uicontrol"> FTP </span>。 Google Merchant Center为此托管FTP服务器。 请参阅Google商家中心帮助，了解如何为此Google产品搜索源设置单独的Google FTP帐户。 </p> 
          <ul id="ul_BC0D8B541068407883CAC948496DBD0A"> 
          <li id="li_DB28CA23C94A4AF09E1A0EB06DF8F40C"> <span class="uicontrol">FTP</span> <p>网站搜索/销售服务器使用被动式FTP。 </p> <p>FTP是将文件推送到另一台服务器的唯一方式。 </p> <p> <span class="uicontrol"> FTP服 </span> 务器 — 指定FTP服务器的名称。在这种情况下， 
            <code>
              uploads.google.com 
            </code>。 请勿包含协议或“ftp://”之前的内容。 </p> <p> <span class="uicontrol"> FTP用户名 </span>  — 指定FTP帐户的名称。 </p> <p> <span class="uicontrol"> FTP密 </span> 码 — 指定FTP帐户的密码。 </p> <p> <span class="uicontrol"> FTP文件名 </span>  — 指定要传输的文件的名称。如果源生成多个文件，则此名称是模板，通常在名称末尾但扩展之前递增一个数字。 例如：basename.xml， basename1.xml， basename2.xml，.., basename-Nth.xml </p> <p> <span class="uicontrol"> FTP目 </span> 录 — 如果需要特定目录路径，请在此处输入。不要在路径中包含文件名。 </p> </li> 
          <li id="li_5990927146434DAF89273F4636D21437"> <span class="uicontrol"> 托管内容网络  </span> <p>“内容网络”是从网站搜索/销售的Web服务器提供文件的方式。 源的收件人使用HTTP请求将其从Web服务器中提取。 </p> <p> 
            <!--After the base filename is entered and the feed is successfully saved, the URL of the Content Network file is displayed on the Verification panel of the wizard. The URL becomes active after the feed is successfully processed. The vendor can get the feed data from this URL. Multiple files use the same URL path. However, be sure that you replace or change the filename according to the enumeration scheme. --> </p> </li> 
          </ul> </li> 
        </ul> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>5 </p> </td> 
      <td colname="col2"> <p>验证 </p> </td> 
      <td colname="col3"> <p>当您进入<span class="wintitle">验证</span>面板时，将保存您的源。 但是，实际的源文件直到以后才会保存。 </p> <p>通过<span class="wintitle">验证</span>面板，可以执行以下操作： </p> 
        <ul id="ul_4A94355A8DF840A3BAF6BD5E9F11C27F"> 
        <li id="li_825697CB36B34C4AB5959B15EDDB55F1"> <span class="uicontrol"> 数据视图  </span> <p>允许您单击链接，通过表格中显示的数据视图检查源输出。 数据视图还可以帮助您排除故障，方法是显示选择了哪些元字段，以及向导中<span class="wintitle">搜索条件</span>面板中的任何指定搜索条件如何影响源输出。 数据视图是动态生成的，因此始终可用。 </p> </li> 
        <li id="li_91B8B5F5F9DE4A13863CD62F74AA6206"> <span class="uicontrol"> 源文件  </span> <p>在站点搜索/促销服务器生成源文件后，您可以使用<span class="uicontrol">源文件</span>下拉列表从服务器视图文件。 将显示新的浏览器选项卡或新的浏览器窗口，其中包含源的内容。 此方法有助于解决格式问题的源。 请注意，您不会从最终目标或供应商自己视图文件。 </p> <p> 如果源是新的，则下拉列表为空，直到您生成源文件。 </p> </li> 
        <li id="li_4A5EC089628E43029A38F8919888FF0A"> <span class="uicontrol"> 内容网络链接  </span> <p>如果在向导的<span class="wintitle">文件提交</span>面板中选择<span class="uicontrol">托管内容网络</span>作为上传方法，则此处将显示URL。 如果尚未生成任何源文件，则在成功生成源之前，URL无效。 </p> </li> 
        </ul> </td> 
      </tr> 
    </tbody> 
    </table>

   **Google站点地图**

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>面板 </p> </th> 
      <th colname="col2" class="entry"> <p>向导面板名称 </p> </th> 
      <th colname="col3" class="entry"> <p>描述 </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>3 </p> </td> 
      <td colname="col2"> <p>馈送名称 </p> </td> 
      <td colname="col3"> <p>指定源的名称。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>2 </p> </td> 
      <td colname="col2"> <p>字段映射 </p> </td> 
      <td colname="col3"> <p>允许您将特定于供应商的源字段映射到站点搜索/销售元数据字段。 向导中的此映射步骤很重要，因为它允许源关联索引中的字段与源数据中的字段之间的信息。 在大多数情况下，除<span class="wintitle">通用源</span>之外，关联将保存在动态生成的搜索模板中。 </p> <p>“字段映射”表中的每一行都表示字段映射。 在表的“添加/删除”列中，单击<span class="uicontrol"> + </span>以添加新字段映射行；单击<span class="uicontrol"> - </span>从表中删除当前选定的字段映射行。 要将源字段与元数据字段关联，请使用相应的下拉列表选择所需的字段。 </p> <p> <b>高级使用</b> </p> <p>您可以创建自己的自定义字段。 在<span class="wintitle">源字段</span>下拉列表中，单击<span class="uicontrol">自定义</span>。 在关联的文本字段中，输入该字段的自定义标记名称。 如果源需要特定于供应商的特殊字段，则此自定义选项很有用。 </p> <p>您还可以创建自定义元数据字段。 在<span class="wintitle">元数据字段</span>下拉列表中，单击<span class="uicontrol">自定义</span>。 在关联的文本字段中，输入自定义元数据字段值。 该值将插入预生成的模板中，并且还可用于插入自定义搜索模板标记。 </p> <p>请参阅<a href="../c-appendices/c-templates.md#reference_F7AA3FF602314E42842BBC740D2CA1A4" type="reference" format="dita" scope="local">搜索模板标记</a>。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>1 </p> </td> 
      <td colname="col2"> <p>搜索条件 </p> </td> 
      <td colname="col3"> <p>当生成源文件时，使用搜索查询来过滤数据。 您可以在此面板中定义用于搜索查询的过滤器。 </p> 
        <ul id="ul_994585E89A044BD3A89A99D30F277432"> 
        <li id="li_61FA9246B9824E3C8124958C8EBFF0DA"> <span class="uicontrol"> 元字段  </span> <p>定义要筛选的元数据字段。 </p> <p> <b>高级使用</b> </p> <p>由于筛选系统是标准的搜索查询，您可以从下拉列表中选择<span class="uicontrol">自由格式</span>以输入CGI搜索参数及其值。 需要URL转义。 将忽略搜索参数<span class="codeph"> sp_q </span>。 您可以创建多行自由表单文本框。 在每行之间，参数将自动用&amp;'s分隔。 </p> <p>请参阅<a href="../c-appendices/c-cgiparameters.md#reference_DA27A8B0728246DA94994885E1353890" type="reference" format="dita" scope="local">搜索CGI参数</a>。 </p> </li> 
        <li id="li_A5D00883738845C8B8F612A7521F160F"> <span class="uicontrol"> 标准 </span> <p>定义筛选操作。 您从下拉列表中选择的筛选器操作将应用在第三列中输入的常量值。 </p> </li> 
        <li id="li_5A312C2984454C2CB518CA453AD9F6D2"> <span class="uicontrol"> 值 </span> <p>常量值。 </p> </li> 
        <li id="li_666AAE1BC7A2432E91953B08EC7394DC"> <span class="uicontrol"> 操作 </span> <p>添加新的字段映射行，或删除当前突出显示的行。 </p> </li> 
        </ul> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>4 </p> </td> 
      <td colname="col2"> <p>文件提交 </p> </td> 
      <td colname="col3"> <p>允许您配置提交源文件的计划，并设置要用于上传文件的方法。 </p> 
        <ul id="ul_49B3255BE669424B925BBAEE4C9B385F"> 
        <li id="li_939828C774D440EBB0769F6D5B0BBA23"> <span class="uicontrol"> 计划 </span> <p>设置提交源的最大频率。 选择<span class="uicontrol">从不</span>将关闭源。 其他值定义了馈送在再次提交之前等待的时段。 在每个索引上决定何时提交源。 换句话说，在索引的末尾，将检查源以查看它是否已过期，并且需要由供应商更新和提交。 此外，它还用作防止帐户过度提交给供应商的方法。 某些供应商针对上传频率过高的数据源制定了策略。 请务必检查供应商有关提交频率的政策。 </p> <p> 
          <!--The time of the last upload and the status of the upload feed is displayed here. If any other feeds are currently running, their status appears here instead. Each account processes one feed at a time. --> </p> <p> 
          <!--Click <uicontrol>Manual Upload</uicontrol> to generate the feed and push the files to the final destination. Any schedule restrictions that you have already set are ignored. --> </p> <p> 
          <!--If <uicontrol>Manual Upload</uicontrol> is dimmed (inactive), the account is currently processing this feed or another feed. An account only works with one feed at a time. --> </p> </li> 
        <li id="li_07B5BCF7936241A7915C4898B231184B"> <span class="uicontrol"> 上载方法  </span> <p>大多数源有两种分发文件的方式：FTP和托管内容网络。 </p> 
          <ul id="ul_74FA98A82754469BA5FADCC63FC364F7"> 
          <li id="li_02940B712D6444A8B65C0A51834187E6"> <span class="uicontrol">FTP</span> <p>网站搜索/销售服务器使用被动式FTP。 </p> <p>FTP是将文件推送到另一台服务器的唯一方式。 </p> <p> <span class="uicontrol"> FTP服 </span> 务器 — 指定FTP服务器的名称。请勿包含协议或“ftp://”之前的内容。 </p> <p> <span class="uicontrol"> FTP用户名 </span>  — 指定FTP帐户的名称。 </p> <p> <span class="uicontrol"> FTP密 </span> 码 — 指定FTP帐户的密码。 </p> <p> <span class="uicontrol"> FTP文件名 </span>  — 指定要传输的文件的名称。如果源生成多个文件，则此名称是模板，通常在名称末尾但扩展之前递增一个数字。 例如：basename.xml， basename1.xml， basename2.xml，.., basename-Nth.xml </p> <p> <span class="uicontrol"> FTP目 </span> 录 — 如果需要特定目录路径，请在此处输入。不要在路径中包含文件名。 </p> </li> 
          <li id="li_EAE504436CD84452BA04BE51855A2BEF"> <span class="uicontrol"> 托管内容网络  </span> <p>“内容网络”是从网站搜索/销售的Web服务器提供文件的方式。 源的收件人使用HTTP请求将其从Web服务器中提取。 </p> <p> 
            <!--After the base filename is entered and the feed is successfully saved, the URL of the Content Network file is displayed on the Verification panel of the wizard. The URL becomes active after the feed is successfully processed. The vendor can get the feed data from this URL. Multiple files use the same URL path. However, be sure that you replace or change the filename according to the enumeration scheme. --> </p> </li> 
          </ul> </li> 
        </ul> <p>请注意，上传方法中的任一方法都要求您在<span class="wintitle">主Sitemap URL </span>字段中指定Google用于检索Sitemap的URL。 此处也确定了sitemap文件的名称。 如果您的sitemap很大，则可能存在多个文件，命名约定是在以数字1开始的文件末尾附加一个索引号。 第一个文件或索引文件没有索引，如<span class="codeph"> sitemap.xml </span>、<span class="codeph"> sitemap1.xml </span>、<span class="codeph"> sitemap2.xml </span>.. <span class="codeph"> sitemap12.xml </span>中所示。 </p> <p>如果选择<span class="uicontrol">托管内容网络</span>作为上传方法，则文件的URL具有相同的文件名，但URL具有托管服务的路径和主机名。 因此，您将Sitemap请求重定向到托管内容网络。 您也应该能够从同一位置提取文件。 </p> <p>在创建源文件并将其提交到中间目标后，Google将被ping通，并让他们知道Sitemap源已就绪。 </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>5 </p> </td> 
      <td colname="col2"> <p>验证 </p> </td> 
      <td colname="col3"> <p>当您进入<span class="wintitle">验证</span>面板时，将保存您的源。 但是，实际的源文件直到以后才会保存。 </p> <p>通过<span class="wintitle">验证</span>面板，可以执行以下操作： </p> 
        <ul id="ul_A1D889A84972419599FC83F39EA2676A"> 
        <li id="li_C8ED077B6DD1461E85A4914C1CFDBE88"> <span class="uicontrol"> 数据视图  </span> <p>允许您单击链接，通过表格中显示的数据视图检查源输出。 数据视图还可以帮助您排除故障，方法是显示选择了哪些元字段，以及向导中<span class="wintitle">搜索条件</span>面板中的任何指定搜索条件如何影响源输出。 数据视图是动态生成的，因此始终可用。 </p> </li> 
        <li id="li_DACEE40703AF40EFBCD90D43825CE9C1"> <span class="uicontrol"> 源文件  </span> <p>生成源文件后，您可以使用<span class="uicontrol">源文件</span>下拉列表从服务器视图文件。 将显示新的浏览器选项卡或新的浏览器窗口，其中包含源的内容。 此方法有助于解决格式问题的源。 请注意，您不会从最终目标或供应商自己视图文件。 </p> <p> 如果源是新的，则下拉列表为空，直到您生成源文件。 </p> </li> 
        <li id="li_1C530354B4F34EC79D92CEFEB5B39ED7"> <span class="uicontrol"> 内容网络链接  </span> <p>如果在向导的<span class="wintitle">文件提交</span>面板中选择<span class="uicontrol">托管内容网络</span>作为上传方法，则此处将显示URL。 如果尚未生成任何源文件，则在成功生成源之前，URL无效。 </p> </li> 
        </ul> </td> 
      </tr> 
    </tbody> 
    </table>

1. 完成向导中的步骤后，单击&#x200B;**[!UICONTROL Close]**。

## 编辑源{#task_B855D28CD99B4FA58E2D4D4FD6DC9CEB}

您可以编辑现有源的配置。

<!-- 

t_editing_a_feed.xml

 -->

>[!NOTE]
>
>编辑源时，无法更改源类型。 如果您需要更改源类型，请删除现有源，然后添加具有所需类型的新源。

请参阅[删除源](../c-about-settings-menu/c-about-searching-menu.md#task_7E39A140E69D43C6B61FB42E81051269)。

**编辑源**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Feeds]**。
1. 执行以下操作之一：

* 在[!DNL Feeds]页面的表的[!DNL Name]列下，单击源名称旁的下拉列表，然后单击&#x200B;**[!UICONTROL Edit feed]**。

* 在[!DNL Feeds]页面的[!DNL Name]列下，单击要更改的源的名称。

1. 在源向导中，为向导中的每个面板设置所需的选项。

   请参阅&#x200B;**添加源**&#x200B;下的选项表。
1. 在向导的末尾，在[!DNL Verification]面板中，单击&#x200B;**[!UICONTROL Close]**。

## 删除源{#task_7E39A140E69D43C6B61FB42E81051269}

您可以删除不再需要或使用的源。

<!-- 

t_deleting_a_feed.xml

 -->

**删除源**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Feeds]**。
1. 在[!DNL Feeds Menu]屏幕的[!DNL Actions]列下，单击&#x200B;**[!UICONTROL Delete]**&#x200B;以获取要删除的源名称。
1. 在[!DNL Delete feed]对话框中，单击&#x200B;**[!UICONTROL Yes]**&#x200B;以确认删除。

## 查看源文件{#task_1E413C7650DE466EA68925F72E086884}

您可以转到“源”向导的最后一个面板，以便您能够快速访问以查看源的数据视图，或从服务器下载任何当前源文件。 如果要验证和检查源输出，此功能很有帮助。

<!-- 

t_viewing_feed_files.xml

 -->

**视图源文件**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Feeds]**。
1. 在[!DNL Feeds]页面的表的[!DNL Name]列下，单击源名称旁的下拉列表，然后单击&#x200B;**[!UICONTROL View Feed Files]**。
1. 在源向导的[!DNL Verification]面板中，单击&#x200B;**[!UICONTROL Show Data View]**。
1. 单击 **[!UICONTROL Close]**.

## 测试没有文件上载{#task_F1F390F72E0A4886B6CD4CD86EDB4C8C}的源

您可以测试源，而无需将文件上传到最终目标。

<!-- 

t_testing_a_feed_with_no_file_upload.xml

 -->

**测试不上载文件的源**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Feeds]**。
1. 在[!DNL Feeds]页面的表的[!DNL Name]列下，单击源名称旁的下拉列表，然后单击&#x200B;**[!UICONTROL Test Feed (No file upload)]**。
1. 在[!DNL Feeds]页面上，测试期间和测试后将更新[!DNL Feed Status]列。

## 生成并上传源{#task_C9A57827C7674035B62A22D310DDAA0C}

无论在“源”向导的[!DNL File Submission]面板中设置了何种计划，您都可以手动生成源文件并将其提交到最终目标。

<!-- 

t_generating_and_uploading_a_feed.xml

 -->

另请参阅[创建源](../c-about-settings-menu/c-about-searching-menu.md#task_63179C1FC359497483CD6CE13FD1C250)。

**要生成并上传源，请执行以下操作**

1. 在产品菜单上，单击&#x200B;**[!UICONTROL Settings]** > **[!UICONTROL Searching]** > **[!UICONTROL Feeds]**。
1. 在[!DNL Feeds]页面的表的[!DNL Name]列下，单击源名称旁的下拉列表，然后单击&#x200B;**[!UICONTROL Generate and Upload Feed]**。
1. 在[!DNL Feeds]页面上，[!DNL Feed Status]列在生成和上传数据馈送期间和之后进行更新。
