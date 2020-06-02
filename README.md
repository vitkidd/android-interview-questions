### Android Design Problem

* **Design Uber App.** - [Learn from here](https://github.com/MindorksOpenSource/ridesharing-uber-lyft-app)

* **Design Facebook App.**

* **Design Facebook Near-By Friends App.**

* **Design WhatsApp.**

* **Design SnapChat.**

* **Design problems based on location based app.**

* **How to build offline-first app? Explain the architecture.**

* **Design LRU Cache.**

* **Design File Downloader** - [Lear from here](https://github.com/MindorksOpenSource/PRDownloader)

* **HTTP Request vs HTTP Long-Polling vs WebSockets** - [Lear from here](https://www.youtube.com/watch?v=k56H0DHqu5Y)

### Java and Kotlin

* **What are Coroutines in Kotlin?** - [Learn from here](https://blog.mindorks.com/mastering-kotlin-coroutines-in-android-step-by-step-guide)

* **What is Coroutine Scope?** - [Learn from here](https://blog.mindorks.com/mastering-kotlin-coroutines-in-android-step-by-step-guide)

* **What is Coroutine Context?** - [Learn from here](https://blog.mindorks.com/mastering-kotlin-coroutines-in-android-step-by-step-guide)

* **Launch vs Async in Kotlin Coroutines** - [Learn from here](https://www.youtube.com/watch?v=nC30UiDv8Xc)

* **What is inline function in Kotlin?** - [Learn from here](https://blog.mindorks.com/understanding-inline-noinline-and-crossinline-in-kotlin)

* **When to use Kotlin sealed classes?** - [Learn from here](https://blog.mindorks.com/learn-kotlin-sealed-classes)

* **Explain function literals with receiver in Kotlin?** - [Learn from here](https://blog.mindorks.com/function-literals-with-receiver-in-kotlin)

* **Tell about Kotlin DSL.** - [Learn from here](https://blog.mindorks.com/mastering-kotlin-dsl-in-android-step-by-step-guide)

* **What are higher-order functions in Kotlin?** - [Learn from here](https://blog.mindorks.com/understanding-higher-order-functions-and-lambdas-in-kotlin)

* **What are Lambdas in Kotlin** - [Learn from here](https://blog.mindorks.com/understanding-higher-order-functions-and-lambdas-in-kotlin)

* **Tell about the Collections in Kotlin** - [Learn from here](https://www.youtube.com/watch?v=XeRt2ZZ-jkA)

### Data Structures And Algorithms

> The level of questions asked on the topic of Data Structures And Algorithms totally depends on the company for which you are applying.

#### Whiteboard Interview Series - Data Structures and Algorithms on Youtube - [Check here](https://www.youtube.com/playlist?list=PLqOiaH9id5qt_lZl2bFi8q9RQoV1JJUpf)

#### Tech Interview Preparation Kit - [Check here](https://afteracademy.com/tech-interview)

#### Android Developer should know these Data Structures for Next Interview - [Check here](https://blog.mindorks.com/android-developer-should-know-these-data-structures-for-next-interview)

* **Complexity Analysis** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/complexity-analysis)
    - What is Input, Output, Correctness, Efficiency of Algorithms?
    - What is Input Size and Running Time of Algorithms?
    - Explain the Worst, Best, and Average case analysis of Algorithms.
    - What is Big-O Notation with respect to Time and Space Complexity?

*  **Iteration and Two Pointer Approach** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/iteration-and-two-pointer-approach)
    - Explain Initialization, Maintenance, and Termination used in iteration.
    - Explain the use-case of Two Pointer approach

* **Recursion and Divide & Conquer Approach** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/recursion-and-divide-and-conquer-approach)
    - Explain Recursion with the help of an example and also draw the recursion call stack for the same.
    - How will you analyse the recursive solution of some problem?
    - Is there any difference between Recursion and Iteration?
    - Explain the Divide and Conquer technique with the help of a real-world example.

* **Arrays and Linked List** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/array-and-linked-list)
    - What do you mean by Linear Data Structures?
    - Explain the basic operations that can be performed on Arrays? Also, tell about Amortized analysis of array.
    - What is a Linked List? Explain with an example by performing some operations on Linked List.
    - What are the types of Linked List?
    - Can you tell the difference between an Array and a Linked List?

* **Stack and Queue** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/stack-and-queue)
    - What is a Stack? Explain various operations that can be performed on a Stack.
    - Can you implement Stack using an Array or using a Linked List? How?
    - What is a Queue? Explain various operations that can be performed on a Queue.
    - Can you implement Queue using an Array or using a Linked List? How?
    - Is there any difference between a Stack and a Queue?

* **Sorting Algorithms** - [Wikipedia](https://en.wikipedia.org/wiki/Sorting_algorithm?oldformat=true)
    - Using the most efficient sorting algorithm (and correct data structures that implement it) is vital for any program, because data manipulation can be one of the most significant bottlenecks in case of performance and the main purpose of spending time, determining the best algorithm for the job, is to drastically improve said performance. The efficiency of an algorithm is measured in its' "Big O" ([StackOverflow](https://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation)) score. Really good algorithms perform important actions in O(n log n) or even O(log n) time and some of them can even perform certain actions in O(1) time (HashTable insertion, for example). But there is always a trade-off - if some algorithm is really good at adding a new element to a data structure, it is, most certainly, much worse at data access than some other algorithm. If you are proficient with math, you may notice that "Big O" notation has many similarities with "limits", and you would be right - it measures best, worst and average performances of an algorithm in question, by looking at its' function limit. It should be noted that, when we are speaking about O(1) - constant time - we are not saying that this algorithm performs an action in one operation, rather that it can perform this action with the same number of operations (roughly), regrardless of the amount of elements it has to take into account. Thankfully, a lot of "Big O" scores have been already calculated, so you don't have to guess, which algorithm or data structure will perform better in your project. ["Big O" cheat sheet](http://bigocheatsheet.com/)
    - Bubble sort [Wikipedia](https://en.wikipedia.org/wiki/Bubble_sort?oldformat=true) 
        - Bubble sort is one of the simplest sorting algorithms. It just compares neighbouring elements and if the one that precedes the other is smaller - it changes their places. So over one iteration over the data list, it is guaranteed that **at least** one element will be in its' correct place (the biggest/smallest one - depending on the direction of sorting). This is not a very efficient algorithm, as highly unordered arrays will require a lot of reordering (upto O(n^2)), but one of the advantages of this algorithm is its' space complexity - only two elements are compared at once and there is no need to allocate more memory, than those two will occupy. 
            <table>
                <tr>
                    <th colspan="3" align="center">Time Complexity</th>
                    <th align="center">Space Complexity</th>
                </tr>
                <tr>
                    <th align="center">Best</th>
                    <th align="center">Average</th>
                    <th align="center">Worst</th>
                    <th align="center">Worst</th>
                </tr>
                <tr>
                    <td align="center">Ω(n)</td>
                    <td align="center">Θ(n^2)</td>
                    <td align="center">O(n^2)</td>
                    <td align="center">O(1)</td>
                </tr>
            </table>
    - Selection sort [Wikipedia](https://www.wikiwand.com/en/Selection_sort) 
        - Firstly, selection sort assumes that the first element of the array to be sorted is the smallest, but to confirm this, it iterates over all other elements to check, and if it finds one, it gets defined as the smallest one. When the data ends, the element, that is currently found to be the smallest, is put in the beginning of the array. This sorting algorithm is quite straightforward, but still not that efficient on larger data sets, because to assign just one element to its' place, it needs to go over all data.
            <table>
                <tr>
                    <th colspan="3" align="center">Time Complexity</th>
                    <th align="center">Space Complexity</th>
                </tr>
                <tr>
                    <th align="center">Best</th>
                    <th align="center">Average</th>
                    <th align="center">Worst</th>
                    <th align="center">Worst</th>
                </tr>
                <tr>
                    <td align="center">Ω(n^2)</td>
                    <td align="center">Θ(n^2)</td>
                    <td align="center">O(n^2)</td>
                    <td align="center">O(1)</td>
                </tr>
            </table>
    - Insertion sort [Wikipedia](https://en.wikipedia.org/wiki/Insertion_sort?oldformat=true)
        - Insertion sort is another example of an algorithm, that is not that difficult to implement, but is also not that efficient. To do its' job, it "grows" sorted portion of data, by "inserting" new encountered elements into already (innerly) sorted part of the array, which consists of previously encountered elements. This means that in best case (data is already sorted) it can confirm that its' job is done in Ω(n) operations, while, if all encountered elements are not in their required order as many as O(n^2) operations may be needed.
            <table>
            <tr>
                <th colspan="3" align="center">Time Complexity</th>
                <th align="center">Space Complexity</th>
            </tr>
            <tr>
                <th align="center">Best</th>
                <th align="center">Average</th>
                <th align="center">Worst</th>
                <th align="center">Worst</th>
            </tr>
            <tr>
                <td align="center">Ω(n)</td>
                <td align="center">Θ(n^2)</td>
                <td align="center">O(n^2)</td>
                <td align="center">O(1)</td>
            </tr>
            </table>
    - Merge sort [Wikipedia](https://en.wikipedia.org/wiki/Merge_sort?oldformat=true)
        - This is a "divide and conquer" algorithm, meaning it recursively "divides" given array in to smaller parts (up to 1 element) and then sorts those parts, combining them with each other. This approach allows merge sort to achieve very high speed, while  doubling required space, of course, but today memory space is more available than it was a couple of years ago, so this trade-off is considered acceptable.   
            <table>
            <tr>
                <th colspan="3" align="center">Time Complexity</th>
                <th align="center">Space Complexity</th>
            </tr>
            <tr>
                <th align="center">Best</th>
                <th align="center">Average</th>
                <th align="center">Worst</th>
                <th align="center">Worst</th>
            </tr>
            <tr>
                <td align="center">Ω(n log(n))</td>
                <td align="center">Θ(n log(n))</td>
                <td align="center">O(n log(n))</td>
                <td align="center">O(n)</td>
            </tr>
            </table>
    - Quicksort [Wikipedia](https://en.wikipedia.org/wiki/Quicksort?oldformat=true)
        - Quicksort is considered, well, quite quick. When implemented correctly, it can be a significant number of times faster than its' main competitors. This algorithm is also of "divide and conquer" family and its' first step is to choose a "pivot" element (choosing it randomly, statistically, minimizes the chance to get the worst performance), then by comparing elements to this pivot, moving it closer and closer to its' final place. During this process, the elements that are bigger are moved to the right side of it and smaller elements to the left. After this is done, quicksort repeats this process for subarrays on each side of placed pivot (does first step recursively), until the array is sorted.
                <table>
                <tr>
                    <th colspan="3" align="center">Time Complexity</th>
                    <th align="center">Space Complexity</th>
                </tr>
                <tr>
                    <th align="center">Best</th>
                    <th align="center">Average</th>
                    <th align="center">Worst</th>
                    <th align="center">Worst</th>
                </tr>
                <tr>
                    <td align="center">Ω(n log(n))</td>
                    <td align="center">Θ(n log(n))</td>
                    <td align="center">O(n^2)</td>
                    <td align="center">O(n)</td>
                </tr>
                </table>  
    - There are, of course, more sorting algorithms and their modifications. We strongly recommend all readers to familiarize themselves with a couple more, because knowing algorithms is very important quality of a candidate, applying for a job and it shows understanding of what is happening "under the hood".

* **Binary Tree** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/binary-tree)
    - What are non-linear data structures? Give example.
    - What is a Tree Data Structure? Explain the properties of tree with an example.
    - How is Binary Tree different from a normal Tree?
    - What is inorder, pre-order, post-order, and level-order traversal of a tree? Explain with an example.
    - Can you find the inorder, pre-order, and post-order of a tree using Stack? How?
    - Explain how searching, insertion, and deletion operations are performed on a Tree?

* **Binary Search Tree** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/binary-search-tree)
    - What is a Binary Search Tree? Explain its properties also.
    - Explain how searching, insertion, and deletion operations are performed on a Binary Search Tree?
    - How is Binary Search Tree different from Binary Tree?

* **Heap and Priority Queue** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/heap-and-priority-queue)
    - What is a Heap data structure and when it is used?
    - Explain the operations that can be performed on a Heap.
    - What is the difference between a min-heap and a max-heap? How to implement these two?
    - What do you mean by Priority Queue? How to implement Priority Queue?
    - What are the real-life applications of Priority Queue?

* **Hash Table** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/hash-table)
    - What do you mean by Direct Address Table?
    - Can you perform search, insert, and delete in O(1)? How?
    - Explain Hash Table and its properties.
    - How to remove collision in Hash Table by Chaining and Open Addressing?
    - What are the real-life applications of Hash Table?

* **Dynamic Programming** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/dynamic-programming)
    - What is Dynamic Programming and how to find if a problem can be solved using DP or not?
    - What are two approaches of solving a Dynamic Programming problem?
    - Explain Optimization and Combinatorial problems?

* **Greedy Algorithms** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/greedy-algorithms)
    - What do you mean by Greedy algorithms? How to find if a problem can be solved by Greedy approach or not?
    - Is there any difference between Dynamic Programming and Greedy Algorithms?

* **Backtracking** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/backtracking)
    - What is Backtracking?
    - How to find if a problem can be solved with Backtracking or not?
    - What is Exhaustive Searching?

* **Graph** - [Learn from here](https://afteracademy.com/tech-interview/ds-algo-concepts/graph)
    - What is Graph and how to represent a Graph?
    - Explain Depth First Search and Breadth First Search.
    - How to represent a Graph? 
    - What are the real-life applications of Graph?
    - What do you mean by Topological Sorting?
    - Explain Dijkstra algorithm with an example.
    - What is a Minimum Spanning Tree?

### Other Topics

* **Describe how REST APIs work. What is REST?** - [Learn from here](https://www.youtube.com/watch?v=1wSEI6_SzMU) and [here](https://www.youtube.com/watch?v=HgXAoBomGcA)

* **Describe SQLite.** - [Learn from here](https://blog.mindorks.com/android-sqlite-database-in-kotlin) and [here](https://www.youtube.com/watch?v=9OHzXUo3Ymk)

* **Describe database.** - [Learn from here](https://afteracademy.com/blog/what-is-a-database-and-dbms)

* **How do you control the application version update to specific number of users?**

* **Can we identify users who have uninstalled our application?**

* **Android Development Best Practices.** - [Learn from here](https://blog.mindorks.com/android-development-best-practices-83c94b027fd3)

* **Android Code Style And Guidelines.** - [Learn from here](https://blog.mindorks.com/android-code-style-and-guidelines-d5f80453d5c7)

* **Have you tried Kotlin?** - [Learn from here](https://blog.mindorks.com/why-you-must-try-kotlin-for-android-development-e14d00c8084b)

* **What are the metrics that you should measure continuously while android application development?** - [Learn from here](https://blog.mindorks.com/android-app-performance-metrics-a1176334186e)

* **What is Chrome Custom Tabs? How to display web content in your app?** - [Learn from here](https://blog.mindorks.com/android-browser-lets-launch-chrome-custom-tabs-with-kotlin)

* **How to avoid API keys from check-in into VCS?** - [Learn from here](https://blog.mindorks.com/using-local-properties-file-to-avoid-api-keys-check-in-into-version-control-system)

* **How does the Kotlin Multiplatform work?** - [Learn from here](https://blog.mindorks.com/how-does-the-kotlin-multiplatform-work)

* **How to use Memory Heap Dumps data?** - [Learn from here](https://blog.mindorks.com/how-to-use-memory-heap-dumps-data)

* **How to implement Dark Theme in your app?** - [Learn from here](https://blog.mindorks.com/build-material-and-dark-themes-apps-using-style-in-android)

* **Have you tried Jetpack compose?** - [Learn from here](https://blog.mindorks.com/using-jetpack-compose-to-build-ui-in-android)

* **How to secure the API keys used in an app?** - [Learn from here](https://blog.mindorks.com/securing-api-keys-using-android-ndk)

* **How to convert check Java equivalent code of Kotlin?** - [Learn from here](https://blog.mindorks.com/how-to-convert-a-kotlin-source-file-to-a-java-source-file)

* **Tell something about memory usage in Android.** - [Learn from here](https://blog.mindorks.com/understanding-memory-usage-in-android)

* **What is Benchmarking?** - [Learn from here](https://blog.mindorks.com/improving-android-app-performance-with-benchmarking)

* **Can you create transparent activity in Android?** - [Learn from here](https://blog.mindorks.com/how-to-create-a-transparent-activity-in-android)

* **How to use Android Sensors?** - [Learn from here](https://blog.mindorks.com/using-android-sensors-android-tutorial)

* **Explain Annotation processing.**  - [Learn from here](https://blog.mindorks.com/android-annotation-processing-tutorial-part-1-a-practical-approach)

* **How to increase the Notification delivery rate?** [Learn from here](https://blog.mindorks.com/how-to-increase-push-notification-delivery-rate-in-android)

* **How does the notification system work?** [Learn from here](https://blog.mindorks.com/how-to-increase-push-notification-delivery-rate-in-android)

* **How to show local Notification at an exact time?** [Learn from here](https://blog.mindorks.com/how-to-increase-push-notification-delivery-rate-in-android)

### Found this project useful :heart:

* Support by clicking the :star: button on the upper right of this page. :v:

[Check out MindOrks awesome open source projects here](https://mindorks.com/open-source-projects)

### License
```
   Copyright (C) 2020 MINDORKS NEXTGEN PRIVATE LIMITED

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

### Contributing to Android Interview Questions
Just make pull request. You are in!
