---
title: 清洗加工数据
date: '2019-09-18'
linkTitle: /post/tidyverse/
source: 楚新元个人主页
description: |-
  <p>9月份初，因为人行LPR的事情，帮着原单位同事做了点数据处理。如今我已习惯了用代码来处理数据，而不是Excel，当然写文档和做幻灯片（PPT仅仅是微软的幻灯片生成工具，我更喜欢叫幻灯片）也喜欢在RStudio中利用Rmarkdown中完成。对于少量非重复性的工作，用Excel或许是合适的，但是对于数据量达到上万行甚至上百万行的时候，Excel运行起来就很吃力了，更重要的是通过鼠标点击操纵Excel得到结果没有记录数据处理的整个过程，下次要想得到同样的结果还得重新理清思路然后一顿点点点，费时费力，而通过写代码处理数据就不会存在上面的问题，虽然学习写代码需要花费一定的时间。在我看来写代码处理数据至少有以下几个方面的好处:</p> <ul>
  <li><p>通过代码得到的结果可行度更好，出错的可能性基本为0，除非表结构变了，或者调用的包版本更新了，而你没有及时更新代码。</p></li> <li><p>通过写代码可以保证结果的可重复性，无论任何时候，只要原始数据还在，重新运行下代码即可获得同样的结果。</p></li> <li><p>代码记录了数据获取、清洗、加工、建模、可视化、生成报告的整个过程，一气呵成，减少了各个软件之间复制粘贴切换，思路不容易被打断，只专注于业务本身。</p></li> ...
disable_comments: true
---
<p>9月份初，因为人行LPR的事情，帮着原单位同事做了点数据处理。如今我已习惯了用代码来处理数据，而不是Excel，当然写文档和做幻灯片（PPT仅仅是微软的幻灯片生成工具，我更喜欢叫幻灯片）也喜欢在RStudio中利用Rmarkdown中完成。对于少量非重复性的工作，用Excel或许是合适的，但是对于数据量达到上万行甚至上百万行的时候，Excel运行起来就很吃力了，更重要的是通过鼠标点击操纵Excel得到结果没有记录数据处理的整个过程，下次要想得到同样的结果还得重新理清思路然后一顿点点点，费时费力，而通过写代码处理数据就不会存在上面的问题，虽然学习写代码需要花费一定的时间。在我看来写代码处理数据至少有以下几个方面的好处:</p> <ul>
<li><p>通过代码得到的结果可行度更好，出错的可能性基本为0，除非表结构变了，或者调用的包版本更新了，而你没有及时更新代码。</p></li> <li><p>通过写代码可以保证结果的可重复性，无论任何时候，只要原始数据还在，重新运行下代码即可获得同样的结果。</p></li> <li><p>代码记录了数据获取、清洗、加工、建模、可视化、生成报告的整个过程，一气呵成，减少了各个软件之间复制粘贴切换，思路不容易被打断，只专注于业务本身。</p></li> ...