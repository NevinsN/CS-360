# CS-360
Mobile Architect &amp; Programming

* Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

  This app needed to funciton off of 2 databases, one for user creation and login and the other for inventoiry storage. It was designed to allow people to manually track inventory, potentially in a warehouse or business setting. It needed to have functionality to prompt for and send SMS texts to notiffy of low inventory, add and remove items, as well as increase and decrease inventory quantity. 
  
* What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

    This project needed a login screen, a notifications permission prompt screen, an inventory management screen, and an add item screen. The entire UI was designed with ease of use and clarity in mind. I added an way to increment or modify by an entered int in order to make inventory updating more efficient.  
  
* How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

    I approached app deveeopment and coding from an object oriented approach. I designed and coded everything to be as modular and efficient as I could. Devloping from start to finish was a great way to practice SDLC, and there's a lot of the planning that will transfer well to future projects. As for coding practices, I came up with some effective ways to tackle challenging issues, and those are designed to be reusable. Mostly, I learned a lot about developing apps for android, and I think I'll find great use for that going forward.
  
* How did you test to ensure your code was functional? Why is this process important and what did it reveal?

    I mostly utilized unit testing as I developed. I prefer to test each piece as I build it, then implement it into the main project and test again. At the end, I ran multiple tests to check against the requirements. This level of testing is vital. Because I tested often, I was able to have a streamlined final testing process as I found bugs as they occured. This led to many frustrating moments where I broke my app unintentionally, but it meant I was able to approach fixing it knowing where the issues lied, because I would test whenever I made impactful changes.
  
* Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

    One specific example was when I was trying to get the gridview to select a row on click. There might be an easier way to do it, but I found that if I get the position of the clicked element, then subtracted that from itself modulo 3, I'd always end up with the first item element in the row, which was the id column. With that, I could then easily call up an item in the database in order to operate on it. There were a lot of other little innovations I have to work on, but this is the one that stands out most.

* In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

    I think I did particularly well with manipulating and building logic and classes to keep the app functional and as streamlined as possible. I know I could probably clean it up more, as I admittedly rushed due to time constraints. However, I think I show a solid foundation with a good handle on industry standards.
