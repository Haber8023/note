# SpringBoot入门

<u>docs.spring.io</u>

## 一、配置要求

java 8+，maven 3.3+



## 二、配置步骤

### 1.创建maven项目

### 2.引入依赖

pom.xml

### 3.创建主程序

```java
@SpringBootApplication
public class Application {

	public static void main(String[] args) {
		SpringApplication.run(Application.class, args);
	}
```

### 4.编写业务

```java
@RestController
public class HelloController {

    @RequestMapping("/hello")
    public String hello() {
        return "Hello 52zhiyuan！";
    }
}
```

### 5.测试

直接运行main方法

### 6.简化配置

application.properties

### 7.简化部署

打成jar包直接在目标服务器执行即可



## 三、主要注解

@SpringBootApplication：主程序类

@Controller：Controller类

@RequestMappping("/request")：请求注解

@ResponseBody：返回注解

@RestController：返回Controller类





###  