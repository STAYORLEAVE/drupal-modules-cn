## Drupal modules 中文
Drupal 模块整理，久不维护或者有安全风险的模块酌情不添加。

### 目录

#### UI
 - [幻灯片](#carousel)
 - [视图](#views)
 - [内容](#node)
 - [权限控制](#permissions)
 - [投票](#vote)
 - [社交](#sns)
 - [官网文档](#doc)

#### TODO
 - [互动](#active)
 - [词汇表](#taxonomy)
 - [SEO](#seo)
 - [移动端](#mobile)
 - [管理](#manage)

<h4 id="carousel">幻灯片 Carousel</h4>

| 模块 | 描述 | 安装量 |
| --- | ---- | :---: |
| [Slick Carousel](https://www.drupal.org/project/slick) | 强大响应式且性能优异的图片轮播解决方案 | 45w+|
| [Views Slideshow](https://www.drupal.org/project/views_slideshow)| 最受欢迎的幻灯片模块，可放任何内容 | 215w+|
| [Colorbox](https://www.drupal.org/project/colorbox) | 轻量级高可定制幻灯片模块，高度集成在drupal中  | 252w+ |
| [Colorbox Node @d7](https://www.drupal.org/project/colorbox_node)| 可以把node,user,views,webform等实体显示在弹窗  | 16w+|
| [Flex Slider](https://www.drupal.org/project/flexslider) | 响应式，支持移动设备手势滑动  | 71w+|
| [Views Nivo slider](https://www.drupal.org/project/views_nivo_slider) | 有很多的效果  | 14w+|
| [Field Slideshow](https://www.drupal.org/project/field_slideshow) | 让内容的图片多值字段支持幻灯片，使用jQuery cycle实现  | 17w+|
| [jCarousel](https://www.drupal.org/project/jcarousel) | 可以把任何内容或图片转换成轮播组件，集成视图，开放一些API |  59w+|
| [Owl Carousel](https://www.drupal.org/project/owlcarousel) | 支持响应式、移动手势、高定制幻灯片，有可用的回调，自定义事件 | 21w+|
| [Vegas @d7](https://www.drupal.org/project/vegas) | 给页面添加全屏的背景图片幻灯片 |  1w+|
| [Juicebox](https://www.drupal.org/project/juicebox) | 可构建HTML5响应式图片库，提供了强大的跨设备解决方案  | 12w|
| [Node Gallery @d7](https://www.drupal.org/project/node_gallery) | 把node使用幻灯片显示 | 15+|


<h4 id="views">视图 Views</h4>

| 模块 | 描述 | 安装量 |
| --- | ---- | :---: |
| [Views Field View](https://www.drupal.org/project/views_field_view) | 在视图中插入另外一个视图，可带参数 | 38w+ |
| [EVA: Entity Views Attachment](https://www.drupal.org/project/eva) | 把视图当成字段插入到内容类型字段中，通过参数可配置出无需后端开发的功能 |53w+|
| [Views Load More @d7](https://www.drupal.org/project/views_load_more) | 通过Ajax加载更多，配合waypoints模块可定制滚动到某个元素时加载 | 24w+|
| [Views Infinite Scroll](https://www.drupal.org/project/views_infinite_scroll) |页面滚动到底部Ajax自动加载，也可配置成按钮触发，轻量级解决方案 | 126w+|
| [Views Database Connector](https://www.drupal.org/project/views_database_connector) | 可以让views连接非Drupal数据库表的外部数据库表 | 1w+|
| [Views Bulk Operations(VBO)](https://www.drupal.org/project/views_bulk_operations) | 为输出的视图添加可批量操作，给有权限的用户自定义查询进而批量更新删除数据 |317w+|
| [Semantic Views](https://www.drupal.org/project/semanticviews) | 该模块可以方便修改Views生成的html标签和class而无需覆写模板 | 15w+|
| [Views Accordion](https://www.drupal.org/project/views_accordion) | 通过Views来输出一个可折叠的手风琴效果组件，依赖jQuery UI Accordion | 37w+ |
| [Views Flipped Table](https://www.drupal.org/project/views_flipped_table) | 把视图输出的表格行和列进行翻转，当字段很多的时候非常有用 | 4.3w+|
| [Better Exposed Filters](https://www.drupal.org/project/better_exposed_filters) | 用户体验更好的视图过滤表单模块 | 152w|
| [Masonry Views](https://www.drupal.org/project/masonry_views) | 使用Masonry API 构建的瀑布流模块 | 7.9w|
| [A Simple Timeline](https://www.drupal.org/project/simple_timeline) | 使用views输出简单的时间轴模块 | 1.3w|
| [Views data export](https://www.drupal.org/project/views_data_export) | 从自定义的视图从导出数据（csv, xls, doc, txt, xml）| 107w+|


<h4 id="node">内容 Node </h4>

| 模块 | 描述 | 安装量 |
| --- | ---- | :---: |
| [Paragraphs](https://www.drupal.org/project/paragraphs)| 创作内容的新方式，在任何内容类型上添加段落字段，段落还可以互相嵌套，从简单的文本或图片到复杂的图片轮播，还可以随意重新排序，[DEMO](https://paragraphs.site-showcase.com/) | 203w+ |
| [Classy Paragraphs](https://www.drupal.org/project/classy_paragraphs)| 给Paragraphs字段添加类，方便为段落区块定制不同的样式风格 | 11w+ |
| [Content lock](https://www.drupal.org/project/content_lock)| 内容锁定，阻止其他用户同时对同一节点编辑，可按节点类型或按格式；可设置避免意外丢失内容，如关闭浏览器链接未保存而离开编辑表单等| 22w+ |
| [Weight](https://www.drupal.org/project/weight) | 对内容启用权重排序，对非重视时间节点的内容很有用，比如产品，你想要的内容 | 38w+ |
| [Exclude Node Title](https://www.drupal.org/project/exclude_node_title) | 前台页面排除显示标题，有些场景下，你并不希望显示内容的标题 | 26w+ |
| [Flippy](https://www.drupal.org/project/flippy) | 为内容添加上一篇/下一篇的功能，这在很多的门户网站中很常见 | 6w+ |
| [Scheduler](https://www.drupal.org/project/scheduler) | 可对内容进行定时发布或者未发布 | 119w+| 
| [linkit](https://www.drupal.org/project/Linkit) | 在编辑器中快速插入节点，用户链接，分类术语，文件和外部链接的模块 | 137w+ |
| [Add another](https://www.drupal.org/project/addanother) | 发布节点后，自动新建节点，快速发布内容，节省操作 | 18w+ |
| [FullCalendar](https://www.drupal.org/project/fullcalendar) | 使用日历来显示字段（使用时间对内容分类） | 21w+ |
| [Calendar @d7](https://www.drupal.org/project/calendar) | 多种日历格式显示节点字段 | 144w+ |
| [Node clone @d7](https://www.drupal.org/project/node_clone) | 允许用户对已存在的内容节点进行克隆| 168w+ |
| [Bulk Delete @d7](https://www.drupal.org/project/bulkdelete) | 一键删除指定内容类型的内容节点 | 1.9w |
| [Inline Entity Form](https://www.drupal.org/project/inline_entity_form) | 如果B关联A内容类型，可以在A的内容维护页面新建B节点 | 214w+ |
| [Metatag](https://www.drupal.org/project/metatag)| SEO 利器，设置页面Meta元数据信息 | 443w+ |
| [Diff](https://www.drupal.org/project/diff)| 跟踪node节点的版本变化，跟踪修改| 268w+ |
| [Node Title Validation](https://www.drupal.org/project/node_title_validation) | 可对节点标题进行验证（字符长度、黑名单、唯一性）| 1.8w+ |
| [FAQ Field](https://www.drupal.org/project/faqfield)| 可快速创建 FAQ 页面（常见问题解答）| 7.5w+ |

<h4 id="permissions">权限控制</h4>

| 模块 | 描述 | 安装量 |
| --- | ---- | :---: |
| [Permissions by Term](https://www.drupal.org/project/permissions_by_term)| Drupal 默认内容类型按角色给访问权限，结合该模块可以让某内容节点只允许某些角色访问或者指定用户访问 | 8w+ |
| [Content Access](https://www.drupal.org/project/content_access)| 按角色和作者统一设置管理内容类型的访问、编辑、删除权限 | 58w+ |
| [Private content](https://www.drupal.org/project/private_content)| 简单的 Node 节点访问控制模块 | 1.3k+ |
| [Block Content Permissions](https://www.drupal.org/project/block_content_permissions)| 开放区块管理权限，允许指定角色新建、更新、删除区块内容 | 4.8w+ |



<h4 id="vote">投票</h4>

| 模块 | 描述 | 安装量 |
| --- | ---- | :---: |
| [Flag](https://www.drupal.org/project/flag)| 重量级模块，提供灵活的标记系统，可提供任何内容类型的实体提供任意数量的标记 | 150w+ |
| [Vote Up/Down](https://www.drupal.org/project/vote_up_down)| 允许对实体节点进行投票 | 26w+ |
| [Fivestar @d7](https://www.drupal.org/project/fivestar)| 默认提供了几种风格的五星评价 | 73w+ |
| [Rate](https://www.drupal.org/project/rate)| 评价模块，提供点赞，五星，yes/no等选项，另外还有一些统计票数可选| 21w+ |
| [Star Rating](https://www.drupal.org/project/starrating)| 提供星级评价字段，在字段显示中可选多种评价样式| 3W+|

<h4 id="sns">社交</h4>

| 模块 | 描述 | 安装量 |
| --- | ---- | :---: |
| [Privatemsg @d7](https://www.drupal.org/project/privatemsg)| 发送私人信息，论坛或者社交网站 | 37w+ |
| [Bookabel Entities Everywhere](https://www.drupal.org/project/bee)| 为任何节点添加预订功能，粒度可以细分到小时或者每日 | 3.7k+ |
| [oLogin](https://www.drupal.org/project/ologin)| 提供国内常用的第三方社交平台统一登录 | 1.5k+ |
| [Wechat](https://www.drupal.org/project/wechat)| Durpal微信公众平台接口，提供基本功能 | 1.1w+ |
| [Organic groups](https://www.drupal.org/project/og)| 允许用户创建自己的组 | 113w+ |



<h4 id="doc">Drupal 官网文档</h4>

| 标题 | 描述 |
| --- | ---- | 
| [添加css和js](https://www.drupal.org/docs/8/theming/adding-stylesheets-css-and-javascript-js-to-a-drupal-8-theme) | 在Drupal8 中添加css和javascript |
| [建立子主题](https://www.drupal.org/docs/8/theming-drupal-8/creating-a-drupal-8-sub-theme-or-sub-theme-of-sub-theme) | 关于建立子主题的文档 |
| [JavaScript API 概览](https://www.drupal.org/docs/7/api/javascript-api/javascript-api-overview) | Drupal8 在页面初始化的时候或者获取数据时候提供了一些API |
| [主题定义.info.yml](https://www.drupal.org/docs/8/theming-drupal-8/defining-a-theme-with-an-infoyml-file) | 详细介绍了主题定义文件的参数 |
| [在主题中添加区域](https://www.drupal.org/docs/8/theming/adding-regions-to-a-theme) | 在 Drupal8 中如何声明一个区域 |
| [Drupal 如何架构CSS](https://www.drupal.org/docs/develop/standards/css/css-architecture-for-drupal-8) | 可以借鉴一下Drupal 对应css组件化开发的一些思路 |
| [Seven UI 样式指南](https://groups.drupal.org/node/283223) | 详细介绍了内置主题 Seven 的UI指南 |
| [Drupal 编码规范](https://www.drupal.org/docs/develop/standards) | 编码规范的目录 |
| [Drupal JavaScript API 文档和注释规范](https://www.drupal.org/docs/develop/standards/javascript/javascript-api-documentation-and-comment-standards) | JavaScript 开发的相关规范 |
| [JavaScript 编码规范](https://www.drupal.org/docs/develop/standards/javascript/javascript-coding-standards) | JavaScript 开发的相关规范 |
| [ESLint settings](https://www.drupal.org/docs/develop/standards/javascript/eslint-settings) | ESLint 代码检查 |
| [jQuery 编码规范](https://www.drupal.org/docs/develop/standards/javascript/jquery-coding-standards) | jQuery 编码规范和最佳实践 |
| [谁使用了Drupal？](https://www.drupal.com/showcases) | 官网收录的Drupal使用案例 |
