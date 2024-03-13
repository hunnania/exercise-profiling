<details>
    <summary>Module 5</summary>

<h2>Comparison</h2>

* JMeter tests <br>
  * all-student (before) <br>
  ![img.png](img.png) <br>
  * all-student (after) <br>
  ![img_1.png](img_1.png) <br>
  * all-student-name (before) <br>
  ![img_5.png](img_5.png) <br>
  * all-student-name (after) <br>
  ![img_2.png](img_2.png) <br>
  * highest-gpa (before) <br>
  ![img_4.png](img_4.png) <br>
  * highest-gpa (after) <br>
  ![img_3.png](img_3.png) <br>
  
* JMeter Command Line Test
  * all-student
  ![img_6.png](img_6.png)
  * all-student-name
  ![img_7.png](img_7.png)
  * highest-gpa
  ![img_8.png](img_8.png)
  
* Profiling
  * all-student (before)
  ![img_14.png](img_14.png)
  * all-student (after)
  ![img_12.png](img_12.png)
  * all-student-name (before)
  ![img_10.png](img_10.png)
  * all-student-name (after)
  ![img_11.png](img_11.png)
  * highest-gpa (before)
  ![img_9.png](img_9.png)
  * highest-gpa (after)
  ![img_13.png](img_13.png)
  
<h2>Reflection</h2>
1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler 
  in the context of optimizing application performance? <br>
   > IntelliJ profiling provides detailed insights into how your application behaves at runtime, helping you pinpoint 
  specific areas of improvement in your code while performance testing with JMeter will measure and analyze how your 
  application performs under various loads which helps you understand the overall performance characteristics of your 
  application under different conditions. <br>
2. How does the profiling process help you in identifying and understanding the weak points in your application? <br>
    > Providing detailed information about the execution flow and resource consumption of your application, Highlighting 
areas of the code that consume the most CPU time, memory, or other resources, Identifying potential memory leaks or 
inefficient algorithms, and others. <br>
3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application 
code? <br>
    > Yes, I can know which part of my code that I can optimize. <br>
4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome 
these challenges? <br>
    > One of the challenges is testing the scalability of the system to handle a large number of users or transactions.
To overcome it, I use load testing tools like JMeter to simulate a large number of users and transactions. <br>
5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code? <br>
    > Detailed insights, real time monitoring, integration with other IntelliJ tools, and many more. <br>
6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with 
findings from performance testing using JMeter? <br>
    > Review the data collected by IntelliJ Profiler to understand the specific performance metrics, such as CPU usage, 
memory allocation, and thread activity. Look for any anomalies or unexpected behavior that could explain the 
reasons of the inconsistency. <br>
7. What strategies do you implement in optimizing application code after analyzing results from performance testing and 
profiling? How do you ensure the changes you make do not affect the application's functionality? <br>
    > I try to focus on optimizing parts of my code that consumes the most resources. uSE Git to track changes to your
code and easily revert back to a previous state if needed to ensure the changes I make does not affect the application's 
functionality. <br>
</details>