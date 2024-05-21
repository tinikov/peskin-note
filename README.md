# QFT note

Peskin & Schroeder QFT 中文笔记（持续缓慢更新中）

若无法编译，请下载导言区`设置字体`中的字体，或将导言区的`设置字体`项注释掉。思源系列字体可以在 Adobe Fonts 的[思源黑体仓库][note:siyuanheiti]以及[思源宋体仓库][note:siyuansongti]中下载。

## 简介

基于 _An Introduction to Quantum Field Theory - Peskin & Schroeder_ 一书的量子场论笔记。

这篇笔记主要对 Peskin & Schroeder 书中正文部分一些复杂（或不太复杂）的计算和难以理解（指我不理解）的段落作了注释，同时根据研究生课程内容对部分较为简略的段落添加了补充说明，希望对场论的初学者（比如说我）有一定的参考意义。由于内容较为困难，故此笔记以中文呈现。<del>若后有闲暇，可能翻译为英文。</del>

一些推导和理解参考了[这篇笔记][note:peskinbysomeone]（谢谢你, 陌生人）以及 [Yuchen Wang][note:wycblog] (非常厉害的一个人！)的 [笔记][note:newqft]。同时感谢朋友 Starry 的增补及校对。

如发现任何错误或遗漏，或希望与我讨论书中的内容，欢迎通过[邮件](mailto:tinikov137@gmail.com)与我联系。

我的邮箱: tinikov137@gmail.com

## 自定义命令

```latex
\HRule    % 长横线
\cemph{}  % 中文着重号

\begin{mybox}{title}  % 评论、注等使用的方框
\end{mybox}

% 无标号 chapter, section, subsection
\nonumchap{}
\nonumchapkphdr{}  % (保持页眉页脚格式)
\nonumsec{}
\nonumseckphdr{}   % (保持页眉页脚格式)
\nonumssec{}
```

## 样式风格

- 除双引号（“”）外，使用英文标点。
- 在 tex 源文件中，每句话后换行。
- 强调内容时，使用 `\textbf{}` 或 `\cemph{}`。

[note:siyuanheiti]: https://github.com/adobe-fonts/source-han-sans
[note:siyuansongti]: https://github.com/adobe-fonts/source-han-serif
[note:peskinbysomeone]: http://gamebm.shoutwiki.com/wiki/Lecture_Notes_of_An_Introduction_to_Quantum_Field_Theory_by_M._Peskin_and_D._Schroeder
[note:newqft]: https://yuchenw.blog/qft-notes
[note:wycblog]: https://yuchenw.blog
