### GUI Test plan result for /all-student-name
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/e2dfe7ef-1490-4662-9dc6-15261d521878)
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/674de8c3-4789-4905-be0f-f901a4d32fbe)
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/880f9007-38ed-4694-9df6-fd4f2e08d27b)
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/34e249e4-9492-4872-ae2e-9ed951b3fee0)

### GUI Test plan result for /highest-gpa
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/c0f8dfc9-192b-4541-af5b-d2606dfd708f)
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/08fa12a2-f0e0-40be-8add-8ca85c661bb3)
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/11eb6d17-2fea-4555-a0e4-8c59aa04bb23)
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/9935e652-63c6-42db-bfbc-f03f184f2181)

### Command-line test plan result for /all-student-name
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/7bfbf9ed-7b13-495f-b05a-f0073bfd43e7)
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/e93d0083-936e-46f3-b595-da7e32635df8)

### Command-line test plan result for /highest-gpa
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/a43c9a6c-777e-4b3f-ada4-3b1ad8dc471b)
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/a07a0264-2148-4ad3-b8b9-0817878d6065)

### Before and after optimization
#### /all-student
* before
![all-student](https://github.com/alfian-f/exercise-profiling/assets/32451722/cefbe404-3900-4291-a41e-2ee80572cba5)
* after
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/d3d58f19-3a2c-4666-86bf-8724a255e2df)

#### /all-student-name
* before
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/e93d0083-936e-46f3-b595-da7e32635df8)
* after
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/64336e1a-de93-4812-adcd-397befd0e069)

#### /highest-gpa
* before
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/a07a0264-2148-4ad3-b8b9-0817878d6065)
* after
![image](https://github.com/alfian-f/exercise-profiling/assets/32451722/2c4c18a6-e4a1-41a7-9760-ad056c1ca684)

### Optimization Conclusion
After optimizing the code, the programs ran with less latency then before, making the optimized one faster.

### Reflection | Module 5
1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?

JMeter checks how well the whole system works and handles many users, focusing on overall performance. Meanwhile, IntelliJ Profiler digs deep into the code to find and fix specific issues, helping to make the application run better.

2. How does the profiling process help you in identifying and understanding the weak points in your application?

Profiling shows how the application works and how it uses resources. This detailed view helps me figure out which parts need improvement.

3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

Yes, its helpful in figuring out what's slowing down the application. It gives useful information about how the program runs, showing which parts of the code might be causing problems.

4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

The main challenges I faced during performance testing and profiling in Intellij profiling is when I was given the result of the profiling, I had trouble reading the results. I overcome these challenges by asking a friend about it.

5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

It helps in finding the specific part of the code where the application's bottleneck is located.

7. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

Check if the testing environments are similar, review and adjust the test scenarios.

8. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

By utilizing Spring Data JPA, and streams method. I also make sure that when I change things in the application, I test it afterward to make sure it still works the way it's supposed to.



