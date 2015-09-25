# Venturesity


 Prerequisites : Data-Structures, Hashing
 
 
 Explanation : 
      We can use a 5-D array to do a successful hashing of the names of customers, as, 
      the maximum length of their names is 5.
      Let 'a' be represented as 1,' b' as 2 and so on... 'z' as 26.
      Hash[i][j][k][l][m]=1 if the corresponding name is present or else it will be 0.
      For example, if 'nandu' is present, Hash[14][1][14][4][21]=1. Note that for names of
      length less than 5, last few of i,j,k,l,m will be 0. For example, if 'rani' is present,
      Hash[18][1][14][9][0]=1
      Now we can traverse the Hash array using 5 nested for-loops. 
      This traversal will be such that lexicographically smaller words will be accessed first
      ( See Author's or Tester's solution for more clarity ).
       
 
 Time Complexity :
   Constant Time to traverse the entire Hash Array = 27^5 = 15 * 10^6 Approximate.
 

