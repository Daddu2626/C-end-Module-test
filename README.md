# C-end-Module-test

Name : Pradyumna Rajkumar Pudke
Batch :24july 2026
FRN No: Frn 18J0726/
set : Set B



question no.1:


#include<stdio.h>
#include<string.h>
int main(){
	char str [100];
	int i=0, word=0;
	
	printf("Enter a string: ");
	scanf("%s",&str);
	
	while(str[i]!='\0'){
		
		if (str[i]!=' ' || str [i]=='/n'){
		
		
		word++;
	}
	
	i++;
	
}
	printf("words of a string : %d", word);
	return 0;
	
}


question no 2:

#include<stdio.h>
int main(){
	
	int n, i;
	int term=0;
	
	printf("Enter n: ");
	scanf("d",&n);
	
	for(i=1;i<=n;i++){
		
		term=term*10+1;
		printf("%d",term);
		
		if(i<n)
		printf("+");
	}
	return 0;	
}t
