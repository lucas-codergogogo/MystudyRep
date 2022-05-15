### 编译运行
* 文件名和类名必须保持一致，且首字母大写（规范。首字母小写也可编译运行）
* 注意关键字符大小写，Java大小写敏感
* 字符串用双引号，字符用英文，中文可能编译不通过或执行时乱码
* 编译&运行需在文件目录下执行Javac xxx.java  &  java xxx
* 修改源码后需重新编译，编译后覆盖原class文件
* 一个Java源文件中可以没有主类或者公共类，但是如果有，只能有一个公共类，主类可以若干。有公共类的时候文件命名必须与公共类保持一致，如果没有公共类则可以自行命名。主类，即函数运行的一个入口，public static void main；公共类，public修饰。
```java
public class test{
    public static void main(String[] args){
        System.out.println("这是一个公共类，只能有一个");
    }
}
class A{
    public static void main(String[] args){
        System.out.println("这是一个主类，可以有多个");
    }
}
```

### 连接github
创建本地项目，并在本地创建仓库。VCS -> create Git Repository  
git commit提交代码到本地仓库  
在git创建代码仓库  
git push到远程仓库，第一次提交需关联Define remote，填入远程仓库http链接

### 