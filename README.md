# matrix-parent-dependencies

该工程是`Matrix`项目Java组业务开发基础框架，使用该工程统一管理业务代码基础依赖，如`Spring`版本、`Dubbox`版本等。


## 快速使用

使用该基础框架需要如下步骤：

1.创建业务工程结构

工程结构图如下：


2.根工程引入

    <parent>
        <groupId>com.le.matrixframework</groupId>
        <artifactId>matrix-starter-parent</artifactId>
        <version>1.0-SNAPSHOT</version>
        <relativePath/>
    </parent>

3.service工程引入下面dependency

    <dependency>
        <groupId>com.le.matrixframework</groupId>
        <artifactId>matrix-parent-starter-service</artifactId>
    </dependency>

4.facade工程引入下面dependency

    <dependency>
        <groupId>com.le.matrixframework</groupId>
        <artifactId>matrix-parent-facade</artifactId>
    </dependency>

5.web工程引入下面dependency

    <dependency>
        <groupId>com.le.matrixframework</groupId>
        <artifactId>matrix-parent-starter-web</artifactId>
    </dependency>


## 使用注意事项
* 建议以后所有业务代码使用该工程，由该工程统一管理业务工程基础依赖，对于特殊依赖，由具体业务完成；
* 注意查看[changelog](CHANGELOG.md)，浏览`matrix-parent-dependencies`工程每个版本变化。

## 版本更新说明

请查看[changelog](CHANGELOG.md)
