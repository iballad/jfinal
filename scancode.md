1. 运行 JFinal.main() 来调试 JFinal，查看其运行加载流程

2. 

参考资料：

	http://download.jfinal.com/upload/2.2/jfinal-2.2-manual.pdf


(为阅读源码方便，摘自网络文档于此)

- JFinalFilter 框架入口，也是接管所有请求的地方
- ActionMapping 映射url至action
- ActionHandler 接管动态请求，控制 action + interceptor + render 执行流程
- ActionInvocation 执行interceptor + action
- Render 渲染视图
- ActiveRecord 数据库支持
- JFinalConfig 系统配置
- Validator 校验