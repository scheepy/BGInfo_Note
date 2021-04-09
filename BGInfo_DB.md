# BGInfo_DB

前題 :  Code對應

> ```java
> Parameter query = new Parameter("D");
> query.setService("APConfig");
> // 上面對應的 MongoDB 就是 APConfig#D
> ```

1. **BGInfo#BGInfo **欄位

   >appID, loginID, ver, devList, sendFlag
   >
   >範例  : 
   >
   >```json
   >{
   >	"_id" : ObjectId("6018f176e5d5c6536f14e62d"),
   >	"appID" : "x4cn",
   >	"loginID" : "usr:ss2_q:ff:k3k16f2dpte9cwg2fiyl491osat8vvtu",
   >	"ver" : 32,
   >	"devList" : [
   >		{
   >			"devToken" : "1114a8979226d991ff5",
   >			"t" : 20210408141439,
   >			"isApple" : true
   >		}
   >	],
   >	"sendFlag" : true
   >}
   >```

2. **BGInfo#Badge**欄位

   > ch, v, badge
   > 範例 :
   >
   > ```json
   > {
   > 	"_id" : ObjectId("604add6be5d5c6536f6f6c13"),
   > 	"ch" : "Info.usr:ctp_gjqh_sim_tcgw:TRADE_FILL:01312.x4cn",
   > 	"v" : 8,
   > 	"badge" : 8
   > }
   > ```

3. **BGInfo#Loss**欄位

   > ch, u, sendDoc, tm
   > 範例 : 
   >
   > ```json
   > {
   > 	"_id" : ObjectId("5f3def4918eae6e0c2bea527"),
   > 	"ch" : "Info.usr:ss2:TRADE_FILL:chin-dev-001.x4cn",
   > 	"u" : "L1597894473:0",
   > 	"sendDoc" : {
   > 		"msg" : "[chin-dev-001] 商品[6C] 以價格0.7565成交1口",
   > 		"u" : "L1597894473:0",
   > 		"badge" : 374
   > 	},
   > 	"tm" : 1597894473154
   > }
   > ```

4. **BGInfo#p12**欄位

   > appID, fileName, isRelease, p12, pswd
   > 範例 : 
   >
   > ```json
   > {
   > 	"_id" : ObjectId("5bc5a10b44b38eb747fe9df7"),
   > 	"appID" : "com.icetech.x3",
   > 	"fileName" : "Tuishou.Production.p12",
   > 	"isRelease" : true,
   > 	"p12" : BinData(0,"MIIMyQIBAzCCDJAGCSqGSIb3DQEHAaCC...   (3,277 bytes)"),
   > 	"pswd" : "Ice70547377"
   > }
   > ```

5. **BGInfo#SendType**欄位

   > appID, appKey, appSecret, type
   > 範例 :
   >
   > ```json
   > {
   > 	"_id" : ObjectId("60580b2d74d5006cacec1d42"),
   > 	"appID" : "gtja.ycgo2",
   > 	"appKey" : "254599c43b6c9b01ed02699b",
   > 	"appSecret" : "c0af98816b9ca52de4ba82f7",
   > 	"type" : "aurora"
   > }
   > ```
   >
   > 

