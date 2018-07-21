5 4  // The rows(n)  and columns(m)  of the coefficient matrix C

/*matrix C*/
1 1 1 1
1 2 3 4
1 3 5 6
1 4 7 9
3 5 4 7

34 243 19 90  //The data you wanna encode,which is a column vector of m rows

1  2  3  5  // The lines you wanna pick for decoding.  



/*Another case of test*/

3  2   // The rows(n)  and columns(m)  of the coefficient matrix C
/*matrix C*/
1   1
1   2
1   3

6  89 //The data you wanna encode,which is a column vector of m rows

1  3  // The lines you wanna pick for decoding.  In this case we pick line1and line3 ,which means we use
/*
	1    1
	1    3
  to decode the encoded data
*/


NOTE: The program will run forever until it reaches EOF(end of file) , so you can try as many test cases as
you want  to examine the  correctness of this program





