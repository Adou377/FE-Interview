# Html题目汇总

- [meta 元素都有什么](#meta-元素都有什么)✅
- [script 的 async 跟 defer 的区别？](#script-的-async-跟-defer-的区别)✅
- [知道语义化吗？说说你理解的语义化，如果是你，平时会怎么做来保证语义化？说说你了解的 HTML5 语义化标签？](#知道语义化吗说说你理解的语义化如果是你平时会怎么做来保证语义化说说你了解的-html5-语义化标签)✅
- [a 标签默认事件禁掉之后做了什么才实现了跳转](#a-标签默认事件禁掉之后做了什么才实现了跳转)✅
- [网站 SEO 怎么处理](#网站-seo-怎么处理)✅
- [html 标签 b 和 strong 的区别](#html-标签-b-和-strong-的区别)✅
- [说一下减少 dom 数量的办法？一次性给你大量的 dom 怎么优化？](#说一下减少-dom-数量的办法一次性给你大量的-dom-怎么优化)✅
- [Html5 有哪些新特性？如何处理 Html5 新标签的浏览器兼容问题？如何区分 Html 和 Html5?](#html5-有哪些新特性如何处理-html5-新标签的浏览器兼容问题如何区分-html-和-html5)✅
- [请说明 Html 布局元素的分类有哪些？并描述每种布局元素的应用场景](#请说明-html-布局元素的分类有哪些并描述每种布局元素的应用场景)✅

### meta 元素都有什么 

公司：完美世界

分类：Html

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/364)
`<meta>` 元素用于在HTML文档的头部（`<head>`）中提供元信息（metadata）。元信息通常是与文档本身无关的数据，它们提供关于文档的信息，如字符编码、关键字、描述、作者等。以下是一些常见的 `<meta>` 元素属性及其含义：

1. `charset`：指定文档的字符编码。例如，`<meta charset="UTF-8">` 表示文档采用UTF-8字符编码，确保文档能够正确显示多语言字符。

2. `name` 和 `content`：用于指定各种文档元信息。常见的组合包括：
   - `<meta name="viewport" content="width=device-width, initial-scale=1">`：用于响应式网页设计，确保网页在移动设备上正确缩放和显示。
   - `<meta name="description" content="网页描述">`：提供关于网页内容的简短描述，用于搜索引擎结果中的显示。
   - `<meta name="keywords" content="关键词1, 关键词2, ...">`：指定与网页内容相关的关键字，用于搜索引擎的搜索优化。
   - `<meta name="author" content="作者姓名">`：指定网页的作者。

3. `http-equiv` 和 `content`：这对属性用于模拟HTTP头信息，通常用于控制文档的缓存和刷新。例如：
   - `<meta http-equiv="refresh" content="5;url=https://example.com/">`：表示浏览器将在5秒后自动刷新到指定URL。

4. `property` 和 `content`（Open Graph协议）：用于在社交媒体平台上共享网页时提供更多信息。例如：
   - `<meta property="og:title" content="页面标题">`：指定在社交媒体上显示的标题。
   - `<meta property="og:image" content="https://example.com/image.jpg">`：指定在社交媒体上显示的图片。

5. `name` 和 `content`（Twitter Cards）：类似于Open Graph协议，用于在Twitter上共享网页时提供信息。
   - `<meta name="twitter:card" content="summary">`：指定Twitter卡片类型。
   - `<meta name="twitter:site" content="@example">`：指定Twitter用户名。

6. `name` 和 `content`（移动设备相关）：用于指定移动设备的特定设置。
   - `<meta name="apple-mobile-web-app-capable" content="yes">`：用于将网页添加到iOS设备的主屏幕时以全屏模式打开。
   - `<meta name="theme-color" content="#RRGGBB">`：指定网页在Android设备的浏览器地址栏和任务切换器中的主题颜色。

7. `name` 和 `content`（搜索引擎相关）：用于指定搜索引擎的行为。
   - `<meta name="robots" content="index, follow">`：告诉搜索引擎是否应索引和跟随链接。
   - `<meta name="googlebot" content="noindex, nofollow">`：告诉Google的爬虫是否应索引和跟随链接。

这只是一些常见的 `<meta>` 元素属性，根据需求，你可以在网页的头部使用不同的元信息来指定文档的相关信息，从而实现不同的功能和效果。

<br/>

### script 的 async 跟 defer 的区别？

公司：虎扑

分类：Html

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/401)
`<script>` 标签的 `async` 和 `defer` 属性用于控制脚本的加载和执行方式，特别是在处理多个脚本文件时。

### 1. `async` 属性：

- **作用**：
  - `async` 表示脚本将异步加载（异步加载不阻止页面的解析和渲染）。
  - 适用于独立的脚本文件，不依赖于其他脚本执行的顺序。
  
- **加载时机**：
  - `async` 属性使得脚本在加载过程中不会阻塞页面的渲染。
  - 脚本的加载和执行是异步进行的，不会等到脚本加载完毕才执行后续代码。
  
- **执行时机**：
  - 脚本可能在页面的任何阶段执行，具体取决于加载完成的顺序和网络速度。

- **适用场景**：
  - 适用于那些不依赖于其他脚本，且可以在加载时立即执行的脚本。
  - 例如：用于加载并初始化一些独立的统计脚本或广告脚本。

### 2. `defer` 属性：

- **作用**：
  - `defer` 也表示脚本的异步加载，但它保证脚本的执行顺序按照它们在文档中的顺序来执行。
  - `defer` 会在文档解析完毕后，DOMContentLoaded 事件触发前依次执行。

- **加载时机**：
  - 与 `async` 类似，`defer` 也会异步加载脚本，不会阻塞页面的渲染。

- **执行时机**：
  - `defer` 脚本会在文档解析完毕后按照它们在文档中的顺序依次执行，但会在 `DOMContentLoaded` 事件触发前执行。

- **适用场景**：
  - 适用于那些依赖于其他脚本，且需要在文档解析完毕后执行的脚本。
  - 通常用于网页中多个脚本文件之间有依赖关系的情况，确保依赖的脚本在正确的顺序加载和执行。

### 总结：

- 如果脚本之间没有依赖关系，并且可以在加载完成后立即执行，可以使用 `async`。
- 如果脚本之间有依赖关系，需要保证按照顺序执行，可以使用 `defer`。

需要注意的是，尽管 `async` 和 `defer` 提供了异步加载脚本的方式，但仍然需要谨慎使用，特别是在涉及到依赖关系和页面行为的情况下，以避免出现意外的结果。

<br/>

### 知道语义化吗？说说你理解的语义化，如果是你，平时会怎么做来保证语义化？说说你了解的 HTML5 语义化标签？

公司：蘑菇街

分类：Html

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/379)
语义化是指使用HTML元素来传达文档的结构和内容的含义，使文档更易于理解和被搜索引擎、屏幕阅读器等工具解析。语义化的目标是通过正确选择HTML元素来清晰地表达文档的结构，而不仅仅是为了样式或布局。

为了保证语义化，通常会采取以下措施：

1. **选择正确的HTML元素**：使用适当的HTML元素来描述内容，如使用`<h1>`到`<h6>`表示标题，`<p>`表示段落，`<ul>`和`<ol>`表示列表等。

2. **避免滥用无语义的`<div>`和`<span>`**：尽量减少使用`<div>`和`<span>`来包裹内容，而是使用更具语义的元素。

3. **使用语义化的链接和按钮**：对于链接和按钮，使用`<a>`标签和`<button>`标签，分别表示超链接和按钮功能，而不仅仅依赖于`<div>`或`<span>`。

4. **添加适当的属性**：例如，对于`<img>`元素，使用`alt`属性提供替代文本，以便屏幕阅读器可以理解图像内容。

5. **使用表格标签表示表格**：如果需要表格，应该使用`<table>`、`<thead>`、`<tbody>`、`<tr>`、`<th>`和`<td>`等元素，而不是用`<div>`来模拟表格布局。

HTML5 引入了一些新的语义化标签，这些标签更好地描述了文档的结构。一些常见的 HTML5 语义化标签包括：

1. `<header>`：表示文档或节的页眉，通常包含标题、标志和导航。

2. `<nav>`：表示导航链接的区域，用于包含页面导航菜单。

3. `<main>`：表示文档的主要内容，每个文档应该只有一个`<main>`元素。

4. `<section>`：表示文档中的一个独立部分，通常有一个标题。

5. `<article>`：表示一个独立的、完整的内容块，如一篇新闻文章或一篇博客帖子。

6. `<aside>`：表示与周围内容相关但不是其主要内容的一部分，通常用于侧边栏或广告。

7. `<footer>`：表示文档或节的页脚，通常包含版权信息、联系方式等。

这些标签帮助开发者更清晰地表示文档的结构和内容，提高了文档的可访问性和可维护性。通过合理使用这些标签，可以使网页更容易理解，对搜索引擎和屏幕阅读器更友好。

<br/>

### a 标签默认事件禁掉之后做了什么才实现了跳转 

公司：滴滴

分类：Html

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/519)
当禁用了`<a>`标签的默认事件后，可以通过JavaScript来实现跳转。以下是一种常见的实现方式：

1. **获取`<a>`标签的引用**：使用JavaScript的DOM操作方法，如`document.getElementById()`或`document.querySelector()`，获取到目标`<a>`标签的引用。

2. **添加点击事件监听器**：使用`addEventListener()`方法，为目标`<a>`标签添加一个点击事件监听器。

3. **在事件处理函数中实现跳转**：在点击事件的处理函数中，使用`window.location.href`属性或`window.location.replace()`方法来实现跳转。例如，可以将`window.location.href`设置为目标URL，或使用`window.location.replace()`方法将当前页面替换为目标URL。

下面是一个示例代码：

```javascript
// 获取目标<a>标签的引用
var link = document.getElementById("myLink");

// 添加点击事件监听器
link.addEventListener("click", function(event) {
  // 阻止默认事件
  event.preventDefault();

  // 实现跳转
  window.location.href = "https://www.example.com";
});
```

在这个示例中，我们首先获取了ID为"myLink"的`<a>`标签的引用。然后，为该标签添加了一个点击事件监听器。在事件处理函数中，我们阻止了默认的跳转行为（即禁用了默认事件），然后使用`window.location.href`将页面跳转到指定的URL。

需要注意的是，禁用`<a>`标签的默认事件后，如果不进行跳转操作，用户可能无法通过点击链接进行页面跳转。因此，在实现自定义跳转逻辑时，需要确保提供了合适的替代方式，以保证用户体验的连贯性。

<br/>

### 网站 SEO 怎么处理 

公司：喜马拉雅

分类：Html

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/439)
进行网站SEO（搜索引擎优化）是为了提高网站在搜索引擎结果中的排名，增加有机流量。以下是一些详细的步骤和策略，帮助你处理网站SEO：

1. **关键词研究**：
   - 确定与你的网站内容相关的关键词和短语。
   - 使用关键词研究工具（如Google关键词规划工具）来找到潜在的高搜索量关键词。

2. **网站结构**：
   - 创建清晰的网站结构，确保每个页面都有一个明确的主题和目标关键词。
   - 使用语义化的HTML标记来描述内容的结构，如段落、标题、列表等。

3. **内容优化**：
   - 编写高质量、有价值的内容，满足用户需求。
   - 将目标关键词自然地包含在标题、段落、图片的alt文本等位置。
   - 使用内部链接将相关内容相互连接。

4. **元标记优化**：
   - 为每个页面设置有吸引力的元标题（Title）和元描述（Description），包含目标关键词。
   - 使用schema.org标记来标识特定内容类型，如产品、评论、文章等。

5. **页面速度**：
   - 优化页面加载速度，包括压缩图像、减少HTTP请求和使用CDN（内容分发网络）。
   - 使用响应式设计以确保适应各种设备。

6. **移动友好性**：
   - 确保网站在移动设备上的显示和导航良好，这对SEO和用户体验都很重要。

7. **外部链接**：
   - 获得高质量的外部链接，这有助于提高网站的权威性。
   - 避免使用不良的链接构建策略，以防止被搜索引擎降权。

8. **社交媒体**：
   - 利用社交媒体平台来推广你的内容，增加流量和链接。
   - 鼓励社交分享和互动。

9. **定期更新**：
   - 定期更新网站内容，添加新信息，以保持网站的新鲜度。
   - 创建博客或新闻页面，定期发布新内容。

10. **分析和改进**：
    - 使用工具如Google Analytics追踪网站流量和关键绩效指标。
    - 根据数据分析，调整和改进SEO策略。

11. **本地SEO**（适用于本地业务）：
    - 注册并优化Google My Business页面。
    - 确保网站包含准确的联系信息和地址。
    - 鼓励用户留下正面的本地评论。

12. **安全性**：
    - 使用HTTPS协议来加密数据传输，这不仅有益于SEO，也有助于网站安全。

继续关注搜索引擎算法的变化，学习最新的SEO趋势，并根据需要调整策略非常重要。SEO是一个长期的过程，需要耐心和持续的努力来取得良好的结果。

<br/>

### html 标签 b 和 strong 的区别 

公司：蘑菇街

分类：Html

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/766)

<br/>

### 说一下减少 dom 数量的办法？一次性给你大量的 dom 怎么优化 

公司：58

分类：Html

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/706)
HTML中的`<b>`和`<strong>`标签都用于强调文本，但它们在语义上有所不同。

1. `<b>`标签：
   - `<b>`标签是用于将文本设置为粗体显示，没有特定的语义含义。
   - 它主要用于样式上的强调，而不是为了强调文本的重要性或语义。
   - 搜索引擎对`<b>`标签的权重较低，不会将其视为重要的关键词。

2. `<strong>`标签：
   - `<strong>`标签用于将文本设置为粗体显示，并且具有语义上的强调作用。
   - 它表示文本的重要性、紧迫性或严重性。
   - 搜索引擎会将`<strong>`标签中的文本视为重要的关键词，有助于提高相关内容在搜索结果中的排名。

总结：
- 如果只是想将文本设置为粗体显示，而没有特定的语义含义，可以使用`<b>`标签。
- 如果希望强调文本的重要性或语义，同时将其设置为粗体显示，应该使用`<strong>`标签。

在实际应用中，建议根据文本的语义含义来选择合适的标签，以提高网页的可读性和语义化。

<br/>

### Html5 有哪些新特性？如何处理 Html5 新标签的浏览器兼容问题？如何区分 Html 和 Html5? 

分类：Html

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/676)
HTML5是HTML的第五个主要版本，引入了许多新特性和改进，以提供更强大的功能和更好的用户体验。以下是HTML5的一些主要新特性：

1. **语义化标签**：HTML5引入了一些新的语义化标签，如`<header>`、`<nav>`、`<section>`、`<article>`、`<footer>`等，使网页结构更清晰明了。

2. **多媒体支持**：HTML5提供了内置的多媒体支持，包括`<video>`和`<audio>`标签，使嵌入视频和音频更简单。

3. **Canvas绘图**：HTML5的`<canvas>`元素允许通过JavaScript进行动态绘图和图形处理，实现了更丰富的图形和动画效果。

4. **本地存储**：HTML5引入了本地存储机制，如`localStorage`和`sessionStorage`，使网页能够在客户端存储数据，提高性能和用户体验。

5. **表单增强**：HTML5为表单提供了一些新的输入类型（如日期、时间、邮箱、电话等）和属性（如`required`、`placeholder`等），简化了表单验证和用户交互。

6. **地理定位**：HTML5的`navigator.geolocation` API允许网页获取用户的地理位置信息，用于提供基于位置的服务和功能。

7. **Web存储**：HTML5的`IndexedDB`和`WebSQL`提供了更强大的客户端数据库支持，使网页能够在本地存储和检索大量结构化数据。

处理HTML5新标签的浏览器兼容问题可以采取以下方法：

1. **使用Polyfill**：对于不支持HTML5新标签的旧版本浏览器，可以使用Polyfill库（如Modernizr、HTML5 Shiv）来模拟新标签的行为和样式。

2. **样式回退**：为HTML5新标签提供样式回退，即为这些标签设置默认样式，以确保在不支持的浏览器中也能正确显示内容。

3. **JavaScript检测**：使用JavaScript检测浏览器是否支持HTML5新标签，如果不支持，则采取相应的替代方案或提供其他内容。

区分HTML和HTML5可以通过以下几个方面：

1. **文档类型声明（DOCTYPE）**：HTML5的文档类型声明为`<!DOCTYPE html>`，而HTML4的文档类型声明为`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">`。

2. **新标签**：HTML5引入了一些新的语义化标签，如`<header>`、`<nav>`、`<section>`等，而HTML4中没有这些标签。

3. **功能特性**：HTML5引入了许多新的功能和API，如多媒体支持、Canvas绘图、本地存储等，而HTML4没有这些功能。

总结：HTML5相对于HTML4来说是一个更加强大和功能丰富的版本，通过引入新标签、功能和API，提供了更好的语义化、多媒体支持、绘图能力、本地存储等特性。处理HTML5新标签的浏览器兼容问题可以使用Polyfill、样式回退和JavaScript检测等方法。

<br/>

### 请说明 Html 布局元素的分类有哪些？并描述每种布局元素的应用场景 

公司：玄武科技

分类：Html

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/843)
HTML布局元素可以分为以下几种分类：

