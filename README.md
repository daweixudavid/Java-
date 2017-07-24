报错信息
Multiple markers at this line
	- No enclosing instance of type xu is accessible. Must qualify the allocation with an enclosing 
	 instance of type xu (e.g. x.new A() where x is an instance of xu).
	- The value of the local variable te is not used
     
解决方法
test1 te = new test().new test1();
test是父类  test1是子类
错误写法
public static void main(String[] args) {
	 test1 te=new test1();
	}
    
    
