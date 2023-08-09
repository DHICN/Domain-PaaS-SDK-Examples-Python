# Iot服务接入实测数据案例说明 
- 使用前请先确保已安装sdk包：pip install dhicn-domain-paas-sdk-python\

在Iot服务接入实测数据案例中包括了5个案例文件、1个用户信息文件、1个设备信息文件，如下图所示。\
![Alt text](images\image-1.png)

案例中的接口调用都需要携带认证信息，即登录成功后返回的token。如需试用，请联系我们 [DHI 中国 业务中台](https://online-products.dhichina.cn/) 获取使用许可和认证信息。

## 实测数据的接入有三种方式，分别是http、opcua、mqtt
- http协议推送数据参考 synchronous_data_http.ipynb
- opcua数据同步参考 synchronous_data_opcua.ipynb
- mqtt协议推送数据参考 synchronous_data_mqtt.ipynb

除了以上三个案例文件以外，还有登录和上传设备数据的案例，分别是login.ipynb和upload_device_data.ipynb，在调用案例前，请先通过login.ipynb完成登录。upload_device_data.ipynb主要是在上传"data\资产配置.xlsx"，目前已上传用于测试的数据，如有需要，可自行修改excel中的数据后重新上传。

## login.ipynb 内容如下
![Alt text](images\image.png)
## synchronous_data_http.ipynb 内容如下
![Alt text](images\image-2.png)
## synchronous_data_opcua.ipynb 内容如下
![Alt text](images\image-3.png)
## synchronous_data_mqtt.ipynb 内容如下
![Alt text](images\image-4.png)
