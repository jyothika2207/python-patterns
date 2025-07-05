# python-patterns(Sand time)
n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if i==0 or i==n-1 or i==j or i+j==n-1:
            print("*",end=' ')
        else:
            print(' ',end=' ' )
    print()

    OUTPUT===
  enter the size 8
* * * * * * * * 
  *         *   
    *     *     
      * *       
      * *       
    *     *     
  *         *   
* * * * * * * * 




# python-patterns(Butterfly)
n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if j==0 or j==n-1 or i==j or i+j==n-1:
            print("*",end=' ')
        else:
            print(' ',end=' ' )
    print()

output===
enter the size 8
*             * 
* *         * * 
*   *     *   * 
*     * *     * 
*     * *     * 
*   *     *   * 
* *         * * 
*             * 




# python-patterns(rectangle)
n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if i==0 or i==n-1 or j==0 or j==n-1:
            print("*",end=' ')
        else:
            print(' ',end=' ' )
    print()


    OUTPUT=====
   enter the size 8
* * * * * * * * 
*             * 
*             * 
*             * 
*             * 
*             * 
*             * 
* * * * * * * *



    
