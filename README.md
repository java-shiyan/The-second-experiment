# The-second-experiment
## 实验目的
用类描述计算机中CPU的速度和硬盘容量。要求java应用程程序中的CPU,PC,HardDisk,Test,其中Test是主类。熟悉类中的构造方法的创建。学会运用多种属性的类型。尝试定义属性和方法的修饰符，并且体会他们的具体用法。构建方法的过程中，尽量使方法更加合理（加入合理的逻辑判断）使程序逻辑更加完善。并且避免对类对象属性的直接调用，通过接口（方法）来控制属性。
## 实验内容
1.按照课本要求编写出PC,CPU,Test,HardDisk,四个类，其中Test是主类
2.每个类添加不少于2个属性，且属性的类型应该多种多样；每个类尝试定义属性的修饰符多样化。
3.尝试把多个类放置在不同的的包中，体会修饰符private的用法。
## 实验方法
1.CPU　

int speed;
double cap;
CPU();
CPU(int m);　　
void setCap　　
int getSpeed　　
void setSpeed(int speed)

2.PC

int money;　　
    int setmoney()
    void getmoney(int money)
    void setCPU(CPU cpu)
    void show
    
3.Test

String args[]

4.HradDisk

int amount;
    float cab;
     HardDisk() 
     void setCab
     int getAmount
     int getAmount
     void setAmount
## 核心代码
构造方法的使用
```
    CPU() {

    }
    CPU(int m) {
    }
```
属性的定义
```
　　int amount;
    float cab;
    double cap;
```
对象创建
```
　　　　CPU cpu = new CPU();
        HardDisk HD=new HardDisk();
        PC pc =new PC();
```
方法使用
```
　　　　cpu.setSpeed(2200);
        cpu.setCap(200);
        HD.setAmount(200);
        HD.setCab(1.0f);
        pc.setCPU(cpu);
        pc.setHardDisk(HD);
        pc.show();
```
##　实验结果
输出　ＣＰＵ的速度：２２００
硬盘容量：２００

##　实验感想
通过这次实验，我对构造方法的理解加深了，应用也越来越得心应手。对于类与类之间的关系也更加明确，同时，对象的创建与方法引用也有了更深的理解，发现错也渐渐变得有迹可循，会快速的修正了。
同时，也体验了修饰符多样化和ｐｒｉｖａｔｅ的用法，很奇妙。



