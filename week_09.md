# week 8

## Learning Experiment

## Learning Activities

During this week I first decided to test two different learning techniques, I decided to test the Promodoro method compared to the traditional method where you study without breaks. Resource 1 gave me the necessary steps to understand how to conducted the experiment.

The Pomodoro Technique is a time management method where you break your work into intervals, traditionally 25 minutes long, called "Pomodoros," separated by short breaks of 5 minutes. After completing four Pomodoros, you take a longer break of 15-30 minutes.

It is designed to help maintain focus, reduce fatigue, and increase productivity. My theory is that applying the Pomodoro Technique to studying will result in better retention of the material compared to my usual continuous studying method.

While the traditional continuous study method, which is consistently setting aside a time to study over time, with no breaks during the study. This method is all about making learning a habit, so you can gradually improve your understanding and mastery over time rather than cramming or studying in short bursts.

Test Steps:

1. Choose a topic to learn that is completely new to you, preferably something that can be divided into two equal parts.
2. Divide the learning material into two sections (A and B).
3. Study section A using my traditional continuous study method. Record the total time spent studying this section.
4. Study section B using the Pomodoro Technique, with 25-minute study intervals and 5-minute breaks. After four intervals, take a 15-30 minute break. Record the total time spent studying this section.
5. After completing the study of both sections, wait 24 hours before assessing retention.
6. Design a quiz or test with an equal number of questions for each section.
7. Take the quiz, and then calculate the percentage of correct answers for each section.
Compare the results of the two sections to determine whether the Pomodoro Technique led to better retention.

I decided to use resource 2 as section A and resource 3 as section B for my experiment, my experiment centred around php programming as I'm relatively new to it.

## Resource/Links

1. <https://www.themuse.com/advice/take-it-from-someone-who-hates-productivity-hacksthe-pomodoro-technique-actually-works>
2. <https://phptherightway.com/#errors_and_exceptions>
3. <https://phptherightway.com/#templating>

## Estimated Hours

In total I spent around 4 hrs on this experiment

## Content Insights

Starting off I found the Pomodoro method more enjoyable than the Traditional Continuos Study (TCS) method. I found that I felt more focused and less distracted after taking short breaks compared to TCS where I found myself becoming tired after continuos study. After conducting both experiment I found that I scored higher using the Pomodoro methods compared to TCS, however it should be noted that I started with TCS then switched to Pomodoro. In future experiments I will see if changing the order in which the methods are tested has any noticeable affect of my score.

## Career/Employability/Learning Insights

The Pomodoro Technique significantly improved my focus and productivity, enabling me to cover more material and understand complex concepts more efficiently than with the traditional study method. This increased focus also resulted in better retention, as evidenced by my higher quiz scores when using the Pomodoro Technique.

Additionally, the technique helped me manage my time more effectively, reducing fatigue and stress during study sessions. This allowed me to stay engaged and maintain a more positive mindset while learning. This could make me a more attractive candidate to employers by demonstrating my ability to quickly acquire new skills and stay up-to-date with industry trends.

Furthermore, the technique's adaptability makes it a valuable tool for various learning situations and work-related tasks. Applying the Pomodoro Technique to professional development and on-the-job tasks can enhance my overall performance and contribute to career advancement.

Based of this experiment and my personal experience using both methods I'm more likely to adopt the Promodoro school of thought when in comes to studying, as I found it improved my focus, productivity and learning comprehension.

## Questions and answers

## Errors and Exceptions

1. What is the difference between an error and an exception in PHP?
2. What function is used to set a custom error handler in PHP?
3. How do you create a custom exception class in PHP?
4. What keyword is used to throw an exception in PHP?
5. What are the three keywords used for handling exceptions in PHP, and in which order should they be used?
6. Which PHP function is used to restore the previous error handler?
7. What are the two main types of exceptions in PHP?
8. How do you catch multiple types of exceptions in a single catch block?
9. How can you re-throw an exception after catching it?
10. What is the purpose of the finally block in exception handling?

## Templating

1. What is the purpose of using a templating engine in PHP?
2. Name a popular PHP templating engine.
3. How do you display a variable in a template using the Twig templating engine?
4. In the Blade templating engine, what is the syntax for including a sub-view (partial) within a template?
5. What is the purpose of using template inheritance, and how do you extend a base layout in the Blade templating engine?
6. How do you create a loop in a Twig template?
7. What is the syntax for escaping output in the Blade templating engine?
8. How do you create a conditional statement in a Twig template?
9. In the Blade templating engine, what is the syntax for defining a section?
10. How can you pass data to a template in the Twig templating engine?

## Errors and Exceptions

1. Errors are issues in the script that cannot be handled at runtime, while exceptions are events that occur during the execution of the script and can be handled 2. using exception handling techniques.
2. The set_error_handler() function is used to set a custom error handler in PHP.
3. To create a custom exception class in PHP, extend the built-in Exception class and define the required properties and methods.
4. The throw keyword is used to throw an exception in PHP.
5. The three keywords used for handling exceptions in PHP are try, catch, and finally, and they should be used in this order.
6. The restore_error_handler() function is used to restore the previous error handler in PHP.
7. The two main types of exceptions in PHP are Throwable and Exception.
8. To catch multiple types of exceptions in a single catch block, use the pipe symbol | to separate the exception types.
9. To re-throw an exception after catching it, use the throw keyword followed by the caught exception variable.
10. The finally block is used to execute code regardless of whether an exception has been thrown or not. It is executed after the try and catch blocks.

## Templating

1. The purpose of using a templating engine in PHP is to separate presentation logic from business logic, making it easier to maintain and create clean, readable code.
2. A popular PHP templating engine is Twig.
3. To display a variable in a Twig template, use double curly braces, like {{ variable_name }}.
4. In the Blade templating engine, the syntax for including a sub-view (partial) within a template is @include('subview_name').
5. Template inheritance allows you to create a base layout and extend it with child templates, promoting code reuse and a consistent design. In the Blade templating engine, you can extend a base layout using the @extends('layout_name') directive.
6. To create a loop in a Twig template, use the {% for %} and {% endfor %} tags.
7. The syntax for escaping output in the Blade templating engine is {{ variable_name | e }} or {{ variable_name | escape }}.
8. To create a conditional statement in a Twig template, use the {% if %}, {% elseif %}, and {% endif %} tags .
9. In the Blade templating engine, the syntax for defining a section is @section('section_name')...@endsection.
10. To pass data to a template in the Twig templating engine, use the render() method and provide an associative array of data .
