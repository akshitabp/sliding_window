**OS VERSION**

     20H2
     
**RUNTIME ENVIRONMENT**

     JRE - JAVA RUNTIME ENVIORNMENT
     
**LANGUAGE VERSION**

     JAVA Version - 1.8.0_92
        
**CODE EXPLANATION**

     Variables used:
     r - No. of request
     s - Sliding window time period
     len - No. of timestamp
     arr[] - sequence of timestamp
     count - Used to count the time period reached. //initialized inside function.
     
     Function used:
     sliding(int s, int r, int arr[])
     
     Loop used:
     for loop to iterate inside the array
     If number of iteration is less than or equal to r,  allow the timestamp value in the array.
     If number of iteration is between r and s, block the timestamp value in the array.
     Once the count value exceeds s, set count value to 1.

**SAMPLE INPUT AND OUTPUT**

     ![Sample input and output](https://user-images.githubusercontent.com/59568640/132096358-bc541f91-448d-4d68-b39c-21c1baabfc68.PNG)

        
       
        
        
     
     
