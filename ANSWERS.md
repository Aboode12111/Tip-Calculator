# Answers

### 1. How to run
just Unzip the file that i upload then you just need to open the `index.html` file in your browser. I did not use packages, so you don't need to type any install commands. 

### 2. Stack & design choices
**Stack:** I used Vanilla HTML, CSS, and JavaScript its embedded on index.html file. I choose this because the app is very small and simple idea. 
**Design Choices:**
* First, I made the calculator work when you type. You don't have to click a "Calculate" button. This is faster for the user.
* Second, I made the "Per Person" number very big and blue (`font-size: 2rem`). I did this because when you split a bill with friends, you mostly want to know how much money you have to pay yourself.

### 3. Responsive & accessibility
On a small phone (360px), the white box takes all the screen space so the inputs are big to tap. On a big laptop (1440px), I used `max-width: 400px` so the box stays in the center and does not get too wide and ugly.



### 4. AI usage
* **Prompt:** I asked it: "How can I show a red error message under my input field if the number is bad, without using window.alert?"
* **What it gave me:** It gave me the `bad(input, span, msg)` and `good(input, span)` helper functions. It showed me how to add a `bad` CSS class to make the box red and how to put the error text in the `span`.


### 5. Honest gap
I would make it look more like a real restaurant app. Right now, it is just a plain white box. I would add a "Dark Mode" switch because people usually open tip calculators in dark restaurants at night, and a bright white screen hurts the eyes.