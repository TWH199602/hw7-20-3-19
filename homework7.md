# 利用Xcode编写简易的C语言求差程序
int main(void)
{
    int n1, n2;
    int wa;

    puts("请输入两个整数。");
    printf("整数1:"); scanf("%d", &n1);
    printf("整数2:"); scanf("%d", &n2);

    wa = n1 -n2;

    printf("它们的差是%d\n", wa);

    return 0;
}

* 将上述代码输入编辑区域；
* 点击左上角的运行键；
* 在右下角输入参数44和22；
* 点击enter键得出结果；
![运行结果](https://github.com/TWH199602/picture1/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202020-03-19%20%E4%B8%8B%E5%8D%8810.02.53.png)
可见运行结果为22
另外如果第一个参数为整数，第二个参数带小数点
![带小数点](https://github.com/TWH199602/picture1/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202020-03-19%20%E4%B8%8B%E5%8D%8810.11.03.png)
在第一个参数为19，第二个参数为10.8时，输出的结果依然为9；

