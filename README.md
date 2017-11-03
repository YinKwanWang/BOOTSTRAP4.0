# BOOTSTRP4.0
Bootstrap 是全球最受欢迎的前端组件库，用于开发响应式布局、移动设备优先的 WEB 项目。

# BS里面文字 标题文字大小class名也有  class="h1~h6",
            比h1还大的class名超大的 class = "display-1~display-6"

            p标签 文字类名     class = "lead"文字会稍微大点
            字体加粗 / 正常 / 斜体 
            类名 font-weight-bold font-weight-normal font-weight-italic

            文本大小写转换类名
            大写->小写    text-lowercase
            小->大        text-uppercase
            文本首字母大写  text-capitalize

            文本字体变大加粗 blockquote
            右对齐 blockquote text-right
            footer标签：作者右下方 字体变小颜色变淡

            文本ul标签样式
            取消默认点 list-unstyled
            li标签成一排 li标签类名 list-inline-item 

            
            (多文字响应式排版):文字左右两边对齐样式  text-justify
            文字靠左居中向右  text-left text-center text-right

            浏览器窗口到达一定尺寸(顺序有大到小)时 左右居中
            text-sm-right left center
            text-md-right left center
            text-lg-right left center
            text-xl-right left center

            文字竖向排版
            文本上下调整 基线 类名：(一起写能看出效果)
            align-baseline align-top align-bottom 
            align-middle   align-text-top align-text-bottom

            快标签->行标签 类名：d-inline 
            行标签->块标签 类名：d-block
            块标签->内联   类名：d-inline-block

            bs中浮动类名   float-left左浮动  float-right有浮动 float-none没有浮动 父级类名clearfix 清除浮动

            响应式浮动类名  float-sm-right (left none)   float-md-right
                          float-lg-right    float-xl-right


             文字导航类名  固定顶部  fixed-top  固定底部 fixed-bottom
                         此文本到达顶部的时候 会固定顶部  sticky-top
 
             默认bs网址引用 文本颜色：
             text-primary 蓝色  text-secondary 灰色 text-success 绿色 
             text-info  浅色蓝色 text-warning   黄色  text-danger 红色 
             text-dark  黑色  text-light 荧光白  text-white 白色
             文本背景颜色  
             bg-primary secondary success info warning danger dark

             文本隐形 invisible

             文本行与行之间的空隙
             m代表margin类 b代表bottom t代表top 数字代表像素
             mb-0 mb-1 mb-2 mb-3 mb-4 mb-5
             r代表right l代表left
             mr-0  ml-1
             x代表左右
             mx-5 左右5px
             y代表上下
             my-5 上下margin 5px
             p代表padding类 用法同上
             四个方向margin 用 m-5   四个方向padding 用 p-5
             实现居中用 类名mx-auto
2.BS->百分比布局

             给横向宽度百分比 w-25  50 75 100 Width25%  
             给纵向高度百分比 h-25  50 75 100 Height25%  都只有这四个值

             加边框 给边框加颜色 
             border(这是border 类加颜色类要写)   border-primary...

             断点 达到一定尺寸改变样式
             向上走
             @media(min-width:576px){ 768px 992px 1200px
                  body{
                        background:red;
                  }
             }
             向下走
             @media(max-width:576px){
                  body{
                        background:red;
                  }
             }


3.BS->导航类
             导航 按钮 btn 类
             btn(类)  btn-primary  btn-info
             带边框边框按钮 
             btn btn-outline-primary  btn-outline-dark

             按钮尺寸 btn btn-primary btn-lg 大尺寸
                     btn btn-info    btn-sm 小
                     btn btn-warning btn-block 撑满整行

             按钮状态  btn btn-primary 原始状态
                      btn btn-primary active 放上后状态
                      btn btn-primary disabled 点击状态

             按钮关联  btn btn-primary  另有data-toggle=""属性

             下拉菜单  button里的类 btn btn-primary dropdown-toggle
                      div里下拉菜单 dropdown-menu
                      div->a 标签里的类 dropdown-item

             菜单组    btn-group -> 子级button btn btn-primary

             类似分页组 btn btn-toolbar -> 3个div类btn-group->button类btn btn-primary

             按钮垂直排列 div类btn-group-vertical->button类 btn btn-primary

            导航基本排版

4.BS->列表组

5.BS->栅格 row-col  & 弹性盒子 d-flex

6. BS->轮播图 提示框 模态框
  7.no-gutters
在BS中不想让她们有间隙的话用它例子：

8.img-fluid 
图片无留白<img class="img-fluid" src="" alt="">

9.消息 框 大点用rows="5"
<textarea rows="5" type="text" class="form-control bg-dark text-muted">信息</textarea>

10.用BS写自己个人简历Demo练习 
