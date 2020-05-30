#include <stdio.h>
 
int main(void) {
	int number1=10,number2=2;
	float f_number_1 = 4.21, f_number_2= 3.456;
	double d_dumner_1 = 9.74158269, d_dumner_2 = 4785.98442254;
 
	//print the result for addition
	printf("number1+number2 = %d \n", number1+number2);
	printf("f_number_1+f_number_2 = %f \n", f_number_1+f_number_2);
	printf("d_dumner_1+d_dumner_2 = %f \n", d_dumner_1+d_dumner_2);
	printf("====================================================\n");
 
	//print the result for Subtraction	
	printf("number2-number1 = %d \n", number2-number1);
	printf("f_number_2-f_number_1 = %f \n", f_number_2+f_number_1);
	printf("d_dumner_2-d_dumner_1 = %lf \n", d_dumner_2+d_dumner_1);
	printf("====================================================\n");
 
	//print the result for Multiplication
	printf("number1*number2 = %d \n", number1*number2);
	printf("f_number_1*f_number_2 = %f \n", f_number_1*f_number_2);
	printf("d_dumner_1*d_dumner_2 = %lf \n", d_dumner_1*d_dumner_2);
	printf("====================================================\n");
 
	//print the result for Division
	printf("number1/number2 = %d \n", number1/number2);
	printf("f_number_1/f_number_2 = %f \n", f_number_1/f_number_2);
	printf("d_dumner_1/d_dumner_2 = %lf \n", d_dumner_1/d_dumner_2);
	printf("====================================================\n");
	return 0;
}