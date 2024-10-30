# Theoretical Sorting

A Computer Science researcher claims to have come up with a sorting algorithm
that can sort arbitrary elements in $O(n)$ time based on comparisons of two
elements at a time. This would be asymptotically faster than any known general
sorting algorithm. The algorithm itself is proprietary and will be sold by a
company.

How would you verify this claim? You may assume that you have access to a
black-box implementation of the sorting algorithm, i.e. you cannot examine the
source code, but you can use it to sort any list you like. Explain in detail
your method for investigating whether X is correct, including any expected
results you would get.

Also give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.

Add your answers to this markdown file.

The first thing that I would do to start verifying without the code, is to input different sized lists from small medium to large. To add other tests I could input the lists in different fasions such as already sorted or reverase sorted or other set ups like that. I would input a 10 size list a 100 size increasing up to around 1,000,000,000 size and maybe even larger depending on the results. By using sizes of ten it would be easy to anylyze if the claim is correct because the claim is linear, so if size 100 input is linearly larger from 10 input and so on we can use that as evidence that the claim is correct. And to measure this i just need to time each run for each input.

In theory i dont beleive this time complexity could be correct. I dont beleive it could be correct becuase we found that the lower bound time complexity of a comparison based algorithm would have to be Big Omega n log n because it takes linear time to go through the list and log n to compare. Because the theoretical is claiming to be linear it is not following the lower bound that we found in class for comparable sorting algorithms.
