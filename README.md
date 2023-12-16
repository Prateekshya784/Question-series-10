# Question-series-10
1. (b) 35%
2. (c) Ask supervisor if she is aware of the situation.
3. (c) 80
4.PROGRAM TO CALCULATE NO OF VOWELS AND CONSONANTS.
 #include <stdio.h>
  int main()
 {
  	char str[100];
  	int i, vowels, consonants;
  	i = vowels = consonants = 0;
 
  	printf("\n Please Enter any String  ");
  	gets(str);
  	
  	while (str[i] != '\0')
  	{
  		if(str[i] == 'a' || str[i] == 'e' || str[i] == 'i' || str[i] == 'o' || str[i] == 'u' ||
		str[i] == 'A' || str[i] == 'E' || str[i] == 'I' || str[i] == 'O' || str[i] == 'U')  
		{
  			vowels++;  	
 		}
  		else
    		consonants++;
    	i++;
	}
    printf("\n Number of Vowels in this String = %d", vowels);  
	printf("\n Number of Consonants in this String = %d", consonants);   	
  
  	return 0;
}


QUESTION SERIES DAY 9

1.Cloud computing services offer shared resources such as servers, databases, and networks via the internet. Software as a Service (SaaS), Infrastructure as a Service (IaaS), and Platform as a Service (PaaS) are the three service models of cloud computing, each built to address specific business requirements.

2.(B) 1/11

3.(C) 10206

4.(A) 19

5.(D) 578

