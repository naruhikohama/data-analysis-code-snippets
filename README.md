# Helpful code snippets here for data analysis
I work with data analysis daily. I seek for help on stackoverflow daily, sometimes chatGPT as well. 

Sometimes I can't find the answer in just one source, so to help myself in the future and others that come by this repo, I will compile many useful codes here.

I will create (and try to keep it organized) many code snippets and show what they can do.

I used to work with R, so I kinda got used to the way you code with dplyr and the pipe operator. I will bring some code snippets in python for those in similar situation.

## Select and filter
[Data filtering in Pandas](https://towardsdatascience.com/filtering-data-frames-in-pandas-b570b1f834b9)

## Groupby
Groupby operations in R are very easy to do. The combination of group_by and summari(z|s)e in R makes it very simple to do very complex groupby operations. You can also use the combination of gorup_by and mutate to broadcast grouped calculations to every row, like, for example, the total of that category, or the max etc. 

In pandas it is not as easy or intuitive. You can do easy aggregations with pandas, like count, max, sum, number of unique (nunique), but when you get to some complex operations, things start to get difficult. But I found a wway to work very much like  I was programming in tidyverse, but on top of pandas (and I plan to do the same when I start working on polars too).

For now, I'll leave this link on apply vs transform that I found on stack overflow. You will use transform when you need to perform an operation to broadcast to all rows, whitout changing its orginal format.
[Apply vs transform on a group object](https://stackoverflow.com/questions/27517425/apply-vs-transform-on-a-group-object)
