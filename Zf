#include<stdio.h>
#include<string.h>
int main()
{
    printf("Please input a sentence:\n");
	char s[1000];
	gets(s);
	printf("Please input a wozd:\n");	
	char w[10];
	gets(w);
	strlwr(s);
	strlwr(w);
	int wlen=strlen(w);
	int slen=strlen(s);
	int cnt=0;
	for(int i=0;i<=slen-wlen;i++)
	{
	    char tempw[wlen+1];
	    tempw[wlen+1]='\n';
		for(int j=0;j<wlen;j++) 
		tempw[j]=s[i+j];
		if(strcmp(tempw,w)==0)
		cnt++;
    }
    printf("%d",cnt);
    return 0;
}
