In securities research, an analyst Will look at a number of attributes for a stock .one analyst would like to keep a record of the ghest positive spread between a closing price and the closing price on any prior day in story. determine the maximum positive spread for a stock given its price story.if the stock remains flat or declines for the full period, return-1. Example 0

px = [7, 1, 2, 5] 

Calculate the positive difference between each price and its predecessors:

• At the first quote, there is no earlier quote to compare to.

• At the second quote, there was no earlier price that was lower.

• At the third quote, the price is higher than the second quote:

• 2-1=1

• For the fourth quote, the price is higher than the third and the second quotes:

5-2=3


05-1=4.

• The maximum difference is 4
.Example 1

px = [7, 5, 3, 1] 

• The price declines each quote, so there is never a difference greater than 0. In this case, return -1.

Function Description


Complete the function maxDifference in the editor below.


maxDifference has the following parameters:

▼

int px[n]: an array of stock prices (quotes)

Returns:

int: the maximum difference between two prices as described above

Constraints

• 1≤ n ≤105

• -105 ≤ px[i] ≤ 105

▼Input Format For Custom Testing

Locked stub code reads input from stdin and passes it to the function.

The first line contains an integer, n, denoting the number of elements in the array px.

Each of the next n lines contains an integSample Case 0


Sample Input For Custom Testing

STDIN Function

7 → px[] size n = 7

2→ px = [2, 3, 10, 2,
4,8,1]


10

2

4

8

1



Sample Output

8



Explanation

Calculate the positive difference between each price quote and the previous ones: duli
At the second quote, the price is higher than the first quote:

• px[1] - px[0] = 3 - 2 = 1

• At the third quote, the price is higher than the first and second quotes:

• px[2] - px[1] = 10 - 3 = 7

• px[2] - px[0] = 10 - 2 = 8

• At the fifth quote the price is higher than the first and second quotes:

• px[4] - px[1] = 4 - 3 = 1 

• px[4] - px[0] = 4 - 2 = 2

• At the sixth quote, the price is higher Ghana than the first, second, fourth and fifth quotes:

px[5] - px[0] = 8 - 2 = 6

• px[5] - px[1] = 8 - 3 = 5

• px[5] - px[3] = 8 - 2 = 6

○ px[5] - px[4] = 8 - 4 = 4

The maximum difference is 8
