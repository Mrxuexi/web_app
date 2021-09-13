# web_app

## Go Web开发脚手架

CLD设计模式

### 使用的工具:

> Viper配置管理工具,	/spf13/viper  
>
> Zap日志库,	go.uber.org/zap  
>
> sqlx,	/jmoiron/sqlx"  
>
> gin,	/gin-gonic/gin  
>



### 脚手架结构:

> ├── config.yaml			 //配置文件  
> ├── controllers		 	 //控制层  
> ├── dao						  //持久层  
> │   ├── mysql				//mysql集成  
> │   │   └── mysql.go	  
> │   └── redis				 //redis集成  
> │       └── redis.go  
> ├── go.mod  
> ├── go.sum  
> ├── logger					//ZAP日志  
> │   └── logger.go
> ├── logic					    //业务层(逻辑层)  
> ├── main.go			     //main  
> ├── models				  //model层,结构映射数据库   
> ├── pkg				   	  //外部工具层  
> ├── README.md  
> ├── routes				   //路由层  
> │   └── routes.go  
> ├── settings				 //config配置处理   
> │   └── settings.go  
> └── web_app.log		//日志记录  

