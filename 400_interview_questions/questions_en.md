# 400 C++ interview questions

Last several years I have often been working on projects where I need to write a lot of C and C++ code. Also one of my activities is to take part in the interview process of the C and C++ developers as a technical interviewer. During the preparation for the interview I was faced with a list of 400 interview questions for C++ developers from Ukrainian site [**dou.ua**](https://dou.ua). You can read them [there](https://dou.ua/lenta/articles/interview-questions-c-developer/).

A lot of them are simple and I never use them in my real interview but this is the most complete list of the C++ technical questions I have ever seen. For this reason I have decided to translate them into English. 

[Junior level](#junior-level)  
[Middle level](#middle-level)  
[Senior level](#senior-level)  

## Junior level

### Common questions
1. Tell me about major OOP principles.
2. What is the complexity of the algorithm?
3. Your code works wrong. What will you do?
4. What are the queue and stack as the data structure?
5. Which did the programming books you read? What did you learn?
6. What do you think are interesting in C++17, C++20 standards?
7. What is ASCII table?
8. What is Unicode?
9. Tell me, please, what are the design patterns and why do they need?
10. Tell me, please, about Singleton, Strategy, Template-Method, Decorator patterns.
11. What do you think why do we use the unit tests?
12. What are the difference between unit and integration testing?
13. What is Test Driven Development (TDD)?

### Metaprogramming
14. What is a class template? What is a function templates?
15. What are the constructors? Which types of the constructors do you know?
16. Can a constructor be a function templates?
17. Can a virtual function be templated?
18. What is a template instantiation?
19. What is template specialization? What is a partial template specialization?
20. Tell me, please, how do you implement the template classes in a .cpp files?

### Preprocessor and compilation
21. Tell me, please, how does the process of compiling .cpp files into a binary file work?
22. What is the preprocessor?
23. How does the preprocessor work?
24. Which commands of the preprocessor do you know?
25. How does the `include` directive work?
26. How does the `define` directive work?
27. What does the linker link?
28. What is the compiler optimisation?
29. What is the compiler flag?
30. How can we prevent the header file from being included twice?
31. What does the `include` directive do?
32. How do the macros works?

### C 
33. How does `static` affect global/local variables?
34. How does `const` affect a variable?
35. What use cases for `extern` do you know?
36. What use cases for `volatile` do you know?
37. What bitwise operations are there?
38. What is Boolean algebra?
39. Describe the stages of developing a library or a program.
40. What are sorting algorithms, and which ones do you know?
41. What string algorithms do you know?
42. What graph algorithms do you know?
43. Where can a variable be stored?
44. What is the difference between `calloc` and `malloc`?
45. What is `realloc` used for?
46. What is a pointer?
47. What is the size of a pointer, and what does it depend on?
48. What operations can be performed on pointers?
49. What is a `struct`?
50. How do you determine the size of a structure?
51. What is alignment in structures?
52. What is a `union`?
53. What is the size of a `union`?

### C++/OOP

54. What is a class?
55. What are the basic data types in C++?
56. What is encapsulation? How is it implemented in C++?
57. What built-in types are there in C++?
58. What is an `enum`?
59. What is the relationship between a class and an object?
60. What is the difference between a `struct` and a `class`?
61. What is the difference between `private`, `protected`, and `public`, and where are they used?
62. What methods are provided by default for a class?
63. What is an abstract class, and what is it used for?
64. How much memory does an object of an empty class `class A {};` occupy?
65. What happens to a function when the `static` keyword is added to it? What does `static` mean for a class member or a class method?
66. What are the characteristics of static class members?
67. What are the characteristics of `const` member functions?
68. How can you modify a class member inside a `const` member function?
69. What methods can be called on `const` objects?
70. What are the heap and the stack? What are their differences, and how do they work?
71. What is the difference between a pointer and a reference?
72. What is a function pointer used for? How do you declare one?
73. What happens if you forget to call `delete`? When will that memory be released?
74. What is a smart pointer? What smart pointers are available in the C++ standard library?
75. How does `std::unique_ptr` work?
76. How does `std::shared_ptr` work?
77. Explain `const` with variables, references, and pointers. What is a constant pointer, and what is a pointer to a constant? What is the size of a pointer in memory?
78. Explain passing arguments by value, by reference, and by pointer.
79. What is the order of evaluation of function arguments?
80. What happens if you return a reference to a temporary object?
81. What is function overloading? What types of overloading are there?
82. What are explicit and implicit type conversions in C++? What explicit type conversion operators are available in C++?
83. What is variable initialization in an `if` statement?
84. What is lazy evaluation in C++?
85. Explain `for` loops and range-based `for` loops.
86. What does the `auto` keyword do? How does `auto` work with return types and function parameters?
87. What is the difference between `delete` and `delete[]`? What happens if you call `delete` on an object created with `new[]`?
88. How is error handling implemented in C++? What constructs are used for exception handling?
89. Can a constructor throw an exception? Which members will be constructed, and which ones will be destroyed?
90. What is a memory leak?
91. Can a destructor throw an exception?
92. How can you handle division by zero in C++?
93. How do `const` member functions work?
94. What is a lambda function in C++? How can it access variables from the enclosing scope?
95. What are `namespace` and anonymous namespaces used for?
96. How do you access an object from a nested namespace?
97. How do `inline` functions work? Can an `inline` function be recursive?
98. What is polymorphism?
99. What is inheritance used for?
100. What types of inheritance are there?
101. What is virtual inheritance used for?
102. How can the diamond inheritance problem be solved without using virtual inheritance?
103. What happens if an object of a derived class is passed by value to a function that accepts a base class?
104. What happens if you inherit from a base class that does not have a virtual destructor?
105. What happens if you call an overridden virtual function from a constructor? Can a constructor be virtual?
106. Can a pure virtual function have an implementation? What happens if a pure virtual function is called from a constructor?
107. What methods are generated for a class by default? When are these methods not generated? How can you explicitly tell the compiler to generate or delete them?
108. How can you prevent a class from being inherited from?
109. What is the order of construction and destruction of classes in an inheritance hierarchy? What is the order of initialization of class members?
110. What are the different ways to initialize class members?
111. Can a destructor be virtual?
112. What does the `virtual` keyword do?
113. What is a virtual destructor used for?
114. What is deep copying?
115. What are virtual functions, and why are they needed?
116. How can you prevent an object from being copied?
117. What is move semantics?

### STL/Algorithms

118. What does the STL consist of?
119. What STL algorithms have you used? What are the advantages of using STL algorithms over writing your own functions?
120. Explain the standard library containers `vector`, `list`, `map`, and `unordered_map`.
121. What types of iterators do you know? How do they differ? Which containers use them?
122. What is the difference between `std::set`, `std::map`, and `std::unordered_multimap`?
123. What is the `erase-remove` idiom?
124. How can you get the minimum value of a type?
125. What is the difference between `std::map` and `std::hashmap`?
126. How can you count the number of elements in a `std::list`?
127. What is algorithmic complexity, and what does it depend on?
128. What is the difference between `vector` and `list`, and when should you use each one?

### Multithreading

129. What do you know about multithreading?
130. What are the similarities and differences between processes and threads?
131. How can you synchronize data exchange between threads?
132. What is the difference between a mutex and a semaphore?
133. What is a deadlock?
134. Is C++ thread-safe?
135. What is a race condition?
136. How can you avoid race conditions?
137. What is an atomic operation?
138. How do you work with `std::mutex`?

### Networking

139. What is a socket?
140. What operations can be performed on a socket?
141. What information is required to create a socket?
142. What network models are there?
143. Explain the layers of the OSI model.
144. Explain the layers of the TCP/IP model.
145. What is an IP address?
146. What is a subnet mask used for?
147. What is the difference between IPv4 and IPv6?
148. How much memory is required to store an IPv4 address?
149. What is a port used for?
150. What is the maximum number of ports?
151. What is the difference between TCP and UDP?
152. Why is an unreliable protocol like UDP useful?

### OS/Linux

153. What is a package manager?
154. What package managers do you know?
155. What Linux distributions do you know?
156. What is a PID?
157. What are file descriptors used for?
158. Explain the standard file descriptors of a process.
159. What is a pipe?
160. What is a named pipe?
161. What is a UID?
162. What Bash commands do you know?

#### SCM/CI/CD

163. What types of SCM systems are there?
164. What are version control systems used for?
165. What Git commands do you know?
166. What are the stages of committing changes?
167. What is the difference between `git fetch` and `git pull`?
168. What are the steps for resolving a merge conflict?

### Practical Tasks

169. Count the number of set bits (`1`s) in an arbitrary number.
170. Given a singly linked list, write a function to reverse it so that the first element becomes the last and the last becomes the first.
171. Implement the function `int atoi(const char *str)` to convert a string to an integer.
172. Write a function to insert an element into a singly linked list.
173. Implement a `vector` class.
174. Implement binary search on an array.
175. Implement any sorting algorithm.
176. Implement a macro to compare two strings.
177. Implement string reversal.
178. Implement conversion of a string to an `int`.
179. Implement a function to count the number of words in a sentence.
180. Implement a function to calculate Fibonacci numbers.
181. Find the elements of two arrays that occur only in one of the arrays. Preferably use the STL.
182. Remove elements whose values are divisible by 2 from an `unordered_map` and print their keys.
183. Write a logging class that can log to either the console or a file.
184. Write a function to determine whether a given year is a leap year.
185. Write a function to determine whether a given word is a palindrome.
186. Implement the Singleton pattern.
187. Implement your own version of `std::vector` with the following operations: `push_back`, `push_front`, `pop_back`, `pop_front`, `size`, and `clear`.
188. Implement a recursive search for a value in a binary search tree.
189. Write a function to check whether a tree is balanced.
190. Write a function to find the unique element in an array.

## Middle level

### General

1. What courses have you taken or books have you read this year? What have you learned?
2. What do you like and dislike about C++? What do you think is missing from the language?
3. What interesting features have you found in the newer C++17 and C++20 standards? Give specific examples.
4. What features were introduced in different versions of C++?
5. Explain the memory model introduced in the C++11 standard.
6. What is serialization? What serialization libraries do you know?
7. What design patterns do you know?
8. What is an operating system? What types of operating systems are there based on their purpose?
9. What are the main components and operating principles of Linux as an example of a general-purpose operating system?
10. What are SFINAE and PIMPL?
11. Name creational, structural, and behavioral design patterns and give examples of their use.

### Preprocessor and Compilation

12. What build automation systems do you know?
13. What is the difference between static and dynamic libraries?
14. What is the difference between an executable file and a dynamic library?
15. What is DLL hell?
16. What are compiler flags, such as `-fPIC`?
17. What is the difference between debug and release builds?
18. What is required to use a third-party library?
19. What is internal linkage?

### C

20. What happens if you call `free` twice on the same memory?
21. How does a function call work?
22. How are parameters passed to a function?
23. How is variable constness handled?
24. What does the `inline` keyword mean?
25. What is memory alignment used for, and can it be controlled?
26. Explain bit-fields.
27. What is `extern "C"` used for?
28. What happens if two files define a function with the same name and parameters? At what stage will an error occur?
29. How do you export/import functions from a dynamic library?
30. What is the difference between C-style casts and C++ casts?

### C++

31. What are explicit and implicit type conversions in C++? Why should a constructor be marked `explicit`?
32. What are uniform initialization and aggregate initialization?
33. What is a reference to a temporary object? How can you extend the lifetime of a temporary object?
34. What is a delegating constructor?
35. What is an initializer list?
36. What is the order of initialization of class members? What happens if a constructor lists members in a different order?
37. What happens if one class member is initialized using another member?
38. What is copy elision? How many times are the constructor and destructor called for an object returned by value?
39. What is move semantics?
40. In what cases will a copy constructor not be generated?
41. What is the difference between a copy constructor and a copy assignment operator?
42. Under what conditions can a constructor throw an exception?
43. What is a default constructor? What are `default` and `delete` used for?
44. What is the difference between an interface and an abstract class?
45. What types of polymorphism are there in C++?
46. How is inheritance implemented by most compilers?
47. What are the pros and cons of multiple inheritance?
48. What is virtual inheritance, and what is the construction order when it is used?
49. Why should you use `override`?
50. What are the type deduction rules when using `auto`? In what cases can `auto` lead to an unwanted copy of an object?
51. What are all the possible uses of the `static` keyword in C++? What is the `static initialization order fiasco`?
52. What does `throw;` do inside a `catch` block?
53. What is the difference between `constexpr` and `const`?
54. What is `const` correctness?
55. When can `const_cast` be used?
56. What is the `mutable` keyword, and when should it be used?
57. What is the `friend` keyword, and when should it be used?
58. Explain lambda expressions in C++, including access to variables in the enclosing scope, capturing `this`, and the lifetime of lambdas and captured variables.
59. What is a functor? Write an example.
60. What is template specialization?
61. What are `dynamic_cast` and run-time type identification (RTTI)?
62. What is an exception? How do you throw and catch one?
63. What happens if an exception is thrown from a constructor? What about from a destructor?
64. What happens if an exception is not caught?
65. What happens if an exception escapes a `noexcept` function?
66. What can private inheritance be used for?
67. What is a function contract?
68. What are `vptr` and `vtable`?
69. Where is the `vptr` stored?
70. Where is the `vtable` stored?
71. What is the difference between `overload` and `override`?
72. How does the compiler distinguish class members from local variables inside member functions?
73. Why are exceptions used?
74. What are `try`, `throw`, and `catch` blocks?
75. Explain how `catch` blocks work.
76. What is a move constructor?
77. What is the difference between a `const` member function and a non-`const` member function?
78. What is Big O notation, and how do you determine the complexity of an algorithm?
79. What is a virtual method table?
80. What class member functions does the compiler automatically generate if they are not explicitly defined?
81. What is data alignment?
82. What is an exception?
83. What standard containers are available in C++, and what data structures are they based on?
84. What is undefined behavior? Give some examples.
85. How can you detect a memory leak in a program?
86. What is `std::make_shared` used for? What are its advantages over creating a `std::shared_ptr` directly with its constructor?
87. What happens if you allocate a certain amount of memory but write beyond the allocated size?
88. What is a stack overflow?

### Design Patterns

89. Why are design patterns needed? What types of design patterns are there?
90. What are the disadvantages of the Singleton pattern? When is it appropriate to use it?
91. What are the advantages and disadvantages of PIMPL?
92. What is the difference between the Factory pattern and the Factory Method pattern? When should each one be used?
93. What is the Observer pattern?
94. How can you manage the state of a program? What are a state machine and the State pattern?
95. What is the Visitor pattern?

### Metaprogramming

96. What are the type deduction rules for templates?
97. What is the difference between `using` and `typedef`?
98. How much memory does an arbitrary structure occupy? What is object alignment?
99. Why does an empty structure occupy 1 byte? What is the smallest addressable unit in C++?

### OOP/OOD

100. What is SOLID? What does each of its principles mean?
101. Explain design patterns.
102. What is Dependency Injection? Give an example.
103. What are the advantages and disadvantages of the functional programming approach?
104. What is the RAII principle?
105. What is the DRY principle?
106. What is the KISS principle?
107. What are the advantages of composition over inheritance?

### STL/Algorithms

108. What STL algorithms have you used? Which algorithms do you think are missing?
109. What requirements must a class meet to be an iterator?
110. What types of iterators are there?
111. Explain iterator invalidation.
112. How can you optimize removing an element from the middle of a `vector`?
113. How is `std::vector` implemented?
114. How is `std::list` implemented?
115. How can STL containers be extended?
116. What algorithms are available in the STL?
117. What is the difference between `vector`, `deque`, `list`, and `set` in the STL?
118. When should you use `map` and when should you use `unordered_map`? What is the complexity of lookup and insertion in these containers?
119. How can you check whether a container has any elements? Why can calling `container.size()` for this purpose be considered bad practice?
120. What is an exception safety guarantee? What exception safety guarantees do STL containers provide?
121. Explain the types of smart pointers and how reference counting works in them.

### Multithreading

122. Is C++ thread-safe?
123. What is the difference between multithreading and asynchronous programming?
124. What is multithreading? What functionality does C++ provide for developing multithreaded applications? What are the main problems associated with multithreaded applications?
125. How can information be exchanged between multiple processes?
126. How can multiple processes be synchronized?
127. What are the important considerations when working with shared memory?
128. How does a spinlock work?
129. What are the important considerations when using a recursive mutex?
130. Explain a read-write mutex.
131. What is a race condition? What is a deadlock? What is a critical section?
132. How can you avoid race conditions?
133. What is the difference between a mutex and a semaphore?
134. What synchronization primitives are available in C++? What are the advantages of `std::lock_guard`?
135. What happens if an exception escapes a thread? What tools does C++ provide for safe asynchronous programming?
136. What is the difference between `std::launch::async` and `std::launch::deferred`?
137. What is an atomic operation? What is `std::atomic`?
138. How do you work with `std::condition_variable`?
139. How do you create a thread using `std::thread`?
140. How many threads should a task ideally be divided into? What does it depend on?
141. How do you work with `std::async`?
142. What thread-safety guarantees do C++ standard library containers provide? Why is the `front()` + `pop_front()` interface problematic in multithreaded code?

### Networking

143. What is a TCP handshake?
144. What is the difference between TCP and UDP?
145. Explain application-layer protocols.
146. What is the difference between HTTP and HTTPS?
147. Explain the SSL/TLS handshake.

### SCM/CI/CD

148. Explain the CI process.
149. How can you edit a commit?
150. Explain interactive rebase.
151. What methods can be used to debug code?
152. What are unit tests used for? How do they differ from functional tests?
153. How do you test code? What testing framework do you use?
154. What libraries do you know for writing tests?
155. What is a mock?
156. How many tests should be written for a single function?
157. What are side effects, idempotency, and pure functions?
158. What is containerization, and what are its advantages and disadvantages? What is Docker or another containerization tool?
159. What is CI/CD, and what benefits does it provide to developers?
160. What are the principles of iterative development methodologies?
161. What are the advantages and disadvantages of coding conventions?

### Practical Tasks

162. Write a robust implementation of a `string` class with a copy constructor and copy assignment operator.
163. Implement a queue.
164. Implement a function that finds the unique element in a container in a single pass.
165. Implement a thread-safe thread pool.
166. Implement Conway’s Game of Life in an object-oriented style.
167. Write a class that retrieves a list of products from a database using a filter and prints them to the console. Write tests for it.
168. Implement any coding task that demonstrates your ability to design interfaces and follow the SOLID, DRY, and KISS principles.
169. Implement your own version of `std::atomic`.
170. Write a program for graph analysis that can detect cycles, deadlock states, and unreachable states.
171. Write a cross-platform program that ensures only one instance of the application is running in the system.
172. Analyze C++ code from a code-quality perspective: identify potential memory leaks, inefficient use of STL containers and algorithms, suboptimal constructs, and other issues.
173. Write code to solve Sudoku.
174. Write code to detect a cycle in a singly linked list.

## Senior level  

### General

1. How do you understand the SOLID principles?
2. How would you design a plugin system in C++?
3. What is RPC? What RPC libraries do you know?
4. What should you pay attention to when conducting a code review?
5. What problems can arise when writing cross-platform code? What should you pay attention to?
6. What should you do if the code is running slowly?
7. What methods and methodologies can be used to measure code performance? How can you eliminate or reduce the impact of measurements on performance?
8. What is SFINAE? What is it used for?
9. What is metaprogramming? How is it implemented in C++?
10. How do you use variadic templates?
11. How can you test private methods?
12. How do you measure test coverage? Is it necessary to do so?
13. What is a cache miss, and how can you detect it?
14. What are SIMD instructions? What are the requirements and ways to use them?
15. What is code coverage, and how can it be achieved?
16. Explain the principles of lock-free data structures and your experience working with them.

### Preprocessor and Compilation

17. Explain how to design and set up a build system.
18. How do you work with build systems such as Make and CMake?
19. How do you integrate third-party libraries into a project?
20. What are memory barriers?
21. Explain working with raw pointers and manual memory management.
22. What is a static code analyzer? Which static analysis tools do you know?
23. What is a dynamic code analyzer? Which dynamic analysis tools do you know?
24. A project takes a long time to build. How can you speed up the build process?

### C/C++

25. Explain the use of `realloc` in containers.
26. How do templates work?
27. Explain template specialization.
28. How does RTTI work?
29. Can exceptions be used in constructors and destructors?
30. What are `rvalue` and `lvalue`?
31. What are the characteristics of `std::set`, `std::map`, `std::unordered_map`, and `std::hash`?
32. What is `placement new`? What is it used for? How do you perform a `placement delete`?
33. How is a class with multiple inheritance and virtual functions laid out in memory?
34. How do breakpoints work?
35. What are vulnerabilities? How do they work?
36. How would you implement your own `std::shared_ptr`?
37. What is the Curiously Recurring Template Pattern (CRTP)?
38. Explain the purpose and behavior of `std::shared_ptr`, `std::unique_ptr`, and `std::weak_ptr`.
39. What are the purposes of `std::variant` and `std::any`, and how do they differ?
40. What improvements did `std::search` receive in C++17?
41. What is copy elision, and when is it possible? How does its behavior differ between C++ standards?
42. What is Return Value Optimization (RVO)?

### OOP/OOD

43. Explain the SOLID principles.
44. Explain the KISS principle.
45. Explain the YAGNI principle.
46. What approaches can be used to optimize code?
47. What should you pay attention to during a code review?
48. What design patterns do you know? Why is the Singleton pattern often discouraged?
49. What is static polymorphism?

### STL/Algorithms

50. When can `std::vector` use `std::move`?
51. Explain your favorite search algorithm.
52. What are lock-free and wait-free algorithms? What are their differences, and how can they be implemented?
53. What is the purpose of execution policies for parallel algorithms?

### Multithreading

54. Explain how to design APIs intended for multithreaded use.
55. What is the difference between kernel-level and user-level threads?
56. What is a coroutine?
57. What does the `thread_local` specifier do?
58. How can synchronization be implemented for the producer-consumer problem?
59. How can synchronization be implemented between different processes?

### SCM/CI/CD

60. Explain how to set up a repository branch management process.
61. Explain branching strategies.

### Practical Tasks

62. Write a basic implementation of `std::shared_ptr`.
63. Implement a sorting algorithm.
64. Implement a hashing algorithm.
65. Implement `shared_ptr` with support for `weak_ptr`.
66. Implement a simple producer-consumer using condition variables.
67. Describe in as much detail as possible what happens in the system when an application makes a network request.
68. Describe in detail the design of a software component, for example, a voting system, taking into account high load, extensibility, and fault tolerance.
