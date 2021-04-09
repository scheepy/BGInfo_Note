# BGInfoSvc

整個BGInfo的進入點，進入點的入口(main方法)，先取消Banner以及關掉IoC。**關掉IoC**代表自此要自己生成物件，這樣做不是很有風險嗎 ?

- 服務之間怎麼溝通的 ? 

> 透過  iQD, iPSD

- 對外和誰溝通？

> - AC (告知有哪些權限), 透過 group : ac-query-perms
> - 透過 svc/channel : BGInfo/getRidX



- DCApi 註冊網址(遠端主機對應服務 _IP+Port_ )



[HashTable 及 HashMap的差異](https://matthung0807.blogspot.com/2018/12/java-hashtablehashmap.html)