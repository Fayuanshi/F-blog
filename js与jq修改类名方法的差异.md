

    在js中修改元素类名的方法为获取到元素之后使用className方法设置元素的class但是需要写全所有的类名，如类名很多再添加一个时较为繁琐    
    
    var item = document.getElementsByClassName('item1 item2 item3 item4 item5');
    item.className = 'item1 item2 item3 item4 item5 item6';

    而此时jq的aadClass方法更为简便

    $(".item").addClass("item6");

    但是如果类名很多需要去掉很多时,jq的removeClass方法反而变得繁琐

    $(".item).removeClass("item1 item2 item3 item4 item5");

    而js方法显得简便
    item.className="item6"

   
    
