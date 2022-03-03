# 3u-conditionals

Create a file called **valid.py** and upload it to this repository. In that file write a program that takes in a date in the form DD/MM and outputs 'valid date' if it is valid and 'not valid date' if it is not (mind the case). Assume 29/02 and 28/02 are both valid for now.

**Sample Input 1**
```
25/01
```

**Sample Output 1**

```
valid date
```

**Sample Input 2**

```
31/04
```

**Sample Ouput 2**

```
not valid date
```

---
Create a file called **email.py** and upload it to this repository. In that file write a program that takes in an email address and checks to see if it is a valid pdsb staff email. PDSB staff emails are either in the form p0######@pdsb.net or p00######@pdsb.net where ###### represents a 6 digit employee number. The employee number cannot start with 0. If it is a valid saff email, output 'valid staff email'. If it is not a valid staff email, output 'not a valid staff email'.


**Sample Input 1**
```
2cool4school@yahoo.com
```

**Sample Output 1**

```
not a valid staff email
```

**Sample Input 2**

```
p012345@pdsb.net
```

**Sample Ouput 2**

```
not a valid staff email
```

**Sample Input 3**

```
p0123456@pdsb.net
```

**Sample Output 3**
```
valid staff email
```

---
Create a file called **student_number.py** and upload it to this repository. In that file write a program that takes in a student number and outputs the possible corresponding grade(s). A student number is composed of all digits and is 6 or 7 digits long. 

If your student number is 6 digits and starts with a 6 or 7 then you might be in grade 9.

If your student number is 6 digits and starts with a 7 or 8 then you might be in grade 10.

If your student number is 6 digits and starts with a 8 or 9 then you might be in grade 11.

If your student number is 6 digits and starts with a 9 or 7 digits and starts with a 10 then you might be in grade 12.

Any other number is an invalid student number - output 'invalid'.

**Sample Input 1**
```
835241
```

**Sample Output 1**
```
Grade 10 or 11
```

**Sample Input 2**
```
984321
```

**Sample Output 2**
```
Grade 11 or 12
```

**Sample Input 3**
```
1198765
```

**Sample Output 3**
```
invalid
```

**Sample Input 4**
```
1086197
```

**Sample Output 4**
```
Grade 12
```
