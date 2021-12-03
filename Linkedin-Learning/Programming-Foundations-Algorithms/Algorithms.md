### Algorithms purpose 
to solve a specific proplem with a sequential sets of steps 
for instance : if you need to add different shaped in groups you can use loop by iterate on each shape if its belong to this group or not 
#### Algorithms charachteristics
* algorithms complixity
    * space complixity
    * time complixity
* input and output
* classification
    * serial/parallel
    * exact/approximate
#### common algorithms
* searching algo find a specific data from a structure
* sorting algo take a set of data and apply a sort order to it
* computational algo given a ser of data calculate another (calculator) 
* collection algo work with collection of data : manipulating and navigating amoung sets of data that are sorted (count a specific items)
exerciese for an algorithm
```python 
def greatest common denomonator (a,b)
    while (b != 0)
        t=a
        a=b
        b=t%b
    return a 

print(20,8)
```
#### Algorithm performance
* how an algorithm will be have based on the size of input set data 
* big-O to describe algorithm performance as the size of input grows over time it usually describe the worst case senario
### Time complixity rank
* O(1) operation in question doesnt depend on the number of elements in the given data set (calculating the number is even or odd)
* O(log n) finding a specific value in a sorted array using a bionary search so if the number of elements grow it takes logarithmic time relation to find any given item 
* O(n) searching for an item in an unsorted array as number of items increase it take the corrosponding linear time to complete the search
* O(nlogn) sorting algorithm like stack and merge sort
* O(n2) as the number of data increase the time it take is squared
___
### Overview on Data structure
#### 1: Array  
**it has either one dimention or multiple , you can calculate**
<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/s600x600/251086554_925828158022548_4213311023797469815_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=u6zZKL4yAaAAX-OKLxY&_nc_oc=AQkNA6-ePRuy6EEP44wqVpitWKFgXthm6i_bGxEWmWmZ8ihzONL9IFIWzgI13BEFJt8&_nc_ht=scontent.fcai20-5.fna&oh=f1674ac952ae782d051e16ecc87ee827&oe=61A63717" width="450"/>
* item index O(1)
* insert or delete at beginning or middle O(n)
* insert or delete at end : O(1) 
#### 2: Linked lists(nodes)  
* linear collection of data elements each node has a field that refer to the next element in the list 
* the benifit of it over arrays is that its fast and easy to add and remove items from the list
* its not necessary to recognize the essintial memory that hold the data because the individual nodes doesnt have to be stored adjecently like arrays 
* the linked lists cant do canstant time random access to any item in the list like the array
<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/s600x600/251468074_925828188022545_1985724231888542230_n.jpg?_nc_cat=104&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=LD8oXbNXHU4AX8pg-ao&_nc_oc=AQmFTNOOouXvndB48LNNbxqkK5norpD7TF8oB02tsdJEZVhTp-vAngsKepDLy_1kED4&_nc_ht=scontent.fcai20-5.fna&oh=21455f1a46e9df832810954abf5eda89&oe=61A3CA33" width="450"/>
**you can inserting a new item in the list**
<img src="https://scontent-hbe1-1.xx.fbcdn.net/v/t1.6435-9/s600x600/251077802_925828241355873_7250618156303485425_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=ZnpwuHBhK74AX9hLYk-&_nc_ht=scontent-hbe1-1.xx&oh=b9fda58c5b21e8ba2fcfa86fbf8fe99e&oe=61A475FF " width="450"/>
#### 3: stack 
**is collection that support two priciples .**
* push  
* pop 
the last item pushed is the first one poped 
<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/s600x600/250834814_925832968022067_4632413539278251179_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=4tpS_2C7JG0AX9SYxN1&_nc_ht=scontent.fcai20-5.fna&oh=1ab9af6a31e48c37050f54da8888f166&oe=61A35506" width="450"/>
is used in 
* expression processing 
* back tracking
#### 4: Queue
**its collection that supports adding and removing and work like stack but**
the first item added is the first one removed
<img src="https://scontent-hbe1-1.xx.fbcdn.net/v/t1.6435-9/s600x600/251166132_925832904688740_4715572629182538361_n.jpg?_nc_cat=111&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=o2ehp8aYC08AX-7QRa_&_nc_ht=scontent-hbe1-1.xx&oh=9de1c95d2cf6804ce17272d8e794f413&oe=61A314C2" width="450"/>
is used in
* order processing 
* massaginh 
#### 5: hash tables 
**an ability to unique map a given key to a specific value (word during dictionary list)**
<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/s600x600/251680376_925832861355411_3917777530643487639_n.jpg?_nc_cat=104&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=YLfNIYexx9QAX9G9Q2E&_nc_ht=scontent.fcai20-5.fna&oh=65ba7839049199c4f55708a8759d52f1&oe=61A31323" width="450"/>
it 
* is very fast
* for small data sets array is more efficient
* hash table dont order entries in a predictable way 
___
### Recursion 
* your recursive function return at some point (breaking condition)
* otherwise it leeds to infinite loop
* each time the function called the value of arguments of the previous call are stored aside not written over by the new call (call stack)
### sorting data
####1: bubble sort
<img src="https://scontent-hbe1-1.xx.fbcdn.net/v/t1.6435-9/s600x600/251286865_925842791354418_2797908617305636563_n.jpg?_nc_cat=106&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=PKPaoN1ukakAX8wSZb1&_nc_ht=scontent-hbe1-1.xx&oh=14d37b6fe4a94ba3b8da9a01c5ed55e5&oe=61A2CCCA" width="450"/>  

its 
* very simple to understand and implement
* performance O(n2)
  * for loops inside of for loops are usually n2
* other sorting algorithms are generally much better
#### 2: merge sort
<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/s600x600/251289872_925843704687660_1095809695731907178_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=VdbKcPpF4AoAX8Yfjbn&_nc_ht=scontent.fcai20-5.fna&oh=02525e63ef5f3494941c933ea7d37462&oe=61A3BCC8" width="450"/>  

by 
* divide and conquer algorithm
* breaks a dataset into individual pieces and merges them
* uses recursion to operate on datasets
its
* performs well on large sets of data 
* generally has O(nlogn) performance
#### 3: Quicksort
<img src="https://scontent-hbe1-1.xx.fbcdn.net/v/t1.6435-9/s600x600/251473192_925843668020997_2579537905274875830_n.jpg?_nc_cat=108&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=ZYd6VbdBuUIAX-hDGgU&_nc_ht=scontent-hbe1-1.xx&oh=64ead2e2ded4b6a8ce4d6c789db51d21&oe=61A6672B" width="450"/>
<img src="https://scontent-hbe1-1.xx.fbcdn.net/v/t1.6435-9/s600x600/251605632_925843634687667_3546591156881561677_n.jpg?_nc_cat=105&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=_XGyX8g4MNAAX_Khuor&_nc_ht=scontent-hbe1-1.xx&oh=30461cfefd79f9c6622bd828af0ebcc8&oe=61A5ADB0" width="450"/>  

* divide and conquer algorithm 
* uses recursion to operate on datasets
* generally has O(nlogn) performance
* operate in place on the data
* worst case is O(n2) when data is mostly sorted already
### searching data
* unordered list search
* ordered list search
* determine if alist is sorted
### other algorithms
* filtering hash table
* counting value with hash table
* find max value recusively
