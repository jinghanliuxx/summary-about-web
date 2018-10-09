#HTML
关于多张图片并排的问题：换行的图片之间可能会存在空隙，可添加注释解决


#CSS
slideToggle：可用transform：scaleY(0);transform-origin:top;transition:all 300ms;
             hover或click之后:transform:scaaleY(1);替代slide效果，可解决下拉菜单闪屏或迟钝的问题
             
选择器:">"选中父元素下的直接子元素(存在其他父元素的不包含在内),
       ":last-children"/":nth-child(n)"选择首尾子元素或父元素下的第n个子元素(":"前不加空格表示选中的为该元素的直接子元素，加空格表示以该元素下的子元素作为判定对象)



#JQ
JQ选择器和css大都相同
遍历.siblings()方法:$("p").siblings(".selected")查找所有类名为selected的p元素
                   $('.item').siblings().css("color","red");查找类名为item的所有同胞元素,并将除它之外的元素color设为red.
