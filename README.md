# DS
> For the Neo4j database, create a file "neo4j.properties"
>
> If you have set up a neo4j database remotely, just replace "localhost" with remote ip address
>
> Default username and password are all neo4j

```
url=jdbc:neo4j:http://localhost
user=yourusername
password=yourpassword
```
**The above is all I know about neo4j, I'm still confused with the syntax**

# 20/05/2021 First Meeting
- Discuss about the project
- Discuss about the implementation of Student and their Relationships
- Discuss about the graph database Neo4j
- Discuss about the implementation of events
- Assign work to each person
  - Toh, Niu -> event 3, 4, 6
  - Liu, Cheong -> event 1, 2, 5, neo4j db
- Discuss the time for next meeting - 27/05/2021

# 28/5 Second Meeting
+ yeyang & huiting: 1,2,5（Week 12一定要弄好） + parallel farming(不是Week 12)
+ toh & niu：3，4，6（Week 12一定要弄好）+ six degree（不是Week 12）

# Handbook
### E3 Lunch:
+ **How to use?**
  ```java
  E3Lunch VARIABLE1= new E3Lunch(YOUR STUDENT ARRAYLIST HERE); // constructor
  ArrayList<Student> VARIABLE2 = VARIABLE.receiver(STUDENT OBJECT YOU); // functional method
  System.out.println(VARIABLE2.getLunchList(ans)); // printer
  ```
  Sample Output:
  ```
  --------------------------------------
  I can have lunch with Student 4,3.

  Student ID:4
  Lunch Period: 11:35-->12:09
  Student ID:3
  Lunch Period: 12:28-->13:00
  --------------------------------------
  ```
+ **How to test?**<br>
Uncomment line 73->77 and line 81->97, then run it.

