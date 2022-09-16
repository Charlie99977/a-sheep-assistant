# a-sheep-assistant
羊了个羊助手，当前版本：`V2022.0.3Beta`

### 介绍

本项目旨在为你快速通关羊了个羊，上手需要一定动手能力以及门槛，请勿使用本程序恶意对游戏服务器持续造成压力，一切后果自负！！！，持续更新中...

所需工具推荐任选：：Fiddler【PC】、HttpCarry【Android】、Stream【iphone】

代码见 `main.py` ，配置文件 `config.py` 需要自行按需修改，具体怎么使用见下方使用教程，t 的值使用软件怎么获取这里不描述，自行探索，懂的都懂，感谢 issues 贡献方法老铁们，集思广益汇集力量，本内容会随时间发生改变，请自行分辨。

效果图： 建议完成时间控制在几分钟到几十分钟不等。

![效果图](./preview1.png)


### 使用教程
1、 克隆本仓库地址或者下载文件到本地，安装好 Python 环境
```shell
git clone https://github.com/Lcry/a-sheep-assistant.git
```
2、安装依赖
```python
pip3 install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```

3、打开 `config.py` ，修改抓取的必填t值，其他参数按照注释按需修改
```shell
    # 获取到的header中t值,必须修改为自己的
    "header_t": "eyxxxxxxxxx.xxxx",
    # 获取到的header中的user-agent值
    "header_user_agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/105.0.0.0 Safari/537.36 Edg/105.0.1343.33",
    # 设定的完成耗时，单位s，默认-1随机表示随机生成1s~1h之内的随机数，设置为正数则为固定
    "cost_time": -1,
    # 需要通关的次数，最大支持10，默认1
    "cycle_count": 1
```

4、执行即可
```python
python3 main.py
```

### 微信交流群
交流相关问题请进微信群：

6群

![扫码进交流群6](./weixinGroup6.png)

1、2、3、4群（已满）

### 免责声明

1. 本仓库发布的 `a-sheep-assistant` (下文均用本项目代替) 项目中涉及的任何脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。

2. 本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布，禁止直接改项目名二次发布。

3. 作者对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.

4. 请勿将本项目的任何内容用于商业或非法目的，否则后果自负。

5. 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本。

6. 以任何方式查看此项目的人或直接或间接使用本项目的任何脚本的使用者都应仔细阅读此声明。作者保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或本项目，则视为您已接受此免责声明。

7. 您必须在下载后的24个小时之内，从您的电脑或手机中彻底删除上述内容。

8. 本项目遵循GPL-3.0 License协议，如果本特别声明与GPL-3.0 License协议有冲突之处，以本特别声明为准。

9. 任何擅自改变计算机信息网络数据属于违法行为，本项目不提供成品可运行程序，仅做学习研究使用。

`您使用或者复制了本仓库且本人制作的任何代码或项目，则视为已接受此声明，请仔细阅读。`
