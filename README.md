# Java-IDValidator

```java
//初始化一个实例
IDValidator validator = new IDValidator();

//验证身份证是否有效
validator.isValid("152103198909218022")

//分析详细信息
validator.getInfo(id15)

//生成18位身份证号
validator.makeID(false)

//生成15位身份证号
validator.makeID(true)
```