# Class 09

Why are forms so important in web development?
- forms are a component of web development that facilitates user interaction, data collection, and the overall functionality of websites and web applications.

When designing a form, what are some key things to keep in mind when it comes to user experience?
- Keep the form layout clean and straightforward. Use a clear and concise design with well-organized fields.
- Organize form fields in a logical sequence, following the natural order of information input.
- Ensure that the form is responsive and works well on various devices, especially on mobile phones and tablets.
- Use clear and descriptive labels for each form field.

List 5 form elements and explain their importance.
- The <form> element formally defines a form and attributes that determine the form's behavior.
- The <fieldset> element is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes.
- The text content of the <legend> formally describes the purpose of the <fieldset> it is included inside.
- The <label> element is the formal way to define a label for an HTML form widget.

How would you describe events to a non-technical friend?
- JavaScript events are like special invitations or triggers that prompt certain actions to take place when specific things occur during the party.

When using the addEventListener() method, what 2 arguments will you need to provide?
- the string "click", "mouseover", "keydown"

Describe the event object. Why is the target within the event object useful?
- The event object provides valuable information about the event, and one of the key properties within it is target. The target property refers to the DOM element on which the event was originally triggered. 

What is the difference between event bubbling and event capturing?
- The browser first captures the event during the capturing phase. This phase involves traversing down the DOM hierarchy from the root element to the target element.
- After the capturing phase, the event enters the bubbling phase. In this phase, the event starts from the target element and moves up the DOM hierarchy towards the root.