![image](https://user-images.githubusercontent.com/97670140/225808612-b7f19d7f-17ed-4571-b744-c5285212fd66.png)

- The Main Logic is to check the median of individual arrays, Then <br>
- if (aMid < bMid) keep [aRight + bLeft]
- else Keep [bRight + aLeft]**
___

![image](https://user-images.githubusercontent.com/97670140/226080517-ebf70e10-7d77-45c3-9fe4-8b72e39db804.png)

- **Break the list to half and half, check the value and sort <br>
- Divide and conquer**
___

![image](https://user-images.githubusercontent.com/97670140/227411199-5a172d89-891a-49da-9d2d-307bf03d9e22.png)

- **When we are updating the buy, we need to reset the sell(we cant sale before buying) <br>
- Edge case - [2,4,1]** 

___

![image](https://user-images.githubusercontent.com/97670140/227421820-0a5c76c1-3185-442b-94dc-4a08607109a7.png)

- **1st - Use Stack and check with the linked list  TC- O(n), SC - O(n) <br>
- 2nd - Find middle of the linked list, now reverse the half of the linked list and traverse from staring and end by matching the element  TC- O(n), SC - O(n)**

___

![image](https://user-images.githubusercontent.com/97670140/227690597-de314f14-0b8e-49c7-bef5-79b527bb6be9.png)

- **We will be creating a Linked List and finding the loop in it, the presense of loop will determine the repeatation of the number <br>
- Creating a two pointer FAST AND SLOW , the intersection determine the presense of loop <br>
- Start the point from starting and another to the intersection , and the point they will meet is the origin of loop or the duplicate number**

____

![image](https://user-images.githubusercontent.com/97670140/227700897-681aa173-de01-496a-a118-02b8d8027643.png)

- **Main logic is multiply the left hand side to the right hand side**
 ![image](https://user-images.githubusercontent.com/97670140/227700998-9bff11b9-8f38-43ba-8c59-b226afa8c6ca.png)
 
 ___

![image](https://user-images.githubusercontent.com/97670140/227756274-0dc52475-40ff-4c18-a7ab-e1ae23021e0a.png)

- **The main logic from the Ist part is   - If we will pick the 1st house then we will pick starting from 3rd OR if we are not picking 1st then we will pick 2nd and starting picking from 4th
- **So the equation becomes Math.max(nums[i] + dp[i-2], dp[i-1]);
<br>
-  **2nd part is we will make two array as the adjacent houses are in circular pattern, so 1st array will not include the last one and 2nd array will not pick the 1st one, We will return the maximum among the following.**
___

![image](https://user-images.githubusercontent.com/97670140/227936515-9cea58d6-618a-402b-8872-24efc83364b7.png)

- Recursive brute force way
- Make tabulation with considering the minimum value

___
