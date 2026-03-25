## NAME: LATCHAYA PRIYAN S
## REG NO: 212224230139

### Aim:
To write a C Program for array of structure to check eligibility for the vaccine person age above 6 years of age.

### Algorithm:
1.	Declare structure eligible with age (integer) and n (character array)
2.	Declare variable e of type eligible
3.	Input age and name using scanf, store in e
4.	If e.age <= 6
-	Print "Vaccine Eligibility: No"
Else
-	Print "Vaccine Eligibility: Yes"
5.	Print details (e.age, e.n)
6.	Return 0
 
### Program:

```
#include <stdio.h>
struct Person {
    int age;
    char name[50];
}per;

int main() {
    scanf("%d %s",&per.age,per.name);
    
    printf("Age:%d\n",per.age);
    printf("Name:%svaccine:%d\n",per.name,per.age);
    if (per.age <= 18) {
        printf("eligibility:no\n");
    } else {
        printf("eligibility:yes\n");
    }
    
    return 0;
}
```

### Output:

<img width="662" height="197" alt="image" src="https://github.com/user-attachments/assets/1220f1d7-66af-4aa4-8094-4bf933f23125" />


### Result:
Thus, the Program is verified successfully. 
