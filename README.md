#include<stdio.h>
struct book{
char name[20];
short price;

};
 int main()
{
	struct book b1={"c++",60};
	struct book*pb=&b1;
	
	
		printf("%s\n",(*pb).name);
		printf("%d\n",(*pb).price);
	
}

