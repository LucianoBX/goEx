# 客户信息系统
## 项目需求
1. 模拟基于文本界面的《客户信息管理软件》
2. 该软件能够实现对客户对了的插入、修改、删除（基于切片），并能够打印客户明细

## 程序架构
- M 模型，业务逻辑custom.go
- V 界面, UI逻辑，customView.go
- C 控制器，输入逻辑 customService.go 

## 项目界面（V）
```
------------客户信息管理软件--------------

            1 添加客户
            2 修改客户
            3 删除客户
            4 客户列表
            5 退    出

请选择(1-5):
------------------------------------------
```

- 添加客户
```
----------------添加客户-----------------
姓名：张三
性别：男
年龄：30
电话：010-56253825
邮箱：zhang@abc.com
---------------添加完成------------------
```

- 修改客户
```
---------------修改客户------------------
请选择待修改客户编号（-1推出）：1
姓名（张三）：<直接回车表示不修改>
性别（男）
年龄（30）
电话（010-56253825）
邮箱（zhang@abc.com）：zsan@abc.com
---------------修改完成------------------
```

- 删除客户
```
---------------删除客户-------------------
请选择待删除客户编号（-1推出）：1
确认是否删除（Y/N）:Y
---------------删除完成-------------------
```

- 客户列表
```
----------------客户列表-----------------
编号	姓名	性别	年龄	电话		邮箱
1	张三	男	30	010-56253825	abc@email.com
2	李四	女	23	010-86889988	lisi@mail.cn
3	王五	男	55	020-33445521	wang@qq.aha
-----------------完全显示----------------
```

## 主要功能
### 客户列表展现
1. 主菜单显示

2. 显示客户列表
编写list方法，返回客户信息（切片）

3. 添加客户


4. 删除客户
M
V
C: Delete Method
	FindById Method
 

