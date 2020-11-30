# HelloWorld
/*
变量定义格式：
	数据类型 变量名 = 变量值；

基本数据类型
	byte,short,int,long,float,double,char,boolean

变量的使用
	取值格式：变量名 = 变量值
	
long类型的变量定义的时候，为了防止整数过大，后面要加L；
float类型的变量定义的时候，为了防止类型不兼容，后面要加F；
*/
public class DemoA{
	public static void main(String[] args)
	{
		int a;
		a=10;
		System.out.println(a);
		a=30;
		System.out.println(a);
		boolean b;
		b = true;
		System.out.println(b);
		
		
		//自动类型转换
		int m=30;
		double d=m;
		System.out.println(d);
		
		//强制类型装换
		int k = (int)44.3;
		System.out.println(k);
	}
}
