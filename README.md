Download Link: https://assignmentchef.com/product/solved-cs1102-programming-1-project-assignment-unit-5
<br>
The goal of this simple payroll system project is twofold: a) serve as a case-study and b) give students the opportunity to connect the dots and implement a full-fledged (albeit simple) application using most of Object-Oriented Programming. Understanding this project, by implementing, testing and debugging it, should provide students with the necessary OOP foundation (classes, information hiding, inheritance and polymorphism) so widely used in real-world applications nowadays. The project, spanning across a few chapters, is developed on a step-by-step basis, starting in unit 5, moving on to inheritance and polymorphism and finally putting it all together in unit 8. All you have to do is to follow the step-by-step instructions, creating your own application and submitting your project via Moodle. At the end of unit 8, you should have a program for a Simple Payroll System in Java that:

·         Keeps a list of employees: Id, Name, Vehicle in the parking lot (if applicable)·         Enter and save the payroll information: Salary, Bonus, Hourly rate, worked hours·         Store employee information to an ArrayList.·         Calculate the payroll

Unit 5 – The first step is to create the necessary classes to the project: Employee, PartTime, FullTime and Vehicle. The main application, which makes use of those classes, is also created here (PayrollSystem). Creating classes and start working with inheritance.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/325.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/325.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Step 1: Creating Project

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/132.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/132.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>After this step you will have a package name “payrollsystem” in which you will have “PayrollSystem.java” class having <em><strong>the</strong></em> main method.

Step 2: Creating new classes

To create a new class, simply right click on “payrollsystem” package name and select new -&gt; java class.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/658.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/658.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>You will need four classes for this project.

Employee class

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/767.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/767.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>FullTime class

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/440.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/440.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>PartTime class

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/114.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/114.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Vehicle class

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/676.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/676.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Step 3: Creating getters and setters.

For example: While working on Employee class, you have three instance variables.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/584.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/584.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Right click anywhere in the editor and choose Refactor option and then Encapsulate fields. See image below for details.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/931.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/931.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>You will get this window.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/483.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/483.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Select the fields whose getters and setters methods you want to be created. For the Employee class you need getters and setters for all the fields (therefore they should all be checked off). Click on Refactor button.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/902.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/902.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Netbeans will, automatically, create getter and setter methods for the chosen fields. Example getEmpId and setEmpId.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/365.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/365.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Step 4: Start working with inheritance

FullTime and PartTime classes are subclasses or child classes of the Employee class also called parent class.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/963.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/963.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/724.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/05/724.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>