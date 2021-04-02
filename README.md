# codebubbling-code-generator
code-generator 代码生成器 在线管理  插件 支持枚举 web spring springboot mybatis 


# 代码生成器

## 痛点

- 配置不共享，升级管理困难
- 手动合代码
- 生成的代码没做隔离，升级困难
- 只支持简单模型
- 只支持生成后端代码
- 枚举手动修改

## 特性

### 通用特性

- 模块配置中心化存储
- 支持多模型， 简单列表，一对一列表，一对多列表，树结构，图表等
- 生成的代码与业务代码分离
- 代码模版支持在线拓展管理
- 生成后台管理代码
- 在线管理
- 生成代码实时浏览
- 支持多数据源配置
- 支持多人协作，产品定义字段， 后端定义java模板， 前端定义react模板
- 支持插件，java插件， react插件，ios插件， android插件，sql插件，后台管理插件
- 数据导出功能
- 下拉栏功能

### java特性

- DO，DTO，VO之间转化采用mapstruct
- 本地缓存采用Caffeine
- 支持自动生成枚举
- 字段校验
- 生成根据外键查询
- 生成查询模型
- 分页查询

### 前端特性

## 基础模块

- 模块管理
- 插件管理
- 模版管理
- 源码管理
- 字段类型管理

## 功能模块

### 字段类型管理

- 数字
- 浮点数
- 字符
- 字节
- 字符串
- 枚举
- 是否
- 日期
- 时间
- 日期时间
- 时间戳
- 一对一
- 一对多

### 插件管理

- 插件名称
- 插件配置
- 插件模板列表

### 模块管理

#### 基础配置

- 模块名称
- 类型

#### 字段管理

- 字段名称
- 字段code
- 类型
- 长度
- 必填
- 说明
- placeHolder
- select

##### 复杂类型

- 一对一，一对多
- 类型名称

#### 插件配置

- 选择插件

#### 代码管理

- 历史代码列表

### 模板管理

- 名称
- 路径
- 版本
- 类型
- 模板

## 插件

### java插件

#### 配置

- 包名
- 模型名称
- author
- 分页
- 数据源
- 缓存配置
- 微服务支持
- 分页
- 接口path

#### 字段管理

- 名称
- 枚举

#### 模板

- controller
- service
- serviceImpl
- dao
- xml
- vo
- dto
- do
- convertor

### sql插件

- 配置：表名，索引
- 模板：create语句

### ...

## 表结构

### 类型表

简单列表

### 模板表

简单列表

### 插件表

复杂列表

#### 插件字段模板表

一对多

#### 插件代码模板表

一对多

### 模块表

复杂列表

#### 模块字段表

一对多

#### 模块插件表

一对多

##### 模块插件字段表

一对多对多

##### 模块插件代码表

一对多对多



