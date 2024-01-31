# AP Computer Science Principles
Tuesday, January 30th 2024

### Introduction to Lists

**AIM:** What are lists in Computer Science, what are their benefits, how can they help us manage the complexity of our programs, and how can we code them?

**OUTCOME ALIGNMENT:**
<br><ins>IEC.TYS62XT.2</ins>: Apply computational thinking skills to a variety of tasks.
<br><ins>IEC.TYS62XT.3</ins>: Code using appropriate logic.
<br><ins>IEC.TYS62XT.4</ins>: Code using appropriate syntax.

**SUCCESS CRITERIA:**
- [ ] I can code a list.
- [ ] I can display an element of a list given its index.
- [ ] I can change an element in a list.
- [ ] I can append a new element to a list.
- [ ] I can remove an element from a list given its value or position.
- [ ] I can display the length of a list.
- [ ] I can analyze code involving basic lists.
- [ ] I can describe the basic structure and syntax of lists.
- [ ] I can describe the benefits of using a list as a data abstraction in a program.

**DO NOW:** Write down a list of anything.

**AGENDA:**

1. What are lists in real life?
2. What are lists in Computer Science?
3. Code-a-long:
   * Basic syntax.
   * Indexing.
   * Appending / removing elements.
4. Coding exercises.
5. List benefits / manageing complexity of programs.
6. AP Exam pseudocode.

**CODING EXERCISES:**

1. Create a new Python file in your Computer Science portfolio on your virtual machine.
2. Name your file, `LastNameFirstInitial_ListExercises.py`. 
3. Copy/paste the code below to your file.
4. Complete all exercises.
5. Save and upload your file to your Computer Science portfolio on GitHub.

**Remember to include an appropriate commit message.**

```python
# 1. Write some code to generate a list containing at least five of your favorite foods, colors, sports teams, or any other category of your choosing, and assign it to an appropriately named variable:

## YOUR CODE GOES HERE ##


# 2. Write some code to display your list:

### YOUR CODE GOES HERE ###


# 3. Write some code to display the first element in your list using its index:

### YOUR CODE GOES HERE ###


# 4. Write some code to display the length of your list:

### YOUR CODE GOES HERE ###


# 5. Write some code to change the last element in your list to a different food, color, sports team, etc., and then display your list:

### YOUR CODE GOES HERE ###


# 6. Write some code to append a new food, color, sports team, etc. to your list, and then display your list and the length of your list:

### YOUR CODE GOES HERE ###


# 7. Write some code to remove the fourth element of your list using its value, and then display your list and the length of your list:

### YOUR CODE GOES HERE ###


# 8. Write some code to remove the second element of your list using its index, and then display your list and the length of your list:

### YOUR CODE GOES HERE ###

```

**HOMEWORK:** 
1. Watch AP Classroom 3.2 Daily Videos 1 through 3 (assigned in AP Classroom and links in reference section below).
2. Complete List Practice (assigned in AP Classroom).
3. If you have not completed and uploaded today's coding exercises by the end of class, you must see Mr. Swotinsky at the end of the day for support.

##
**REFERENCE:**

|List Basics|
|---|
|1. Lists are used to store collections of data.<br><br>2. Lists are enclosed in brackets with each item separated by a comma.<br> *Ex/ `colors = ['red','orange,'yellow','green','blue','purple']`*<br><br>3. The variable a list is assigned to is considered the name of the list.<br>*Ex/ The name of the list above is `colors`.*<br><br>4. The items in a list are known as elements.<br>*Ex/ The elements of the list above are `'red'`,`'orange'`,`'yellow'`,`'green'`,`'blue'`, and `'purple'`*<br><br>5. The length of a list is the number of elements it contains.<br>*Ex/The length of the list above is 6.*<br><br>6. Each item in a list is assigned a whole number index to identify its position in the list.<br>**In <ins>Python</ins>, the index of the first element in a list is <ins>zero</ins><br>However, on the <ins>AP Exam</ins>, the index of the first element in a list is <ins>one</ins>.**<br>*Ex/ In Python, the index of `'red'` is `0`, the index of `'orange'` is `1`, the index of `'yellow'` is `2`,etc.<br>Ex/ On the AP Exam, the index of `'red'` is `1`, the index of `'orange'` is `2`, the index of `'yellow'` is `3`,etc.*|

<br>

|To...|Code...|
|-|-|
|...access the element at index, `i`, of `my_list`.|`my_list[i]`|
|...change the element at index, `i`, of `my_list`to `new_element`.|`my_list[i] = new_element`|
|...append `new_element` to `my_list`.|`my_list.append(new_element)`|
|...remove the first occurence of `this_element` from `my_list`.|`my_list.remove(this_element)`|
|...delete the element at index, `i` from `my_list`.|`del my_list[i]`|
|...determine the length of `my_list`.|`len(my_list)`|

<br>

|Benefits of Lists / How Lists Manage Complexity of a Program|
|---|
|1. Lists allow us to bundle related elements together.  So, one variable can be used to represent a list instead of using a separate variable for each element in the list. <br>*For example, imagine a list that represents an online shopping cart.  Without using a list, a new variable would be needed everytime an element is added to the shopping cart.*<br><br>2. The length of a list can be changed by appending elements to or removing elements from the list. This allows us our program to update a list as it runs.<br>*For example, consider the shopping cart example again.  The length of the list can change every time an item is added to or removed from the shopping cart.*  <br><br>3. Lists improve the readability of a program.<br>*For example,*<br>`cart = ['milk','eggs','flour','sugar']`<br>*is more elegant than*,<br>`cart_0 = 'milk'`<br>`cart_1 = 'eggs'`<br>`cart_2 = 'flour'`<br>`cart_3 = 'sugar'`<br><br>4. Lists allow us to easily apply the same algorithm to all elements within the list.<br>*For example, all grades in a list of grades could be rounded to the nearest whole number, or all prices in a list of prices could be discounted by 10%.*|

<a href='https://apcentral.collegeboard.org/media/pdf/ap-computer-science-principles-exam-reference-sheet.pdf'> **Click here for the AP Exam Reference Sheet**</a> (See page 3-4 for list operations)

**AP Classroom Videos:**<br>
<a href='https://apclassroom.collegeboard.org/d/r95gljggp1?sui=103,3'>Click here for AP Classroom 3.2 Daily Video 1 (Data Abstraction 1)</a><br>
<a href = 'https://apclassroom.collegeboard.org/d/ot676bj0ey?sui=103,3'>Click here for AP Classroom 3.2 Daily Video 2 (Data Abstraction 2)</a><br>
<a href='https://apclassroom.collegeboard.org/d/w0pwn2qus4?sui=103,3'>Click here for AP Classroom 3.2 Daily Video 3 (Data Abstraction 3)</a><br>
