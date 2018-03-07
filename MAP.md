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
    "data": {
      
    }
  }</code></pre>
    * 返回参数说明：<br /><br /><table><thead><th>参数</th><th>类型</th><th>说明</th></thead><tbody><tr><td>uid</td><td>string</td><td>用户id</td></tr><tr><td>name</td><td>string</td><td>用户昵称</td></tr><tr><td>groupid</td><td>int</td><td>用户组id: 1.管理员2.普通用户</td></tr><tr><td>reg_time</td><td>timestamp</td><td>注册时间</td></tr><tr><td>last_login_time</td><td>timestamp</td><td>最后登入时间</td></tr><tr><td>region</td><td>array|object</td><td>列表数据</td></tr></tbody></table><br />
