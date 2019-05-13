# Switch:

```c
#include <stdio.h>
int main()
{
	// Switch - החלפה בין תוכן של משתנים

	int a = 5, b = 8, temp=0;

	printf("a = %d\tb = %d\n",a,b);

	temp = a;   // a = 5, b = 8,temp=5
	a = b;      // a = 8, b = 8,temp=5
	b = temp;   // a = 8, b = 5,temp=5

	printf("a = %d\tb = %d\n", a, b);

}
```
#scanf - קלט מהמשתמש
```c
#include <stdio.h>
int main()
{
	// scanf - קלט מהמשתמש
	int num;
	printf("Enter number:\n");
	scanf("%d", &num);
	printf("num = %d\n", num);
}
```
# if - משפט תנאי
 כאשר מה שבתוך הסוגריים מתקיים - נכנס לתוך הלולאה. 
if - אם המשתמש גדול או שווה ל-18 הוא יוכל להכנס
else if - כאשר התנאי הראשון לא מתקיים, אנחנו נבדוק עוד אפשרות.


## אפשרויות

* && - AND - שני התנאים חייבים להתקיים
* || - OR - מספיק שתנאי אחד יתקיים

```c
#include <stdio.h>
int main()
{
	int age;
	printf("Welcome! Enter your age please\n");
	scanf("%d", &age);
	// IF - אם
	if (age>18 || age==18)
	{
		printf("Welcome\n");
	}
	else if (age<18)
	{
		printf("Bye\n");
	}
}
```
# אנשים בכיתה וגילאים שלהם
```c
#include <stdio.h>
int main()
{
	float Adir = 22.5, Ori = 19, Avishag = 20, Liad = 25;
	printf("---------CLASS 1 ----------\n");
	printf("Adir is    %.1f years old\n", Adir);
	printf("Ori is     %.1f years old\n", Ori);
	printf("Avishag is %.1f years old\n", Avishag);
	printf("Liad is    %.1f years old\n", Liad);


}
```


# Increment and decrement (העלאה באחד, הפחתה באחד)
* (x = x+1) =  x++
* (x = x-1) = x--

```c
#include <stdio.h>
int main()
{
	int x;
	// while = כל עוד
	printf("Enter number:\n");
	scanf("%d", &x);
	while (x>0)
	{
		printf("x = %d \n",x);
		x--;
	}
	// בסוף x=0
	while (x < 5)
	{
		printf("*****\n");
		x++;
	}
	
}
```




