SYSTEM WIDE TESTING

HOME PAGE

Button – 

`           `1 . Manage examinations.

`           `2. Class manage

`          `3. Students manage

`          `4. Manage invigilator

1 .MANAGE EXAMINATIONS 

Links to Examinations page 

-details of upcoming examinations are displayed

\_details include

`                                  `create button(for new exams) **( Not functional**)

`    `- Si no, exam name, action (view)  .(functional)



`                                   `Action (view button)

`                                  `Displays details of respective examinations

`                                  `Name of examinations, add(button)(**not functional)**

`                                   `-Date, invigilator(button),subjects(button)

`                                      `Invigilator(button)-

`                                      `Details of invigilator for the exam (name,class room,duty count,),action(change)                                                                       

`                                                                              `**Back to previous page, change button is Not functional**
**
`                                     `Subjects(button)** 

`                                    `Details of subjects, download button **-not functional,** add button**-not functional**

`                                     `-  Subject code, subject name, no: students, action(view button)

`                                      `Action (view button)

`                                         `Exam hall details, button(download,edit(**NOT FUNCTIONAL))**

`                                        `-Exam hall, no:students, action(view,download (**NOT FUNCTIONAL))**

`                                        `Student details , Add button**(Not functional)**

`                                        `-Regno,name,DOB,Department,status,action(delete)**not functional**))

`                                                                              `**Back to previous page button is not functional**

`  `2 Class Manage **(NOT FUNCTIONAL)**

3 Student Manage

`    `STUDENT DETAILS

Department wise search bar(drop down list), Name or Roll no: wise search bar, search button    

Checked all test cases for searching 

Results

`  `\*  No result if space,special characters, numbers or letteres not included in any name or roll      no: is searched

**!!Bug found (no prefference)**

\*Case1 ;If 2 is searched as roll no:

` `1<sup>st</sup> result will be -rollno: 125 and corresponding student details

up to 14 row results then starts roll no: with 2 ie:20021…

`    `suggestion\* use different sql querry or add separate conditions for displaying         

`                                                                                                                                `data

!!

Display all student details by default 

-roll no, name, department,academic year, view(button)

View(button)

-Display respective student details with

Edit(button),delete(button) both are functional

**Attended exam details(no data ), date(no data**)

`           `**Suggestion: Add link to home page from student details (to avoid difficulty of user to go**

`                                        `**back to home page due to numerous search and filter) ,**

`                            `**Add link to STUDENT DETAILS page from Student Data Update(to avoid difficulty** 

`                         `**of user to go back to student details after numerous data updation on each** 

`                       `**student details).** 
**


`   `4. Manage invigilator**(NOT FUNCTIONAL)**

