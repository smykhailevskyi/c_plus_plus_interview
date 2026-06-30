<h3>A collection of C and C++ questions I found on the internet</h3>

<strong>Vtable - C++ Interview Questions</strong>
<p>1. Does every instance of a class have its own <code>vtable</code>, or do they share it?</p>
<p>2. Can we call a <code>virtual function</code> from a constructor or a destructor? What happens if we do?</p>
<p>3. What happens to the <code>vtable</code> if a class has no <code>virtual functions</code>, or if the base class has <code>virtual functions</code> but the derived class does not override them?</p>
<p>4. Is the <code>vptr</code> initialized at compiletime or runtime?</p>
<p>5. How does the <code>vtable mechanism</code> affect the memory footprint of an object?</p>
<p>6. Have you ever had to debug an issue related to <code>object memory layout</code> or <code>vtable pointer corruption</code>?</p>

<h3>Questions</h3>  

1. How does <code>object layout</code> change with multiple inheritance when both base classes have <code>virtual functions</code>?
2. What is a secondary <code>vptr</code>, and why can one object contain more than one <code>vptr</code>?
3. What happens to <code>this pointer adjustment</code> when calling a <code>virtual function</code> through a <code>non-primary base pointer</code>?
4. How does <code>virtual inheritance</code> affect object layout compared to <code>regular multiple inheritance</code>?
5. Where is the <code>virtual base offset</code> stored, and how does the runtime find the shared <code>virtual base subobject</code>?
6. Can a template class have <code>virtual functions</code>?
7. Why can't a <code>virtual function</code> itself be a template?
8. How would you implement <code>conditional polymorphism</code> with templates?
9.  How does CRTP avoid <code>vtables</code>, and when is it preferable to runtime polymorphism?
10. What is devirtualization, and under what conditions can the compiler replace a <code>virtual call</code> with a <code>direct call</code>?
11. Why can calling <code>virtual functions</code> in constructors/destructors be dangerous even when it is legal?

