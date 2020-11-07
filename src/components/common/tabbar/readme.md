#############
使用说明：
1.需要将该插件引入到对应的项目中
###############
2.在项目中需要挂载 TabBar 与TabBarItem两个组件
##################
3.在TabBarItem中有两个具名插槽，icon表示图标字体，text表示文字内容
####################
4.在App.vue中使用
    <TabBar>
        <TabBarItem>
            <div slot='icon'></div>
            <div slot='text'></div>
        </TabBarItem>
    </TabBar>
################
5.在TabBarItem组件上可以设置的属性
    1.path属性：设置路由的路径
    2.col属性：设置点击态的颜色