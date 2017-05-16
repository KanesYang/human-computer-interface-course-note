## Date: 5/16/2017

---

## Software Engineering



Bad Practice: waterfall model

|      |                       |                 |                                       |
| ---- | --------------------- | --------------- | ------------------------------------- |
| 1    |                       | get requirement |                                       |
|      | ↑                     | ↓               | ↑                                     |
| 2    |                       | analysis        |                                       |
|      | ↑                     | ↓               | ↑                                     |
| 3    |                       | design          | (architecture design / specification) |
|      | ↑                     | ↓               | ↑                                     |
| 4    |                       | implementation  |                                       |
|      | ↑(user center design) | ↓               | ↑                                     |
| 5    | have impact           | testing         | （flow of information)                 |
|      |                       |                 |                                       |

**Analysis:** object => concept

**Synthesis**: idea, concept => objects



---

## Human Computer Interface Design

Conceptual design ( **with requirement** )



Note: never could get all requirement from user, designer have to guess the user requirement, then implement it and show to user, then make some changes to specify again, to analyze (that is where the software need to be **Modifiable**), then to make the right one.



|      |        |      |                                          |                              |                                          |        |
| ---- | ------ | ---- | ---------------------------------------- | ---------------------------- | ---------------------------------------- | ------ |
|      |        |      | informal Behavior(concept of behavior)   |                              |                                          |        |
|      | ↙      |      | ↓                                        | 1. processing 2. methodology | implementation <=> concept (**user centered design**) | ↘      |
|      | system |      | system has behavior                      |                              |                                          | system |
|      |        |      | system/real behavior/physical implements |                              |                                          |        |
|      |        |      |                                          |                              |                                          |        |

---

## Design Architects

**UML (Unify Modeling Language)**

SRS (*Software Requirements Specification*)

 

**Requirement from  user** = informal spoken requirement



**SRS** (spoken requirement specification)



**SRS:** 

1. **functional requirement**: (contains input / output states): security, performance, reliability, Avoidability, Latency, usability (not for system, must in a real usage scenario)
2. **Non-functional requirement**: scalability, reusability **(=> modular code)**, modifiability, readability,extensibility



### **2 categories**

1. **structural**
2. **behavioral**



### **State Chart / State diagram**: 

Category: behavioral (**exception:**  for some state chart that have high hierachical, also have structural)



### Object / Class diagram

category: structural (exception: for each object and class are both structural and behavioral for having methods, but for the input/output part are only structural for having no methods)



### Use Case diagram

category: behavioral



**What is use case?**

Use case is just a state, is what you can do, is case of use, is what the user ***<u>is doing</u>*** , **at any one time**, it means one user could only **do one thing**, in which state



### User scenario

Category: behavioral

User will compare physical behavior with conceptual behavior in the user scenario



