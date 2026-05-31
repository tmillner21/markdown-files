# Edugator Student Guide

Welcome to **Edugator**! This guide will walk you through signing up, joining your course, navigating modules, completing coding problems, and using Edugator’s built-in AI assistant.

Follow along with the screenshots in each section.

---

## 1. Creating Your Account

Go to Edugator and click **Sign Up**.

📸 **Screenshot:** Edugator homepage, outline Sign Up button

Enter:

- Your name
- Email address
- Password

> **Tip:** You can sign up with a personal email, but it’s best to use your school email. That’s usually how your instructor will invite you to your course.

After signing up, accept any course invitations sent by your instructor.

📸 **Screenshot:** Course invitation screen, outline Accept invitation button

---

## 2. Opening Your Course

Once you’re logged in:

1. Go to **Current Courses**
2. Click your course

📸 **Screenshot:** Current Courses page

You’ll arrive at your **Course Home / Overview** page.

This page gives you a quick overview of:

- Modules
- Lessons
- Coding problems
- Your progress

📸 **Screenshot:** Course overview page

---

## 3. Navigating the Sidebar

On the left side of the course page is the sidebar.

📸 **Screenshot:** outline Sidebar 

### Courses

Takes you back to the **Current Courses** page.

### Home

Returns to the course overview page.

### Content

Shows all lessons and coding problems in a compact dropdown view.

📸 **Screenshot:** Content tab open with a module open

### Exams

Future exams may appear here.

Exams work similarly to regular course content, but may include:

- Timers
- Locked access windows

### Grades

Shows:

- Completed problems
- Course progress

📸 **Screenshot:** Grades page

---

## 4. How Course Content Is Organized

Edugator content is organized into **modules**.

Each module can contain:

- Lessons (reading + questions)
- Coding problems

---

## 5. Modules

Inside a module you will see different icons.

### 📖 Three-line icon = Lesson Content

This contains:

- Reading material
- Explanations
- Multiple-choice questions

### Right Arrow

Moves to the next module.

### Left Arrow

Returns to the previous module.

### Computer icon = Coding problem

Will be explained more below but this is where you get to code and practice.

📸 **Screenshot:** module 1.1 with arrows pointing to relevant icons and has label

---

## 6. Coding Problems

Click a **computer icon** to open a coding problem.

📸 **Screenshot:** Computer icon highlighted

The screen is divided into two sides.

### Left Side

Contains:

#### Problem Statement

Instructions for what you need to code, may include some examples.

#### Submission History

See:

- Previous submissions
- Passed/failed attempts
- Test runs

####  AI Assistant

Edugator’s AI assistant can help guide you if you get stuck while solving problems.

It will **not** give you the answer directly, but it can:

- Explain errors
- Point out mistakes
- Suggest what to check next

### Right Side

This is your coding editor.

Write your code here.

> **Important:** Keep your code inside the function provided for you.

📸 **Screenshot:** whole coding problem dashboard with relevant tabs outlined and labeled

---

## 7. Example: Hello World

Open **Displaying Output: Hello World**.

Read the problem statement.

Then write your code in the editor.

### C++

```cpp
std::cout << "Hello World" << std::endl;
```

Click **Test Code**.

Edugator will run your code and show console output.

📸 **Screenshot:** Test Code button + output panel

Then click **Submit Code**.

If something fails:

Read the test feedback. There is usually a hint that will guide you to fix your code.


Example:

> Hint -- Make sure you do not add extra white space or new lines at the end of the output as we compare exact outputs.

Fix the issue and submit again.

### C++

```cpp
std::cout << "Hello World";
```

📸 **Screenshot:** Failed test → passed test

> **Tip:** Edugator uses 	`dif` to check that your output is correct. Due to this, your output needs to be EXACTLY the same as the expected output (`dif` is case-sensitive and whitespace sensitive). 

---

## 8. Viewing Submission History

You can review:

- All submissions
- Test case results
- Passed/failed attempts

Under **Submission History** in the left panel.

📸 **Screenshot:** Submission history panel

---

## 9. Example: Reading Input

Open **Reading Input**.

This problem asks you to read values from the user and print the sum.

### C++ Example

```cpp
int firstInput;
int secondInput;

std::cin >> firstInput;
std::cin >> secondInput;

std::cout << firstInput + secondInput;
```

Click **Test Code**.

You can control the input using:

**Testing tab → STDIN**

Example input:

```text
4
3
```

Expected output:

```text
7
```

📸 **Screenshot:** STDIN + output panel

---

## 10. Debugging Errors

Sometimes your code won’t run.

That’s normal.

Example in C++:

Using `cin` incorrectly:

```cpp
std::cin << firstInput;
```

Testing may show an error.

Edugator will display:

- Error message
- Line number
- Compiler feedback

📸 **Screenshot:** Compiler error

Reading the error message is a great habit.

It often tells you exactly where to look.

---

## 11. Using the AI Assistant

If you get stuck:

Open **AI Assistant**. The AI assistant has access to your code editor but will not give you code. Using the AI assistant is great practice in learning how to ask the right questions.

📸 **Screenshot:** AI assistant first message

Describe your issue.

Example:

> “I’m trying to write a program that takes in two numbers from a user and outputs the sum of those numbers, but I’m getting an error.”

The AI Assistant can help identify:

- Syntax errors
- Input mistakes
- Logic bugs

Then you can return to your code and fix it.

📸 **Screenshot:** AI response example

### C++ Example Bug

Let's go back to the example above of using `cin` incorrectly:

```cpp
std::cin << firstInput;
```

Input:

```text
1
2
```

Output:

```text
some compiler error
```

Ask AI assistant:

> “my code is erroring out around line #, could you help me figure out why?”

Buddy explains that `cin` uses `>>` and not `<<`.

Then update:

```cpp
std::cin >> firstInput;
```

📸 **Screenshot:** AI assistant's answer and correction in code editor

---

## 12. Final Tips

✅ Use your school email 
✅ Read lesson content carefully  
✅ Test before submitting  
✅ Read error messages  
✅ Use AI Assistant when stuck  
✅ Check Grades to track progress

Edugator is designed to help you learn by practicing.

**Good luck in your course—and welcome to Edugator!**