1. **块级元素**：块级元素在默认情况下会独占一行，可以设置宽度、高度、内外边距等属性。常见的块级元素有`<div>`、`<p>`、`<h1>`-`<h6>`等。块级元素适合用于创建页面的主要结构和布局，如页面的头部、导航栏、侧边栏、内容区域等。

2. **内联元素**：内联元素不会独占一行，只占据其内容所需的空间，不能设置宽度、高度等属性。常见的内联元素有`<span>`、`<a>`、`<strong>`、`<em>`等。内联元素适合用于包裹文本或行内元素，实现对文本的样式化或超链接等功能。

3. **内联块级元素**：内联块级元素具有内联元素的特性，但可以设置宽度、高度、内外边距等属性。常见的内联块级元素有`<img>`、`<input>`、`<button>`等。内联块级元素适合用于包裹其他内联元素，实现水平排列或创建按钮等功能。

4. **表格元素**：表格元素用于创建表格布局，包括`<table>`、`<tr>`、`<td>`等。表格元素适合用于展示结构化的数据，如数据报表、排行榜等。

5. **弹性盒子（Flexbox）**：Flexbox是一种弹性布局模型，通过设置容器和子元素的属性，实现灵活的自适应布局。常见的Flexbox属性有`display: flex`、`flex-direction`、`justify-content`、`align-items`等。Flexbox适合用于创建响应式布局，实现灵活的元素排列和对齐。

6. **网格布局（Grid）**：网格布局是一种二维布局模型，通过将容器划分为行和列，实现复杂的网格布局。常见的网格布局属性有`display: grid`、`grid-template-rows`、`grid-template-columns`、`grid-gap`等。网格布局适合用于创建复杂的网格结构，实现多列布局和对齐。

以上是HTML布局元素的主要分类和应用场景。根据具体的需求和设计，可以选择合适的布局元素来实现所需的页面布局和结构。

<br/>

