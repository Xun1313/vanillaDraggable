容器的事件
dragover
//一移動就瘋狂觸發
dragenter
//一移動先觸發一次,之後進到別的容器立刻觸發一次
dragleave
//一移動離開自己的容器觸發一次,之後進到別的容器再離開後又觸發一次
drop
//把dragover設preventDefault才有
//一放開滑鼠就觸發



內容的事件
dragstart
//一移動指觸發一次,之後不觸發
dragend
//滑鼠一放開就觸發


(1)移動的殘影是draggable='true'來的
(2)刪掉原本容器裡的內容和增加到新的容器裡要自己實作
刪掉用class none起來增加用appendChild()
