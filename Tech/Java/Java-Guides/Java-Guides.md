# Java 避坑指南

## 对象拷贝

避免用 Apache Beanutils 进行属性的 copy。 说明：Apache BeanUtils 性能较差，可以使用其他方案比如 Spring BeanUtils：

```java
//apach
BeanUtils.copyProperties(to, from)
// spring
BeanUtils.copyProperties(from, to);
```