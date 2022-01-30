# YAML_programming


# RULES OF YAML
# 1) YAML document should start with three hyphens(---)
# 2) comments should be denoted by using pound sign (#)
# 3) key value pairs should look like this (key : value)
# 4) child elements should have indent of 2 spaces from parent
# 5) in the key, value pairs, value can be of multiple item
# 6) in case of multiple values for a key, we have to use list by using hyphen(-)
# 7) if there are multiple childs to parent, all the child should be having same indendation
# 8) string can be mentioned using either single quotes or double quotes and without quotes as well. mostly if a string 
# 9) we have to explicitly mention the datatype for the YAML to get detected.


# Extensions := .yaml or .yml 

# Basic syntax of YAML

# 1) Syntax of simple key value pairs

**Below example is having simple key value pairs for datatypes strings, numerics and float values


![image](https://user-images.githubusercontent.com/80065996/151697355-2d275d5e-76df-4635-b192-7c0355ecd9be.png)


# 2) if you are using any special character in strings, you have to use single quotes or double quotes

**Single quotes**


![image](https://user-images.githubusercontent.com/80065996/151697511-1732f4b1-f50b-4605-8c5c-e2548232a0b8.png)


**Double Quotes**


![image](https://user-images.githubusercontent.com/80065996/151697522-b3af01c6-a17c-41d3-a9de-1ad5fa7c9f49.png)


# 3) comments

**We need to use pound symbol (#) for comments


![image](https://user-images.githubusercontent.com/80065996/151697583-cd259414-ae44-46f8-8eed-54f463988ac2.png)


# 4) Object := grouping the key value pairs called as "Object"


![image](https://user-images.githubusercontent.com/80065996/151698335-2f2fbffe-91a9-4783-b2c5-a889bb8401f8.png)


**Above image shows group and its child


# 5) Lists


![image](https://user-images.githubusercontent.com/80065996/151698386-fbc35413-1d19-480d-9b35-9d49c5c6cd05.png)


# 6) Boolean - (true or false) && (on / off)
 

![image](https://user-images.githubusercontent.com/80065996/151698432-13ff9e69-50a1-457e-82a6-d82bc444ae46.png)


==========================================================================================================================================================

# YAML coding - Harsha tutorials

# YAML should always starts with three hyphens(---).

# sample simple YAML


![image](https://user-images.githubusercontent.com/80065996/151702540-ffb98aac-ecf2-40cb-97cf-195105e01f0e.png)


# when you need to mention multiple values for a particular group, you have to mention the details in hyphen(-).
# in the above image (AWS, devops) are the lists under courses group.


![image](https://user-images.githubusercontent.com/80065996/151702614-f74435f7-ca48-4d86-b9f5-fbb122ba16a6.png)


# even you can mention the in the array format in case of multiple values needed for groups. but in YAML, mostly we will see hyphen format rather than array format


# Another sample example of YAML


![image](https://user-images.githubusercontent.com/80065996/151702853-8c7c1d51-9d9c-4177-924a-3e7f2faf7993.png)


# We are going to write the number of students from Quality thought company:


![image](https://user-images.githubusercontent.com/80065996/151703068-debc5ae6-984b-4729-9aea-e60f205a69ff.png)


**STEP 1:**
**'Students' is the parent. students will come under this parent 'students' as shown in above image

**STEP2**

**we can optimize it slightly as shown below


![image](https://user-images.githubusercontent.com/80065996/151703207-95567f44-a06f-4e6c-bd17-b56d3f42a40d.png)


**we can follow 2 space indendation for YAML


**STEP 3**
**you can use 2 spaces or 3 spaces indendation for child but the thing is you have to maintain consistently throughout the file**
**if you see below every child of 'students' parent is in the same indendation.


![image](https://user-images.githubusercontent.com/80065996/151703417-4880f4d5-ff89-422c-a3c6-72104909a68f.png)


**below is the sample excel data we want to convert into YAML,**


![image](https://user-images.githubusercontent.com/80065996/151703666-59151c47-7b10-45dd-9ba5-b19c0290476b.png)


![image](https://user-images.githubusercontent.com/80065996/151703728-09b8760e-ea67-450f-a4ac-083ac32153d1.png)


**so we can add the student details as child items. we added details of 2 students. we can go ahead and add more students as a list **


# Example : "key" is single and "values" are multiple
# 'fruits' is key which is a single value and "Apple","orange","strawberry","Mango" are the values which are multiple mentioned as list(represented by  hypen(-))


![image](https://user-images.githubusercontent.com/80065996/151704075-20749c87-adeb-4cfd-a151-c2e31f635792.png)


# Example Details of employee. Single employee have multiple details


![image](https://user-images.githubusercontent.com/80065996/151704227-3f29c2ab-83ec-4a76-8f6b-1861511efe04.png)


![image](https://user-images.githubusercontent.com/80065996/151704388-f926cff6-8ce9-41a9-9b4b-06261c18583a.png)


# Remember here, this is not 'list'. This is just a key value pair so we didnt mention hyphen(-) to the details(childs) of martin(parent)


# We are going to raise ticket management system with YAML file


**1) Starts with parent 'theatres' and list of theatres available:**


![image](https://user-images.githubusercontent.com/80065996/151704690-2594ec05-97d7-45c2-8e7e-35e5201d041a.png)


![image](https://user-images.githubusercontent.com/80065996/151707798-5773e2de-a51e-411a-8c10-4504d495ffb5.png)


# Datatypes. YAML has datatypes but we need to explicitly specify them for YAML to get detected.


![image](https://user-images.githubusercontent.com/80065996/151708077-bad166ce-f90f-4958-881e-c368d14bc4d0.png)




