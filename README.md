# C-Class
IoT-2021-1 Class resource 한글 사용 가능
2021-03-02 IoT Class daily report

### C 언어 1강
2021-03-03 공부한 내용입니다 ^^!!
```
#include <stdio.h>

int main()
{
//	int a=1,b=10,result=0;
	
	// a = 10;
	// b = 20;
	// result = a + b;
//	scanf("%d %d",&a, &b);
//	
//	printf("a = %d\nb= %d\n",a,b);
//	
//	int t = a;		//변수 a의 초기값 보과용 
//	
//	while(a<=b)
//	{
//		result = result + a;
//		a = a + 1;
//	// result += a++;
//	}
//	
//	printf("[while]문을 이용한 누적 계산\n");
//	printf("a = %d\nb= %d\n",t,b);
//	printf("result = %d\n",result);
//	
//	result = 0; // result 값 초기화
//	for(int a = t; a<=b; a++)
//	{
//		result = result + a;
//	} 
//	
//	printf("[for]문을 이용한 누적 계산\n");
//	printf("a = %d\nb= %d\n",t,b);
//	printf("result = %d\n",result);
//	
//	
//	
//	return 0;
	
	int odd_sum = 0, even_sum = 0;
	int a, b;
	
	printf("두 수를 입력하세요\n");
	scanf("%d %d",&a, &b);
	
//	if(a%2==0) {
//		for(int i=a; i<b; i=i+2) {
//			even_sum += i;
//		}
//		for(int i=a+1; i<b; i=i+2) {
//			odd_sum += i;
//		}
//	}
//	else {
//		for(int i=a+1; i<b; i=i+2) {
//			even_sum += i;
//		}
//		for(int i=a; i<b; i=i+2) {
//			odd_sum += i; 
//		}
//	}

//	for(int i=a; i<=b; i++) {
//		if(i%2==0) {
//			even_sum += i;
//		}
//		else {
//			odd_sum += i;
//		}
//	} 
//	
//	printf("짝수의 합은 : %d\n", even_sum);
//	printf("홀수의 합은 : %d\n", odd_sum);

	int res1=0;
	int res2=0;
	int res3=0,res4=0,res5=0,res6=0,res7=0,res8=0,res9=0;

	for (int i = a; i<=b; i++) {
		if (i%9==0) res9 += i;
		else if(i%8 == 0) res8 += i;
		else if(i%7 == 0) res7 += i;
		else if(i%6 == 0) res6 += i;
		else if(i%5 == 0) res5 += i;
		else if(i%4 == 0) res4 += i;
		else if(i%3 == 0) res3 += i;
		else if(i%2 == 0) res2 += i;
		else res1 += i;
	
	}
	
	
	printf("9의 배수의 합 = %d\n", res9);
	printf("8의 배수의 합 = %d\n", res8);	
	printf("7의 배수의 합 = %d\n", res7);	
	printf("6의 배수의 합 = %d\n", res6);	
	printf("5의 배수의 합 = %d\n", res5);	
	printf("4의 배수의 합 = %d\n", res4);	
	printf("3의 배수의 합 = %d\n", res3);	
	printf("2의 배수의 합 = %d\n", res2);	
	printf("나머지수의 배수의 합 = %d\n", res1);	
	
	int n;
	
	printf("1부터 9까지의 정수를 입력하세요(0입력시 종료)if문으로 분 : ");
	scanf("%d", &n);
	
	while(n!=0) {
		if(n==1) {
			printf("%d : One\n", n);
		}
		else if(n==2) {
			printf("%d : Two\n", n);
		}
		else if(n==3) {
			printf("%d : Three\n", n);
		}
		else if(n==4) {
			printf("%d : Four\n", n);
		}
		else if(n==5) {
			printf("%d : Five\n", n);
		}
		else if(n==6) {
			printf("%d : Six\n", n);
		}
		else if(n==7) {
			printf("%d : Seven\n", n);
		}
		else if(n==8) {
			printf("%d : Eight\n", n);
		}
		else if(n==9) {
			printf("%d : Nine\n", n);
		}
		else {
			printf("잘못입력했습니다. 다시 입력하세요.\n");
		}
		printf("1부터 9까지의 정수를 입력하세요(0입력시 종료) : ");
		scanf("%d",&n);
	}
	
	printf("1부터 9까지의 정수를 입력하세요(0입력시 종료)switch문으로 분류 : ");
	scanf("%d", &n);
	
	while(n!=0) {
		switch(n) {
			case 1:	printf("%d : One\n", n); break;
			case 2:	  	printf("%d : Two\n", n); break;
			case 3: 	printf("%d : Three\n", n); break;
			case 4: 	printf("%d : Four\n", n); break;
			case 5: 	printf("%d : Five\n", n); break;
			case 6: 	printf("%d : Six\n", n); break;
			case 7: 	printf("%d : Seven\n", n); break;
			case 8: 	printf("%d : Eight\n", n); break;
			case 9: 	printf("%d : Nine\n", n); break;
			default:  	printf("잘못입력했습니다. 다시 입력하세요.\n");
		}
		printf("1부터 9까지의 정수를 입력하세요(0입력시 종료) : ");
		scanf("%d",&n);
	}

}
```
