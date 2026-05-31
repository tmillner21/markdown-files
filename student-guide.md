# Edugator Student Guide

Welcome to **Edugator**! This guide will walk you through signing up, joining your course, navigating modules, completing coding problems, and using Edugator’s built-in AI assistant.

Follow along with the screenshots in each section.

---

## 1. Creating Your Account

Go to Edugator and click **Sign Up**.

<img width="1050" height="855" alt="edugator homepage, sign up button outlined" src="https://github.com/user-attachments/assets/53154cca-de6f-4c19-b9da-af8d34e03d24" />


Enter:

- Your name
- Email address
- Password

> **Tip:** You can sign up with a personal email, but it’s best to use your school email. That’s usually how your instructor will invite you to your course.

After signing up, accept any course invitations sent by your instructor.

<img width="1094" height="899" alt="invitations tab and accept button outlined" src="https://github.com/user-attachments/assets/33bab2ba-dae1-4a06-949c-1034d9483ff0" />

---

## 2. Opening Your Course

Once you’re logged in:

1. Go to **Current Courses**
2. Click your course

<img width="1094" height="899" alt="current courses tab" src="https://github.com/user-attachments/assets/aeead6c2-2b36-4cca-b348-4acf42dca2ea" />


You’ll arrive at your **Course Home / Overview** page.

This page gives you a quick overview of:

- Modules
- Lessons
- Coding problems
- Your progress

<img width="1094" height="899" alt="course overview page" src="https://github.com/user-attachments/assets/02159679-bf90-480d-8072-7ff47798c86d" />


---

## 3. Navigating the Sidebar

On the left side of the course page is the sidebar.

<img width="1094" height="899" alt="course overview page with sidebar outlined" src="https://github.com/user-attachments/assets/dc7ea0a0-c5f1-4c92-9b0f-9abb5ff56ce7" />

### Courses

Takes you back to the **Current Courses** page.

### Home

Returns to the course overview page.

### Content

Shows all lessons and coding problems in a compact dropdown view.

<img width="1094" height="899" alt="content tab with a module open" src="https://github.com/user-attachments/assets/08ee1785-4ba7-411e-8459-25605268b407" />


### Exams

Future exams may appear here.

Exams work similarly to regular course content, but may include:

- Timers
- Locked access windows

### Grades

Shows:

- Completed problems
- Course progress

<img width="1094" height="899" alt="grades page" src="https://github.com/user-attachments/assets/4da0a91a-26fc-4c89-8669-c509e74bd9c9" />


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

<img width="1094" height="899" alt="different icons in gutter labeled with arrows" src="https://github.com/user-attachments/assets/56f9bccf-5046-450e-ba3b-0e9aa207745c" />

---

## 6. Coding Problems

Click a **computer icon** to open a coding problem.

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

<img width="1094" height="899" alt="entire dashboard that shows problem statement, submission history, AI assistant, and coding editor tabs" src="https://github.com/user-attachments/assets/1b6fb48d-5a68-487a-9022-0f70bc55263f" />


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

<img width="1094" height="899" alt="successful compilation of hello world" src="https://github.com/user-attachments/assets/0921d98c-57b6-420b-81e6-824f2f69b946" />

Then click **Submit Code**.

<img width="1094" height="899" alt="failed submission, 0% score" src="https://github.com/user-attachments/assets/fc957eb9-bd0c-4542-9236-198893287ebb" />

If something fails:

You can read each test case's feedback by hitting the corresponding **View** button. There is usually a hint that will guide you to fix your code.

Example:

<img width="1094" height="899" alt="submission results" src="https://github.com/user-attachments/assets/02c86b64-1c57-4e44-8911-b70e49ab6174" />

Fix the issue and submit again.

### C++

```cpp
std::cout << "Hello World";
```

<img width="1094" height="899" alt="hello world problem passing" src="https://github.com/user-attachments/assets/14fde711-a78d-425f-b46d-114dea418e96" />


> **Tip:** Edugator uses 	`dif` to check that your output is correct. Due to this, your output needs to be EXACTLY the same as the expected output (`dif` is case-sensitive and whitespace sensitive). 

---

## 8. Viewing Submission History

You can review:

- All submissions
- Test case results
- Passed/failed attempts

Under **Submission History** in the left panel.

<img width="1094" height="899" alt="submission history tab" src="https://github.com/user-attachments/assets/2b5ae155-d02e-470f-a4cb-5a76aa892231" />

Submissions have a percentage while runs will not.

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

<img width="1094" height="899" alt="whole problem after hitting test code with stdin tab of testing tab outlined" src="https://github.com/user-attachments/assets/44353586-6c73-4056-97f5-12e209954ffc" />

Example input:

```text
3
4
```

<img width="1094" height="899" alt="stdin tab with 3 and 4" src="https://github.com/user-attachments/assets/4de503f1-3691-4972-91e3-70bba3cfe16a" />

Expected output:

```text
7
```

<img width="1094" height="899" alt="output tab with the output 7" src="https://github.com/user-attachments/assets/d56dd7c8-399d-49b9-a5df-08b411935748" />

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

<img width="1094" height="899" alt="whole tab with error" src="https://github.com/user-attachments/assets/f4df6b12-520b-45f4-a465-821bb43178eb" />


Reading the error message is a great habit.

It often tells you exactly where to look.

---

## 11. Using the AI Assistant

If you get stuck:

Open **AI Assistant**. The AI assistant has access to your code editor but will not give you code. Using the AI assistant is great practice in learning how to ask the right questions.

<img width="1094" height="899" alt="whole coding problem with AI assistant tab selected, welcome message from AI assistant is visible" src="https://github.com/user-attachments/assets/6addd4ec-dd19-45e6-b97f-25b7937ee024" />


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
main.cpp: In function ‘int main()’:
main.cpp:10:12: error: no match for ‘operator<<’ (operand types are ‘std::istream’ {aka ‘std::basic_istream<char>’} and ‘int’)
   10 |   std::cin << firstInput;
      |   ~~~~~~~~ ^~ ~~~~~~~~~~
      |        |      |
      |        |      int
      |        std::istream {aka std::basic_istream<char>}
```

Describe your issue:

> “I’m trying to write a program that takes in two numbers from a user and outputs the sum of those numbers, but I’m getting an error around line 10”

The AI Assistant can help identify:

- Syntax errors
- Input mistakes
- Logic bugs

Then you can return to your code and fix it.

<img width="1135" height="931" alt="20th" src="https://github.com/user-attachments/assets/d10044e1-f021-48bd-9724-5345003625b9" />

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
