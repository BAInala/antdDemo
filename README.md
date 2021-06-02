# antdDemo

1.有vuecli的环境  没有搭建

2. vue create antd-demo

3. 使用组件 npm i --save ant-design-vue

安装less-loader

less-loader  : npm install -D less-loader@7.x

更改主题色: 1.根据官网 修改vue.config.js
                  2. main.js---将’ant-design-vue/dist/antd.css’ 改为 “ant-design-vue/dist/antd.less”

                   3.如果报错 就npm i less  重新启动项目就可以

这个问题 是在这个链接解决的：https://blog.csdn.net/pacholy/article/details/115869261?utm_medium=distribute.pc_aggpage_search_result.none-task-blog-2~aggregatepage~first_rank_v2~rank_aggregation-2-115869261.pc_agg_rank_aggregation&utm_term=antd+%E4%BF%AE%E6%94%B9%E4%B8%BB%E9%A2%98%E8%89%B2&spm=1000.2123.3001.4430
