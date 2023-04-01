# First-and-Follow

OUTPUT:

Enter no. of terminals: 5
Enter the terminals :
+
*
a
(
)
Enter no. of non terminals: 5
Enter the non terminals :
E
B
T
Y
F
Enter the starting symbol: E
Enter no of productions: 5
Enter the productions:
E->TB
B->+TB/@
T->FY
Y->*FY/@
F->a/(E)
   Non Terminals           First               Follow       
         E               {'a', '('}          {')', '$'}     
         B               {'+', '@'}          {')', '$'}     
         T               {'a', '('}       {')', '+', '$'}   
         Y               {'*', '@'}       {')', '+', '$'}   
         F               {'a', '('}     {'*', ')', '+', '$'}
![image](https://user-images.githubusercontent.com/96488109/229266808-7e50bad2-ec14-454b-9306-cf5b339eafb5.png)
