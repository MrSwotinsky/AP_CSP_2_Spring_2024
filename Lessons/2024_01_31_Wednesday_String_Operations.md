# AP Computer Science Principles
Wednesday, January 31st 2024

### String Operations

**AIM:** What are strings in Computer Science, and how can we perform operations on strings?

**OUTCOME ALIGNMENT:**
<br><ins>IEC.TYS62XT.2</ins>: Apply computational thinking skills to a variety of tasks.
<br><ins>IEC.TYS62XT.3</ins>: Code using appropriate logic.
<br><ins>IEC.TYS62XT.4</ins>: Code using appropriate syntax.

**SUCCESS CRITERIA:**
- [ ] I can describe the basic structure and syntax of strings.
- [ ] I can reference a character in a string given its index.
- [ ] I can perform string operations.
- [ ] I can using code tracing strategies to make my thinking visible while performing string operations.

**DO NOW:** In 10 minutes or less, create the most fashionable name bracelet you can.

**AGENDA:**

1. Name bracelets.
2. What are strings in real life?
3. What are strings in Computer Science?
4. String operations (interactive model/practice).

**STRING OPERATIONS:**

A program contains the following procedures for string manipulation.
 
|Procedure Call|Explanation|
|-|-|
|`len(str)`|Returns the number of characters in `str`.  <br><br>*For example, `len('party')` returns`5`.*|
|`concat(str1,str2)`|Returns a single string consisting of `str1` followed by `str2`.<br><br>*For example, `concat('cup','cake')` returns`'cupcake'`*.|
|`substring(str,start,length)`|Returns a substring of consecutive characters from `str`, starting with the character at position, `start`, and containing `length` characters.<br><br>*For example, `substring('balloons',2,3)` returns`'all'`*.|

<br>

> **Example 1/**
> What will be stored in `word` when the code segment below is executed?
>
> ```
> word = 'data'
> word = substring(word,2,2)
> word = concat('gre', word)
> ```

<br>

> **Example 2/**
> What will be stored in `vacation` when the code segment below is executed?
>
> `vacation = concat(substring('cyber',3,2),substring('yacht',2,3))`

<br>

> **Example 3/**
> What will be stored in `fruit` when the code segment below is executed?
>
> `fruit = concat(substring('recursive',len('RAM'),3),substring('vibrant',4,4))`

<br>

> **Example 4/**
> A programmer is writing a code segment to change the format of date records stored as a strings.
>
> The current format for each date record is the ten-digit string, `'MM/DD/YYYY'`, where MM represents the month as a two-digit number, DD represents the day as a two-digit number, and YYYY represents the year as a 4-digit number.
>
> The new format for each date record will be the eight-digit string, `'MM/DD/YY'`, where MM represents the month as a two-digit number, DD represents the day as a two-digit number, and YY represents the year as a 2-digit number.
>
> To accomplish this, the programmer writes a code segment that is intended to remove the 7th and 8th characters of each date record.
>
> a) Will the following code segment accomplish this task?
>
> ```
> new_date_record = concat(substring(date_record,1,6),substring(date_record,9,10))
> ```
>
> b) Will the following code segment accomplish this task?
>
> ```
> temp_date_record_1 = substring(date_record,1,len(date_record)-4)
> temp_date_record_2 = substring(date_record,len(date_record)-2,2)
> new_date_record = concat(temp_date_record_1,temp_date_record_2)
> ```

<br>

**HOMEWORK:** 
1. Watch AP Classroom 3.4 Daily Video 1 (assigned in AP Classroom and link in reference section below).
2. Complete String Practice (assigned in AP Classroom).  **Apply code tracing strategies to determine your answers.**
3. Capture an image of your code tracing work and save it as `LastNameFirstInitial_StringPractice_CodeTracing.tif`in your Computer Science portfolio on your virtual machine.
4. Upload your code tracing work to GitHub.

**Remember to include an appropriate commit message.**

##
**REFERENCE:**

**<a href='https://apclassroom.collegeboard.org/d/ncircsavfi?sui=103,3'>Click here for AP Classroom 3.4 Daily Video 1 (Strings)</a>**


**<ins>Examples of String Procedure Calls</ins>**

**Note:** The table below includes some, but not all, possible examples of string procedure calls.  Additionally, always take a moment to read the explanation for string procedure calls. Do not assume they are identical to the those listed in the table below.

|Procedure Call|Explanation|
|-|-|
|`len(str)`|Returns the number of characters in `str`.  <br><br>*For example, `len('abcde')` returns`5`.*|
|`reverse(str)`|Returns the reverse of  `str`.  <br><br>*For example, `reverse('abcde')` returns`'edcba'`*.|
|`prefix(str,length)`|Returns the first `length` characters of `str`.<br><br>*For example, `prefix('abcde',2)` returns`'ab'`*.|
|`suffix(str,length)`|Returns the last `length` characters of `str`.<br><br>*For example, `suffix('abcde',2)` returns`'de'`*.|
|`substring(str,start,length)`<br><br>(version 1)|Returns a substring of consecutive characters from `str`, starting with the character at position, `start`, and containing `length` characters.<br><br>*For example, `substring('abcde',2,4)` returns`'bcde'`*.|
|`substring(str,start,end)`<br><br>(version 2)|Returns a substring of consecutive characters from `str`, starting with the character at position, `start`, and ending with the character at position, `end`.<br><br>*For example, `substring('abcde',2,4)` returns`'bcd'`*.|
|`concat(str1,str2)`|Returns a single string consisting of `str1` followed by `str2`.<br><br>*For example, `concat('abcde','vwxyz')` returns`'abcdevwxyz'`*.|
