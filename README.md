# 实验2-Android布局
### 使用线性布局，约束布局，表格布局实现三种页面
##### 1.线性布局LinearLayout实现
页面中先采用LinearLayout的垂直布局，再在其中嵌套四个水平布局，每个水平LinearLayout中设计四个按钮，分别命名为one one ,one two ,one three ,one four ,two one ,two two ,two three ,two four ,three one ,three two ,three three ,three four ,four one ,four two ,four three ,four four

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201208163358958.JPG?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NDcyODUzNw==,size_16,color_FFFFFF,t_70#pic_center)
##### 2.约束布局ConstraintLayout实现
向约束页面先添加七个按钮，点击拖动按钮设置约束，将按钮拖动到适合位置，再修改每个按钮的颜色,命名按钮为red ,orange ,yellow ,green ,blue ,indigo ,violet ，分别设置按钮的高度和宽度

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201208164135424.JPG?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NDcyODUzNw==,size_16,color_FFFFFF,t_70#pic_center)
##### 3.表格布局TableLayout实现
在TableLayout布局中添加6个TableRow组件，第一个TableRow中放三个按钮，后两个按钮命名为Open ,CTRL-o ,第二个TableRow中放三个按钮，后两个按钮命名为save,CTRL-s ,第三个TableRow中放三个按钮，后两个按钮命名为save as ,CTRL-shift-s ,添加一条分割线，第四个TableRow中放两个按钮，命名为X ,import... ,第五个TableRow中放三个按钮，命名为X ,export... ,CTRL-e,再添加一条分割线，最后一个TableRow中放两个按钮，后一个命名为quit

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201208164714713.JPG?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NDcyODUzNw==,size_16,color_FFFFFF,t_70#pic_center)

##### 总结：本次实验学习了三种布局方式，分别是线性布局，约束布局，表格布局，在实验过程中有一个需要注意的地方：运行不同页面前应在MainActivity.java中修改要运行的页面名。
