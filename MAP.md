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
  * 返回参数说明：<br /><br /><table><thead><th>参数</th><th>类型</th><th>说明</th></thead><tbody><tr><td>uid</td><td>string</td><td>用户id</td></tr><tr><td>name</td><td>string</td><td>用户昵称</td></tr><tr><td>groupid</td><td>int</td><td>用户组id: 1.管理员2.普通用户</td></tr><tr><td>reg_time</td><td>timestamp</td><td>注册时间</td></tr><tr><td>last_login_time</td><td>timestamp</td><td>最后登入时间</td></tr><tr><td>region</td><td>array|object</td><td>列表数据</td></tr></tbody></table><br />
