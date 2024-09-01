# Java 算法题编码环境

在 IDEA 编辑器搭建 Java 算法题编码环境，提供 LeetCode 和 ACM 模式的类文件与 IDEA 实时模板配置。

## 文件选择

- LeetCode 使用 Solution 类
  - 用法：把题目代码复制覆盖 `import java.util.*;` 下方内容，编写代码
- AcWing 和牛客等 acm 模式的平台，使用 Main 类
  - 用法：把代码重置，直接编写代码

## 实时模板配置

编辑器按需配置实时模板。因 IDEA 实时模板不支持配置到项目目录中，且内容不多，仅记录在说明文件。

选中下方代码，菜单 Code -> Save as Live Template ，设置对应的适用于类型。

### sin: 使用 Scanner 输入

右下角 Applicable in 选择: Java - Expression

```
Scanner sc = new Scanner(System.in);
```

### swap: 交换数组元素

右下角 Applicable in 选择: Java - Declaration

```
static void swap(int[] a, int i, int j) {
    int t = a[i];
    a[i] = a[j];
    a[j] = t;
}
```