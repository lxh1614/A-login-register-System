    
    简单的登录注册系统，使用了数据库sqlserver、单例模式、门面模式、正则表达式以及图形化界面开发等知识。

1、在登录界面，可以登录或者注册用户。 注册用户界面，按照正则表达式规定的格式要求来输入信息，若有误，则重新输入。

2、点击注册，首先连接SQLserver数据库，连接成功则会判断该用户名是否已经存在，若存在，则给出提示。反之则进行注册。 

3、登录界面，点击登录按钮时，首先与数据库建立连接。按照用户名和密码来向数据库中查找，若有，则登录成功。反之给出提示。

4、利用单例模式，实现了只创建类SQLserver的一个对象，大大节省了内存开销。

5、利用了门面模式，使客户端与子系统并不相互依赖，提高了系统的灵活性。

6、基于此，可以进行大量的拓展功能。

author:ywq

email：956283501@qq.com