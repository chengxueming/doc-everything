* 管理后台类
  * js table 
    * feature
      * 筛选，排序，分页
      * 自定义字段内容
    * 参考项目
      * [react-component/table](https://github.com/react-component/table) [grouping columns](http://react-component.github.io/table/examples/grouping-columns.html), [Fixed columns](http://react-component.github.io/table/examples/fixedColumns-auto-height.html)
      * [gajus/table](https://github.com/gajus/table#table-usage-column-width) [cldwalker/table](https://github.com/cldwalker/table) 控制台表格
      * [Smart-Table](https://github.com/lorenzofox3/Smart-Table) [例子](https://smart-table.github.io/www/dist/demo.html) 筛选，排序，分页，自定义字段内容，搜索
      * [vue-data-tables](https://github.com/njleonzhang/vue-data-tables) 搜索，分页，排序，vue
    * php web gen
      * feature
        * 自定义layout 水平垂直
        * 面包屑导航 
        * 提供插件式拓展
      * 参考项目
* emacs
  * php project parser
    * feature
      * 生成项目的调用类图
      * 统计函数或类调用频率 官方的，非官方的，给出[文档地址](http://php.net/)
    * 参考工具
      * [PHP-Parser](https://github.com/nikic/PHP-Parser) 读取php file信息
      * [graphviz](https://gitlab.com/graphviz/graphviz) 根据格式化文本生成svg或图片的命令行程序 [class relation](https://graphviz.gitlab.io/_pages/Gallery/directed/Genetic_Programming.html) [data structure](https://graphviz.gitlab.io/_pages/Gallery/directed/datastruct.html) [gallery](http://www.graphviz.org/gallery/)
     * 参考项目
       * [php graph uml](https://github.com/clue/graph-uml) 用php来分析php，生成调用关系图
       * [php class grapher](https://github.com/sixty-nine/class-grapher)
    * source bookmark
    	* feature
    		* 为代码阅读位置添加书签，树状书签列表可随时整理
    		* 生成书签使用次数统计，项目书签数量统计
    * use history
    	* featrue
    		* 获得快捷键使用数量统计，插件使用次数统计，单个和组合按键点击次数统计，对应功能
    * codesnippet
    	* feature
    		* 通过快捷键将代码发送到片段仓库 并命名,根据类型和项目标签自动归类，并且同步账户
    		* 发送时指定需要自定义的变量 和 提示语言 使用时根据上下文自动补全
    * php ide
    	* feature
    		* 指定源码路径可以根据 原生函数 跳转到php-src
    		* 根据完善的注释自动提示补全 错误检查（如返回value类型，@duplicate等）配置语言级别，支持链式调用
    		* 新建类快捷键，支持psr4，自动填充命名空间和命名空间补全，快捷键添加函数（通过提示指定函数名称）
    		* 指定安装了什么拓展，自动下载对应头文件，自动补全（swoole，mongo），指定拓展源码也可以跳转到定义
    * graphic char
    	* feature
    		* 绘制字符矩形可以指定 与 另一个矩形的margin，padding
    		* 绘制边线可以指定箭头方向（visio），可绘制流程图，在边线上加文字
    		* 自定义矩形class，添加属性，新建矩形指定类可自动提示。
* 工具
  * 平台
    * web() eamcs 命令行(python, ruby)
  * Redis Designer
    * feture
      * 根据文本描述生成redis数据结构图，计算redis将会达到的规模，给出常用命令参考和时间复杂度
      * 给出不同redis 数据结构的关系
    * 参考项目
      * TODO
* web 项目
	* music view
		* feature
			* 导入乐谱生成 五线谱
			* 自动播放，🎵跳动动画
			* 可以选择钢琴键盘或者五线谱
	* 已有项目
		* [简陋 code pen](https://codepen.io/chengxueming/pen/RMOvLg)
	* 参考项目
		* [skechup msphsics 钢琴](https://3dwarehouse.sketchup.com/model/94df3cd9-3a96-4fb1-b4df-17705afc3511/MSPhysics-MIDI-Piano)
		* [一个html钢琴 很有魔性](https://codepen.io/jakealbaugh/pen/qNrZyw)
		* [精美的纯css五线谱](https://codepen.io/32bitkid/pen/Ihciy)
		* [另一个css五线谱](https://codepen.io/dudleystorey/pen/PwXqYO)
	* co-coder
		* feature
			* 发布项目，召集合伙人，申请和审批
			* 提供交流机制，和报酬，规定完成时间和信誉体系
	* friends card
		* feature
			* 根据微信注册，上传头像，个人简介，个人页面的卡片
			* 可以分享出去别人来评论，和点赞，评论可以是语音，文字，网址，图片
			* 拥有者选择接受或否定评论，可以给评论者打标签（爸爸，妈妈，女朋友），可以删除评论，
	*	vr cube
		*	feature
			* 在web vr里实现目睹一个魔方还原
		*	参考项目
			* [vue 魔方](https://github.com/caolinjian/rubik-cube)
* sketchup 项目
	* cube cube
		* feature
			* 以sketchup插件形式，切换二三四阶层魔方，可以打乱和还原
		* 	已有项目
			* [3阶层还原未完成](https://github.com/chengxueming/Rubik-s-Cube)  
		*	参考项目
			*  [skechup开源小插件](https://github.com/thomthom/sketchup-robot-simulator)
	*  lego language
		*	feature
			*	用简写给cube命名，用code指定摆放方式
			* 	可以封装lego类库，制作lego城市和机器人
			*  编写lego函数，支持自定义模型并且绑定lego语言
	*	立体拼图
		*	feature
			*  可以给卡片绑定插槽属性，用代码指定卡片装配形式
			*  可以在画板上用绘图工具绘制图案，指定插槽信息和拼装方式，生成立体模型
	*	立体折纸
		*	feature
			*  通过代码进行折纸，定义函数
		*	参考项目
			*  [css 纸飞机](https://codepen.io/victorfreire/pen/gPwBwe)
			*  [svg 纸鸟](https://codepen.io/guttentag/pen/Ktbxu)     
