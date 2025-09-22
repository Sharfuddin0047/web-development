# Doctype:-
1. Doctype is document type declaration that represents we are using html-5 version.
2. It is not a tag.

# Tag in HTML:-
1. Keyword enclosed by angular brackets(<>) is know as opening or starting of a tag.
<h1> --------> Opening Tag

2. When forward slash(/) with keyword enclose by angular bracketsis known as closing or ending of a tag.
</h1> ---------> Closing Tag

<h1>Namaste</h1>

<br> Hello World  


# VS-Code Shortcut:-
1. alt + z :- wrapping
2. ctrl + b :- open/close side bar
3. ctrl + / :- comment
4. ctrl + R:- Recent
5. shift + alt + down:- copy line down
6. shift + alt + up:- copy line up

# Hyperlink:-
1. Hyperlink is used to link or attach different documents to our web/html page.

2. To create hyperlink we use anchor tag(<a></a>) and inside anchor tag we use href attribute.

3. syntax:-
    <a href="" target=""></a>

# Target Attribute:- 
Target attribute is used to specify 
where to open the link.
 i) _self:- Open link in same tab.
ii) _blank:- Open link in new tab.


# List in HTML:-
1. List is collection or group of related items.

# Types of List:-
In html we have 3 types of list

1. Ordered List:- <ol></ol>
2. Unordered List:- <ul></ul>
3. Description List:- <dl></dl>

# Nested List:-
List inside another list is known as Nested List.

# Table in HTML:-
1. It is collection of rows and columns.
2. To create table in html we use <table></table> tag.
3. Here we are creating table row by row.
4. To create table row we use <tr></tr> tag.
5. To create cells, html provide 2 tags.
   i) <Th></Th> Tag:- It is used to create table heading cells.
   ii) <Td></Td> Tag:- It is used to create table data cells.

6. To provide title or caption to the table we use <caption></caption> tag.
7. Caption tag we have to write within table tag.

# Attribute of th and td tag:-
1. rowspan:- rowspan is an attribute used to span the cells on row basis.
2. colspan:- colspan is an attribute used to span the cells on column basis.

Examples:-
<th rowspan="2" colspan="3"></th>
<td rowspan="3"></td>
<th colspan="2"></th>

# Attribute of table tag:-
1. cellpadding
2. rules
3. border

# Thead:- 
The top most part of our table we have to write within <thead></thead> tag.

# Tfoot:-
The bottom most part of our table we have to write within <tfoot></tfoot> tag.

# Tbody:-
The remaining content of our table we have to write within <tbody></tbody> tag.


# Importance of Thead, Tbody and Tfoot tag:-
It is highly recommended to used inside table for better explanation of code and crawler's understanding purpose.


# Semantic Tag:-
It is 
1. Header
2. Nav
3. main
4. sectionSelf Explanatory Tag.
5. Article
6. Footer
7. Aside :- Advertisements


# Form in HTML:-
1. Forms are used to accept input from the user.
2. To create form in html, we use form tag.
3. To create input field we use input tag. It is unpair tag.
   <input type="text">
4. Input tag we have to write with in form tag.

# Attributes in input tag:-
1. type:- type attribute is used to specify which type of data we can accept in that input field.

1. text
2. tel
3. email
4. password
5. file mutliple attribute
6. date
7. time
8. datetime-local
9. search
10. url
11. range
12. color
13. number
14. radio
15. checkbox
16. hidden

2. name:- name attribute is used to provide name to the input field.

3. value:- value attribute is used to provide initial (starting) value to the input field.

4. disabled:- Input field is disabled. User can not access the input field.

5. readonly:- It will make the input field as readonly. user can access the input field but can not change or edit the value.

6. required:- It will make the input field as required or mandatory to be filled. If input field is empty form will not be submitted.

7. placeholder:- It is used to provide hint to the user.

8. autofocus:- It will automatically focus an input field after page reload or page open.

9. autocomplete:- It is used to provide suggestions to the user.
   on, off

10. maxlength:- 10

11. minlength:- 2

# Input Tag:- 
1. Input tag is single line input field.
2. It is unpair tag.

# Textarea:- 
1. It is used to create multi line input field.
2. It is pair tag.

cols attribute:- width of text area
rows attribute:- height of text area

# Label Tag:-
1. Label tag is used to connect text with the input field.
2. The text we want to connect we have to write within label tag.
3. To connect text with the input field we have to use id attribute inside input tag.
4. That id's value we have to pass to the label tag for attribute.
5. whenever user click on that text if will focus the respective input field.

# Fieldset tag:-
1. Fieldset tag is used to group form control and it is used to create one box around the form elements.
2. Fieldset tag we have to write within form tag.

# Legend Tag:-
1. Legend tag is used to provide title or caption to the fieldset tag.
2. Legend tag we have to write within fieldset tag.

# Select tag:- Select List/ Dropdown List
1. Select Tag is used to create select list or dropdown list.
2. To create select list we use select tag.
3. To create options we use option tag.
4. Option tag we have to write within select tag.

<select name="" id="">
        <option value=""></option>
        <option value=""></option>
        <option value=""></option>
        <option value=""></option>
</select>


# Datalist/ Suggestion List/ Autocomplete List:-

# Datalist tag:- Id attribute
# Input Tag:- list attribute

1. The Datalist Tag is introduced in Html-5.
2. The Html datalist tag is used to provide an autocomplete feature on the form element.
3. Datalist tag is a container tag.
4. It is block level element.
5. It is used to provide a list of predefined options to the users.
6. Datalist tag is used to create suggestion list or autocomplete list.
7. The <datalist> tag contains a set of <option> tags that define the options in the list.
8. We are binding the suggestion list with the input field, for this we have to provide 'list' attribute in the input tag and 'id' attribute in the datalist tag, this same 'id' we have to provide in the 'list' attribute of input tag.
9. Whenever the user inputs in the input field related suggestions are displayed.

10. The advantage of using the datalist tag is that it allows users to enter values that are not present in the options list.


# Communication Question:-
1. Tell me about yourself?
2. Tell me about your native place?
3. What is your hobbies?
4. What is your strengths and weakness?
5. What is your short term goals and long term goals?
6. Where do you see yourself after 5 years?
7. Why should i hire you?
8. Tell me any 2-3 qualities why should i hire/ not hire you?
9. How much salary you are expecting?
10. Are you comfortable to work in night shifts?
11. Which one is best WFH or WFO?
12. How do you know about this requirement?
13. How do you know about our company?

# Technical Questions:-
1. What is Label Tag?
2. What is Fieldset Tag and Legend tag?
3. What is the difference between id and class?
4. What is the difference between inline and block level element?
5. What are semantic Tag? Explain all?
6. What is List and How many types of list?
8. What is the importance of thead, tbody and tfoot tag?
9. What is Element, Void Element and Root Element?
10. What is Dropdown List? How to create?
11. What is Suggestion List? How to create?




