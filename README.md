# Grade
akshita
#include<stdio.h>

int main(){
	int x;
	printf("Enter marks:");
	scanf("%d",&x);
	switch(x/20){
	case 5:
		printf("Grade A");
		break;
	case 4:
		printf("Grade B");
		break;
	case 3:
		printf("Grade C");
		break;
	case 2:
		printf("Grade D");
		break;
	case 1:
		printf("Grade F");
		break;
	}
}
