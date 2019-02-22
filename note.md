1. 豆瓣源安装python库
```shell
    pip install -i https://pypi.doubanio.com/simple/ --trusted-host pypi.doubanio.com django
```

2. 数据库引擎配置
```json
{
    "default": {
        "ENGINE": "django.db.backends.mysql",
        "NAME": "mxshop",
        "USER": "root",
        "PASSWORD": "123456",
        "HOST": "localhost",
        "PORT": 3306,
        "OPTIONS": {"init_command": "SET default_storage_engine=INNODB;"}
    }
}
```