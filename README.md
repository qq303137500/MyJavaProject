# 英臻车联3.0>代码>后台

IgenVehideAnalysis:接入分析项目,主要负责数据的接入,轨迹存储,报警等业务.
	IgenVehicleAnalysisEb(作废):专门为二轮车创建的接入项目
	
IgenVehideDataMove:数据迁移项目,为后期2.0平台客户迁入3.0专有的业务,成功案例客户瑞博恩.

IgenVehidePlatform:整个平台项目集合,里面会详细介绍平台项目的构成
	IgenVehicleAdmin:项目服务管理,暂时只在测试环境使用,未上商用
	IgenVehicleBase:基础项目-orm层
	IgenVehicleConfig:配置中心
	IgenVehicleGateWay:网关中心
	IgenVehicleServer:客户平台项目模块中心
	IgenVehicleService:平台项目服务集合
		IgenElectricMotoCollection:二轮车集成项目
		IgenElectricMotoUser:二轮车项目之用户模块
		IgenVehicleServiceAlarm:报警相关服务
		IgenVehicleServiceApi:对外开放接口相关服务
		IgenVehicleServiceCollection:汽车金融集成项目
		IgenVehicleServiceComm:共用模块
		IgenVehicleServiceDemo:demo模块,早期创建
		IgenVehicleServiceDevice:设备相关服务
		IgenVehicleServiceDictionary:字典相关服务
		IgenVehicleServiceError:错误码相关服务
		IgenVehicleServiceFence:围栏相关服务
		IgenVehicleServiceFile:文件相关服务
		IgenVehicleServiceInsurance:保险相关服务(C端)
		IgenVehicleServiceNotice:通知相关服务
		IgenVehicleServiceOperation:客户平台权限操作项目集合服务
		IgenVehicleServiceOrder:客户工单相关服务
		IgenVehicleServiceOss:运营平台服务
		IgenVehicleServiceOssRy:运营平台服务(若依新版交互)
		IgenVehicleServicePlug:基础插件相关服务
		IgenVehicleServicePlugOss:oss插件相关服务
		IgenVehicleServiceReportForms:客户报表相关服务
		IgenVehicleServiceRms:进销存相关服务
		IgenVehicleServiceTest:Test模块,早期创建
		IgenVehicleServiceToken:Token,早期创建
		IgenVehicleServiceUser:User模块,早期创建
	IgenVehicleWeb:前期前后端项目不分离的demo
	
ras:专门为融合创建的风控项目

