# Stock Analysis Project Using VBA 

## Project Overview: 
The purpose of this project is to refactor the code already used in the original script so that the code can be used on a larger dataset to analyze the stock market over the last few years. By refactoring, the aim is to run the code successfully and faster than the original code.
![image](https://user-images.githubusercontent.com/81877387/147510081-cf2d6e64-243f-41e7-8ed9-50a91df86e58.png)

## Results: 
By refactoring the code, the data shows that in 2017 the stock market outperfomed better than 2018. This is displayed clearly by using the conditional code formating of the return column in green (positive return) and red (negative return). In 2017 only one stock (TERP) under performed and had a negative return. By keeping this code from the original green stocks macro and moving it within the refactor code, this makes the data easy to read with clear daily volume values and percentages. 

## 2017 Stock Analysis Results 
<img width="1440" alt="All Stocks 2017" src="https://user-images.githubusercontent.com/81877387/117559106-9ba3af00-b050-11eb-83af-bcf6ce0ac959.png">

## 2018 Stock Analysis Results 
<img width="1440" alt="All Stocks 2018" src="https://user-images.githubusercontent.com/81877387/117559108-9d6d7280-b050-11eb-8fca-fa8f7866c00a.png">

## Code for formating data with color conditions, percentages & values 
Formating Code![image](https://user-images.githubusercontent.com/81877387/117559194-516efd80-b051-11eb-99c3-74078eed5590.png)

Overall with refactoring the original code, the time performance is only slightly longer (0.67 seconds for the refactoring code compared to 0.63 seconds). 

## Timeframe of orignal script in 2018 compared to refactored code in 2018 
<img width="1440" alt="Green Stocks 2018 " src="https://user-images.githubusercontent.com/81877387/117559408-01913600-b053-11eb-8896-4986e0e60882.png">

Although the refactored code is slightly longer than the original, running the new refactored code is still completed within 6 seconds with a cleaner code compared to the original. 

## Summary:
The advantages of refactoring code is the ability to understand the code and shorten codes to make it run more efficiently. For example, it is a normal process to review somebody elses code and without the process of refactoring code, it is hard to understand why a code was built the way it was and also understand where improvements could be made within the code. 

The disadvantages of refactoring code is that it is very time consuming and may not always have the same results as the structure of the code has changed. This may cause confusion for the recipient and the coder if by refactoring a code, the results is not what was initially concluded. 

By refactoring the original code, I was able to understand areas where the code could be shorten, removed or moved within the same lines without creating new sub routines. This made the refactored code much more easier to read and understand by being combined into one, as it was not subroutined into different sections. This also helped me pin point areas where my code was not running correctly in the original script and what could be shortened or removed to produce the same outcome. 

However my refactored code did not meet the aim of the project, which was the refactor the code to run faster. Although it was only slightly longer, it may not be reflective of meeting Steve's goal. 
