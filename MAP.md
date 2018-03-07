# 地图数据
1.  地图-摄像头(基站)

    * 简要描述：
    地图中摄像头数据
    * 请求URL：
    http://xx.com/api/map/camera
    * 请求方式：
    POST
    * 参数：<br /><br /><table><thead><th>参数</th><th>必选</th><th>类型</th><th>说明</th></thead><tbody><tr><td>uid</td><td>必选</td><td>string</td><td>用户id</td></tr></tbody></table>
    * 返回示例：<br /><br /><pre><code>{
    "error_code": 0,
    "data": [
        {name:"海淀基站",value:[116.301501,39.96263],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"peter",phone:"15623526487"},
        {name:"石景山基站",value:[116.226464,39.926008],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"james",phone:"15623526487"},
        {name:"丰台基站",value:[116.303963,39.859286],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"jack",phone:"15623526487"},
        {name:"西城基站",value:[116.375439,39.903264],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"lucy",phone:"15623526487"},
        {name:"东城基站",value:[116.426604,39.93234],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"lilei",phone:"15623526487"},
        {name:"朝阳基站",value:[116.463859,39.92206],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"paul",phone:"15623526487"},
        {name:"通州基站",value:[116.666881,39.903682],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"joe",phone:"15623526487"},
        {name:"门头沟基站",value:[116.102403,39.951789],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"michael",phone:"15623526487"},
        {name:"驿马图牧场基站",value:[115.107629,41.162113],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"michael",phone:"15623526487"},
        {name:"沽源县",value:[115.721064,41.781334],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"michael",phone:"15623526487"},
        {name:"杨树沟",value:[116.628065,41.429862],symbol:"image://img/station-right.png",type:"station",status:"ok",message:"",woker:"michael",phone:"15623526487"}
      ]
  }</code></pre>
     * 返回参数说明：<br /><br /><table><thead><th>参数</th><th>类型</th><th>说明</th></thead><tbody><tr><td>name</td><td>string</td><td>摄像头(基站)名称</td></tr><tr><td>value</td><td>array</td><td>摄像头(基站)坐标</td></tr><tr><td>symbol</td><td>string</td><td>摄像头(基站)图标</td></tr><tr><td>type</td><td>string</td><td>设备类型</td></tr><tr><td>status</td><td>string</td><td>摄像头(基站)状态</td></tr><tr><td>message</td><td>string</td><td>label信息</td></tr><tr><td>woker</td><td>string</td><td>负责人名称</td></tr><tr><td>phone</td><td>string</td><td>负责人电话</td></tr></tbody></table><br />
1.  地图-车辆定位

    * 简要描述：
    地图中车辆数据
    * 请求URL：
    http://xx.com/api/map/gps
    * 请求方式：
    POST
    * 参数：<br /><br /><table><thead><th>参数</th><th>必选</th><th>类型</th><th>说明</th></thead><tbody><tr><td>uid</td><td>必选</td><td>string</td><td>用户id</td></tr></tbody></table>
    * 返回示例：<br /><br /><pre><code>{
    "error_code": 0,
    "data": [
    	  {name: '京A JK2351',local:[116.493956,39.962733], value: 90},
	     {name: '京B JH2351',local:[116.388171,39.994137], value: 90},
	     {name: '京C BA2351',local:[116.313432,39.914935], value: 90},
	     {name: '京D BC2351',local:[116.313432,39.914935], value: 90},
	     {name: '京E DC2351',local:[116.273188,39.874192], value: 90},
	     {name: '京F ED2351',local:[116.273188,39.874192], value: 90},
	     {name: '京G FE2351',local:[116.273188,39.874192], value: 90},
	     {name: '京H GF2351',local:[116.12371,39.80638], value: 90},
	     {name: '京J HG2351',local:[116.525001,39.809484], value: 90},
	     {name: '京K JH2351',local:[116.313432,39.80638], value: 90},
	     {name: '京L KJ2351',local:[116.49568,39.863116], value: 90},
	     {name: '京M LK2351',local:[116.29101,39.991926], value: 90},
	     {name: '京N ML2351',local:[116.416342,39.844948], value: 90}
    ]
  }</code></pre>
     * 返回参数说明：<br /><br /><table><thead><th>参数</th><th>类型</th><th>说明</th></thead><tbody><tr><td>name</td><td>string</td><td>车牌号</td></tr><tr><td>local</td><td>array</td><td>车辆坐标</td></tr><tr><td>value</td><td>int</td><td>车辆图标大小</td></tr></tbody></table><br />
