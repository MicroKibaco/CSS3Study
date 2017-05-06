># CSS3入门与实践
## 选择器

###### A. CSS选择器
1. 类选择器
2. ID选择器
3. 后代选择器
4. 通配符选择器
5. 元素选择器

###### B. CSS3新增选择器

1. 子元素选择器
2. 相邻元素选择器
3. 通用兄弟选择器
4. 群组选择器
5. 属性选择器

| CSS3新增选择器     | 概念 | 语法格式   | 兼容性   |举个栗子   |
| :------- | ----: | :---: |:---: |:---: |
| 子元素选择器 | 子元素选择器只能选择某元素的子元素 |  父元素 > 子元素 (Father > Children)   |IE8+、FireFox、Chrome、Safari、Opera    |[子元素选择器](../selector/child.html)  |
| 相邻元素选择器    | 相邻兄弟选择器可以选择紧接在另一元素后的元素,而且他们具有一个相同的父元素   |  元素 + 兄弟相邻元素 (Eelement + Sibling)   |IE8+、FireFox、Chrome、Safari、Opera   |[相邻元素选择器](../selector/sibiling.html)   |
| 通用兄弟选择器     | 选择某元素后面的所有兄弟元素,而且他们具有一个相同的父元素   |  元素 ~ 后面所有兄弟相邻元素 (Eelement ~ Siblings)  |IE8+、FireFox、Chrome、Safari、Opera  |[通用兄弟选择器](../selector/sibilings.html)  |
| 群组选择器     | 选择某元素后面的所有兄弟元素,而且他们具有一个相同的父元素    |  元素1, 元素2, ..., 元素n (Eelement1, Element2, ..., Elementn)  |IE6+、FireFox、Chrome、Safari、Opera  |[群组选择器](../selector/group.html)   |
| 属性选择器     | 对带有指定属性的HTML 元素设置样式    |  使用CSS3属性选择器,你可以只指定元素的某个属性,或者你还可以同时指定元素的某个属性和 其对应的属性值。  |IE8+、FireFox、Chrome、Safari、Opera  |[属性选择器](../selector/Attribute.html)   |