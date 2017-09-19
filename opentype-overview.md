# OpenType 概览

OpenType 是 TrueType 的扩展，在其之上增加了对 PostScript 的支持。OpenType 字体格式由 Microsoft 和 Adobe 共同开发。在支持 OpenType 字体的系统上，用户可以方便地安装和使用 TrueType 轮廓或者 CFF (PostScript) 轮廓的字体。

设计 OpenType 字体格式有以下几个目标：
* 支持多平台
* 为多种国际化字符集提供更好的支持
* 更好地保护字体数据
* 减小字体文件大小，以更高效地分发字体文件
* 为高级文字排版特性提供支持

OpenType 字体通常指 TrueType Open 2.0 字体，因为它们都使用了 TrueType 的名「sfnt」的字体文件格式。OpenType 中的 PostScript 数据可以被根据宿主操作系统上安装的光栅化引擎直接转换为 TrueType 轮廓格式——这些对于用户来说都是透明的，用户不用去关心 OpenType 中的轮廓数据是用哪种格式表示的。同样，字体设计者也可以使用最适合他们的轮廓格式，而不用担心功能受到限制。

OpenType 字体包含 OpenType 布局表，其允许字体设计者可以设计出更好的国际化支持的高端字体。OpenType 布局表包含了诸如字符替换、字符定位、齐行、基线定位等信息，这些信息可以改善字处理软件的文字布局。

与 TrueType 字体相比，OpenType 可以处理 Unicode 编码的大规模字符集，以提供更加广泛的国际化支持和字符的排版变体。

值得一提的是，OpenType 字体中可以包含数字签名，这使得操作系统和浏览器程序可以验证字体文件的来源和完整性。字体设计者还可以把嵌入限制（embedding restrictions）编码进 OpenType 字体中。如果字体的开发者是经过签名的，字体中的这些限制将不能被更改。

## 相关文献

下面这些文献可以提供更多有用的信息：
* Adobe Technical Note #5176: “The Compact Font Format Specification.”
* Adobe Technical Note #5177: “Type 2 Charstring Format.”
* TrueType 1.0 Font Files, Technical Specification. Microsoft.
* OpenType Layout Font Specification. Microsoft.
* Adobe Type 1 Font Format. *Addison Wesley, 1991*; ISBN 0-201-57044-0.
* Technical Note #5015: “The Type 1 Font Format Supplement.” *This document contains all updates to the Type 1 format.*
* Adobe Technical Note #5087: “Multiple Master Font Programs for the Macintosh.”
* Adobe Technical Note #5088 “Font Naming Issues.” *This document discusses general font name issues.*
