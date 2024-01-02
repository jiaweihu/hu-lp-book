# Case Study: Happy Pet Food Description

This case study is of an organization called Happy Pet Food which is seeking to maximize profit on the products that they produce and sell. 

Happy Pet Food produces two types of dog food, Meaties and Yummies. The ingredients in each of these products include cereal and meat. Each Meaty requires 20 pounds of cereal and 20 pounds of meat. Each Yummy requires 30 pounds of cereal and 10 pounds of meat. Happy Pet Food can procure only 400,000 pounds of cereal in a month and 200,000 pounds of meat in a month. In addition, Happy can only make a maximum of 8,000 batches of Meaties each month due to these sales constraints. The profit on each batch of Meaties is `$`65 and the profit they make on each batch of Yummies is `$`45. 

|          | Meaties X1 | Yummies X2  | Resource constrains | 
| --------:| ---------- | ----------- | ------------------- | 
| Cereal   | 20         | 30          | 400,000             |
| Meat     | 20         | 10          | 200,000             | 
| Sales    | 1          |             | 8,000               |
| Profits  | 65         | 45          |                     |

The **decision variables** are the number of batches of Meaties as x1, with one batch of Meaties use 20 pounds of cereal and 20 pounds of meat. The number of batches of Yummies is x2. This has 30 pounds of cereal and 10 pounds of meat. 

The objective of this exercise is to maximize our profit. The profits are $65 on Meaties and $45 on Yummies. The **objective function** is:

$$Z = 65x1 + 45x2$$

Let's turn our attention to the constraints, which can vbe expressed as:

$$20x1 + 30x2 \leqslant 400,000$$
$$20x1 + 10x2 \leqslant 200,000$$
$$x1 \leqslant 8,000$$
$$x1 \geqslant 0$$
$$x2 \geqslant 0$$


