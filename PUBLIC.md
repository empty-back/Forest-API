# 页面公共部分索引
1.  左侧地区列表

    * 简要描述：
    地图左侧所有地区列表
    * 请求URL：
    http://xx.com/api/public/region
    * 请求方式：
    POST
    * 参数：<br /><br /><table><thead><th>参数</th><th>必选</th><th>类型</th><th>说明</th></thead><tbody><tr><td>username</td><td>必选</td><td>string</td><td>用户名</td></tr><tr><td>password</td><td>必选</td><td>string</td><td>密码</td></tr></tbody></table>
    * 返回示例：<br /><br /><pre><code>{
    "error_code": 0,
    "data": {
      "uid": "1",
      "username": "12154545",
      "name": "james",
      "groupid": 2 ,
      "reg_time": "1436864169",
      "last_login_time": "0",
      "region": [{
			"name": "坝上",
			"child": []
		},
		{
			"name": "东北林区",
			"child": ["大兴安岭", "小兴安岭", "长白山"]
		},
		{
			"name": "西北林区",
			"child": ["横断山区"]
		},
		{
			"name": "南方林区",
			"child": ["秦岭", "淮河", "云贵高原"]
		}
	]
    }
  }</code></pre>
    * 返回参数说明：<br /><br /><table><thead><th>参数</th><th>类型</th><th>说明</th></thead><tbody><tr><td>uid</td><td>string</td><td>用户id</td></tr><tr><td>name</td><td>string</td><td>用户昵称</td></tr><tr><td>groupid</td><td>int</td><td>用户组id: 1.管理员2.普通用户</td></tr><tr><td>reg_time</td><td>timestamp</td><td>注册时间</td></tr><tr><td>last_login_time</td><td>timestamp</td><td>最后登入时间</td></tr><tr><td>region</td><td>array|object</td><td>列表数据</td></tr></tbody></table><br />
    
1.  顶部导航列表
    * 简要描述：
    所有页面顶部导航菜单
    * 请求URL：
    http://xx.com/api/public/menu
    * 请求方式：
    POST
    * 参数：<br /><br /><table><thead><th>参数</th><th>必选</th><th>类型</th><th>说明</th></thead><tbody><tr><td>username</td><td>必选</td><td>string</td><td>用户名</td></tr><tr><td>password</td><td>必选</td><td>string</td><td>密码</td></tr></tbody></table>
    * 返回示例：<br /><br /><pre><code>{
    "error_code": 0,
    "data": {
      "uid": "1",
      "groupid": 2 ,
      "menu": [{
			"name": "无人机管理",
			"href": "#"
		},
		{
			"name": "摄像头管理",
			"href": "#"
		},
		{
			"name": "车辆定位",
			"href": "#"
		},
		{
			"name": "告警历史",
			"href": "#"
		}
	]
    }
  }</code></pre>
    * 返回参数说明：<br /><br /><table><thead><th>参数</th><th>类型</th><th>说明</th></thead><tbody><tr><td>uid</td><td>string</td><td>用户id</td></tr><tr><td>groupid</td><td>int</td><td>用户组id: 1.管理员2.普通用户</td></tr><tr><td>menu</td><td>array|object</td><td>菜单列表</td></tr></tbody></table><br />
