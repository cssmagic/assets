#方案说明
###警告！以下方案水分含量过高，完全没有干货，请大家谨慎阅读。
	- assests/
		- web/   [ 第一层按平台划分 ]
		- wap/ 
			- lib/   --前端底层库和组件
			- common/  --全站通用资源
				- stylesheets/  --样式表
				- images/  --图片
				- scripts/  --脚本
				- views/   --视图(jade/jedi/html)
            - module/  --多个业务模块公用的子功能
			- viewad/  --业务划分
				- README.md  --写清楚该业务的范围
				- common/  --业务通用资源
				- module/  --多个页面公用的子功能
				- page/ -- 有url的页面
					- {url}/  -- ？？不确定是否该这么命名
						- README.md
						- stylesheets/
						- images/
						- scripts/
						- views/ 
			- weishop/  --（业务）
			- page/ --尚不清楚该放在哪个业务下的页面

##好处：
- 可以根据类型创建文件夹，比如可以用 yo 来新建一个 viewad 下的依赖某某 module 的 page 文件夹

##P.S.
这是一个不开发镐京的童鞋参照了师兄的方案后 YY 出来的开发流程（看吧，我把 views 都放进来了，多么不靠谱啊啊）。此举只是为了响应鹏哥号召，为该 repo 抛砖引玉、攒点人气（不然这种完全不顾实现的可能性和编译部署阶段难度的方案我为什么只写好处捏~）。

###P.P.S
待我勤劳起来再补上示例文件吧 > <
