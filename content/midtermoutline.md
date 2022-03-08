---
title: Midterm Outline
date: 2022-03-06T03:14:59.000-06:00

---
 1. **Know the principles of Object Oriented programming (inheritance, encapsulation etc.)**

    [3354_oo_process.pdf](https://heuristic-brahmagupta-965a2c.netlify.app/uploads/3354_oo_process.pdf)

    [3354_s20_june3-2020.pdf](https://heuristic-brahmagupta-965a2c.netlify.app/uploads/3354_s20_june3-2020.pdf)
	
	Use All to Achieve OO:
	- Inheritance: Is an ability to inherit. Function implementations (behaviors) by a subclass from a super class. Main benefit is software reuse.
	"No silver bullet".
	Drawback: class hierarchy.
	- Polymorphism: Is an ability to provide multiple implementations for a single function declaration. Simplifies code. Complicates testing. Superclass shape example: We need to have an array of shapes. We can use a general "shape".
	- Encapsulation: Is hiding an object's state. Ex: Not wanting to change attributes. Increases reliability--a reliable system doesn't have many bugs on paths of frequent executions.
 2. **Be able to give an overview of the Extreme Programming process from the survey of agile processes**

    _3.1.1. Process (Figure 2. Life cycle ...)_

    [agilecomp.pdf](https://heuristic-brahmagupta-965a2c.netlify.app/uploads/agilecomp.pdf)
 3. **Know the principles of Model-Driven development and its advantages**
 
	Model driven paradigm:
	- The system is defined as an executable specification which is an object-oriented analysis model.
	- The system is validated at the analysis model level.
	- A software and execution architecture is defined as a set of class templates in an object-oriented programming system.
	- The executable system is realized by compilation of the validated analysis model to the software execution architecture.
	
	Advantages/Why:
	[introclassesattr.pdf](https://heuristic-brahmagupta-965a2c.netlify.app/uploads/introclassesattr.pdf)
 4. **Know the Model-View-Controller (MVC) architectural style - its constraints and benefits**
	![]https://heuristic-brahmagupta-965a2c.netlify.app/uploads/mvc-diagram.jpg
	Constraints and benefits:
	[model-view-controller.PDF](https://heuristic-brahmagupta-965a2c.netlify.app/uploads/model-view-controller.PDF)
 5. **Know how to implement event-based notification in Java**
 
	General Idea/Code snippets from:
	[model-view-controller.PDF](https://heuristic-brahmagupta-965a2c.netlify.app/uploads/model-view-controller.PDF)
 6. **Know the syntax of the class diagram language (class representations, various kinds of associations)**
 
 7. **Know the syntax of the statechart diagram language**
 
 8. **Be able to create a class diagram and a statechart from requirements**
	
	Class diagram: Library Example
	
	Statechart: LExceptionAndLightBulbClass.pdf
 9. **Know what is tested in different stages of testing (unit, integration, system, acceptance, regression)**
 
	**V**alidation: techniques for assessing the quality of a software product.
	**V**erification: the use of analytic inference to (formally) prove that a product is consistent with a specification of its intent
	
	Types of Testing—what is tested
	- Unit: exercise a single simple component
		- Procedure
		- Class
	- Integration: exercise a collection of interdependent components
		- Focus on interfaces between components
	- System: exercise a complete, stand-alone system
	- Acceptance: customer's evaluation of a system
		- Usually a form of system testing
	- Regression: exercise a changed system
	
	[VandV.PDF](https://heuristic-brahmagupta-965a2c.netlify.app/uploads/VandV.PDF)
10. **Be able to create testcases with a JUnit framework**

	http://junit.sourceforge.net/doc/testinfected/testing.htm
	(no coding)
11. **Be able to create testcases according to boundary, statement and edge coverage criteria**

	Given Java code. Provide X amount of paths.
	
---

03/08/22 Review Session

1. Inheritance, encapsulation, polymorphism. June 3 pdf. Definition, benefits and downsides.

2. Draw Figure 2 diagram or textually describe the different phases. (Pair programming mentioned in class, senior-junior example)

3. Model Driven development ... manage the scale of large systems. Theoretically spent all your time designing so coding/product can be automated/easier. Less testing because more validation. "The system is validated at the analysis model level".

4. Model-View-Controller (recreate MVC diagram jpg) "MVC Architecture from SUN" Benefits: 
	- Prof's favorite: Ability to create multiple views w/o shutting down the model.
	- Reusability of application and/or user interface compoents
	- Ability to develop the application

5. Basic idea for implementation/methodology. Probably not code based testing. Modern software can talk with other software.

6 - 8. Create your own diagrams. More flexibile than library example (blank boxes are short-term/long-term goal)...
Statechart ExceptionAndLightBulbClass.pdf ...

9.

10.

