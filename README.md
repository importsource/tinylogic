# TinyLogic
TinyLogic  is a flyweight microservice container.

You can add some code to the doIt method,then all is ok.

The `obj` field  push content to client. eg. your browser. the format of data is json.


###三步写一个TinyLogic服务。

第一步：新建一个maven项目。然后写个这样的类：
```java
@MicroService(value="/apps/hello2")
public class Hello2 extends DefaultHttpHandler{
	@Override
	public void doIt(Request request, Response response) {
		obj =  "hello world";
	}
	
}
```

第二步：打包项目。把jar复制到｀tinylogic\webapp｀下。

第三步：双击“start.cmd”。OK啦！




![](doc/image/tlogic-welcomepage-d.png)

![](doc/image/tlogic-demo-d.png)




