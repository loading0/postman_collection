#wedbriver原理解析，postman调用chromedriver启动的服务端接口实例
## 本地运行环境准备
1. **在本地启动chromedriver**
    ```bash
    # postman创建环境变量
    remoteHost,  initial value: http://localhost:9515/session
    ```

2. **首先运行SeesionConnet接口**
    如果接口成功，便可以直接运行集合，或者依次单次运行每个接口。

3. **注意事项**
    chromedriver版本要与chrome浏览器版本相对应，不然建立session失败。