# Popularity-Analysis-of-Instagram-filters-using-Hadoop-and-Map-Reduce
Popularity Analysis of Instagram filters using Hadoop and Map Reduce

The instagram dataset contained information of random 5 million photos on Instagram. The content includes:

1. userId – The ID of user
2. photoId – The ID of the photo
3. createdTime – Time of the photo posted by user
4. filter – Filter type used in the photo
5. likes – Number of likes
6. comments – Number of comments

The goal of this project is to understand what kind of filter is popular and what is not. 

Specifically, the project implemented the following two steps:
1. Developed a MapReduce program to count each type of filters.
2. Designed another pair of mapper and reducer, which takes the output from Step 1 as the
input, and ranks the filters by their frequencies in a decreasing order.

The final output format is the default of Hadoop, which is key value pair separated by tab. 
For example,
filterAAAA 9999 
filterBBB 5555 
filterCC 111
