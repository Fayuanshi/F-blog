

在dom对象中可以通过数组下标获取对应的子对象
var items = document.getElementByClassName("item");
var item = items[1];

在jq中除了可以通过eq选择器选中相应index的子对象
var item =$(".item:eq(1)");

也可以通过数组下标获取对应的子对象
var item =$(".item")[1];
