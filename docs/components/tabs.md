# tabs控件

tabs控件 切换`active`状态包括线性跟随和背景跟随
tabs控件依赖 `u-tabs` 类，状态类是共用的。
改变修饰类可以改变active样式。
默认是`active`状态为线性跟随
添加修饰类`.u-tabs-pill` 为背景跟随

# 如何使用

头部`<a>`是锚链接，链向下列的`<div>`类的名字

# 示例


##背景tabs


切换 背景色跟随作为`active`状态
<div class="example-content"><style>.ws{
	width: 60px;
	display: inline-block;
	border: 1px solid #ddd;
	height:30px;
	line-height: 30px;
	text-align: center;
	margin-left: 60px;
	margin-top: 10px;
}
#example,#example1{
	margin-left: 60px;
}
#example label:first-child,#example1 label:first-child{
	margin-left: 0px;
}
</style>
<div class="u-tabs">
    <div class="u-tabs__tab-bar">
        <a href="#tab-panel-1" class="u-tabs__tab is-active">页签1</a>
        <a href="#tab-panel-2" class="u-tabs__tab">页签2</a>
        <a href="#tab-panel-3" class="u-tabs__tab">页签3</a>
    </div>
    <div class="u-tabs__panel is-active" id="tab-panel-1">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
            <li>项目3</li>
            <li>项目4</li>
            <li>项目5</li>
        </ul>
    </div>
    <div class="u-tabs__panel" id="tab-panel-2">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
            <li>项目3</li>
        </ul>
    </div>
    <div class="u-tabs__panel" id="tab-panel-3">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
        </ul>
    </div>
</div>

</div>
<div class="examples-code"><pre><code>.ws{
	width: 60px;
	display: inline-block;
	border: 1px solid #ddd;
	height:30px;
	line-height: 30px;
	text-align: center;
	margin-left: 60px;
	margin-top: 10px;
}
#example,#example1{
	margin-left: 60px;
}
#example label:first-child,#example1 label:first-child{
	margin-left: 0px;
}</code></pre>
</div>
<div class="examples-code"><pre><code>&lt;div class="u-tabs">
    &lt;div class="u-tabs__tab-bar">
        &lt;a href="#tab-panel-1" class="u-tabs__tab is-active">页签1&lt;/a>
        &lt;a href="#tab-panel-2" class="u-tabs__tab">页签2&lt;/a>
        &lt;a href="#tab-panel-3" class="u-tabs__tab">页签3&lt;/a>
    &lt;/div>
    &lt;div class="u-tabs__panel is-active" id="tab-panel-1">
        &lt;ul>
            &lt;li>项目1&lt;/li>
            &lt;li>项目2&lt;/li>
            &lt;li>项目3&lt;/li>
            &lt;li>项目4&lt;/li>
            &lt;li>项目5&lt;/li>
        &lt;/ul>
    &lt;/div>
    &lt;div class="u-tabs__panel" id="tab-panel-2">
        &lt;ul>
            &lt;li>项目1&lt;/li>
            &lt;li>项目2&lt;/li>
            &lt;li>项目3&lt;/li>
        &lt;/ul>
    &lt;/div>
    &lt;div class="u-tabs__panel" id="tab-panel-3">
        &lt;ul>
            &lt;li>项目1&lt;/li>
            &lt;li>项目2&lt;/li>
        &lt;/ul>
    &lt;/div>
&lt;/div>
</code></pre>
</div>

##线性tabs

切换 线性跟随作为`active`状态
<div class="example-content"><style>.ws{
	width: 60px;
	display: inline-block;
	border: 1px solid #ddd;
	height:30px;
	line-height: 30px;
	text-align: center;
	margin-left: 60px;
	margin-top: 10px;
}
#example,#example1{
	margin-left: 60px;
}
#example label:first-child,#example1 label:first-child{
	margin-left: 0px;
}
</style>
<div class="u-widget-body">
    <div class="u-tabs u-tabs-pill">
        <div class="u-tabs__tab-bar">
            <a href="#tab-pills-panel-1" class="u-tabs__tab is-active">页签1</a>
            <a href="#tab-pills-panel-2" class="u-tabs__tab">页签2</a>
            <a href="#tab-pills-panel-3" class="u-tabs__tab">页签3</a>
        </div>
        <div class="u-tabs__panel is-active" id="tab-pills-panel-1">
            <ul>
                <li>项目1</li>
                <li>项目2</li>
                <li>项目3</li>
                <li>项目4</li>
                <li>项目5</li>
            </ul>
        </div>
        <div class="u-tabs__panel" id="tab-pills-panel-2">
            <ul>
                <li>项目1</li>
                <li>项目2</li>
                <li>项目3</li>
            </ul>
        </div>
        <div class="u-tabs__panel" id="tab-pills-panel-3">
            <ul>
                <li>项目1</li>
                <li>项目2</li>
            </ul>
        </div>
    </div>
</div>
</div>
<div class="examples-code"><pre><code>.ws{
	width: 60px;
	display: inline-block;
	border: 1px solid #ddd;
	height:30px;
	line-height: 30px;
	text-align: center;
	margin-left: 60px;
	margin-top: 10px;
}
#example,#example1{
	margin-left: 60px;
}
#example label:first-child,#example1 label:first-child{
	margin-left: 0px;
}</code></pre>
</div>
<div class="examples-code"><pre><code>&lt;div class="u-widget-body">
    &lt;div class="u-tabs u-tabs-pill">
        &lt;div class="u-tabs__tab-bar">
            &lt;a href="#tab-pills-panel-1" class="u-tabs__tab is-active">页签1&lt;/a>
            &lt;a href="#tab-pills-panel-2" class="u-tabs__tab">页签2&lt;/a>
            &lt;a href="#tab-pills-panel-3" class="u-tabs__tab">页签3&lt;/a>
        &lt;/div>
        &lt;div class="u-tabs__panel is-active" id="tab-pills-panel-1">
            &lt;ul>
                &lt;li>项目1&lt;/li>
                &lt;li>项目2&lt;/li>
                &lt;li>项目3&lt;/li>
                &lt;li>项目4&lt;/li>
                &lt;li>项目5&lt;/li>
            &lt;/ul>
        &lt;/div>
        &lt;div class="u-tabs__panel" id="tab-pills-panel-2">
            &lt;ul>
                &lt;li>项目1&lt;/li>
                &lt;li>项目2&lt;/li>
                &lt;li>项目3&lt;/li>
            &lt;/ul>
        &lt;/div>
        &lt;div class="u-tabs__panel" id="tab-pills-panel-3">
            &lt;ul>
                &lt;li>项目1&lt;/li>
                &lt;li>项目2&lt;/li>
            &lt;/ul>
        &lt;/div>
    &lt;/div>
&lt;/div></code></pre>
</div>


<!--### 示例1

示例1说明

### 示例2

示例2说-->


