# LAB-1-ATM
## ATM and Banking SYSTEM
### AIM: 
To study the problem statement, SRS document and draw all the UML diagrams of ATM
System.

<br>

### SRS(Procedure):
#### Use Case Diagram
- First, identify the **actors** (like `Customer`, `Technician`) and the **system boundary** (the "ATM"). Then, list all the **use cases** (functions like `Withdraw Cash`, `Maintain ATM`) inside the boundary and connect the actors to the functions they perform.

#### Class Diagram
- Identify the main **classes** (nouns like `Account`, `Customer`). For each class, define its **attributes** (data like `+AccNo`) and **methods** (actions like `+checkBalance()`). Finally, draw lines to show **relationships** like inheritance ("is-a") and association ("has-a") between them.

#### Activity Diagram
- Map the step-by-step **workflow** for a single use case (like "Withdrawal") from a start node to an end node. Use **action** boxes for steps, **diamond** shapes for decisions (like "PIN Valid?"), and thick bars to show **parallel activities**.

#### Sequence Diagram
- Show how objects interact **over time** for one specific scenario (like "Account Creation"). Place objects as vertical **lifelines** across the top and draw **numbered messages** from top to bottom to show the exact sequence of calls between them.

#### Communication Diagram
- This diagram shows the **relationships** between objects rather than time. Place the objects (`Customer`, `Manager`, `ATM`) on the diagram, draw **links** between them, and then add **numbered messages** along those links to show the sequence of communication.

#### Package Diagram
- Group related classes from your class diagram into **packages** (like folders, e.g., `Accounts`, `Transactions`, `UserManagement`). This organizes your system into logical modules. Then, draw dashed arrows (dependencies) to show when one package needs to use a class from another.

<br>


### UML DIAGRAMS:
#### Usecase Diagram:

<img width="1192" height="913" alt="image" src="https://github.com/user-attachments/assets/8d2653ab-78f5-4970-95b1-65fe1b396f1a" />
<br>

#### Class Diagram:

<img width="1178" height="938" alt="image" src="https://github.com/user-attachments/assets/0291d41d-0d8a-483c-9527-a67eb6c87eb9" />
<br>

#### Activity Diagram:

<img width="903" height="940" alt="image" src="https://github.com/user-attachments/assets/9d67f86e-677a-4794-a5ed-f1573fc92486" />
<br>

#### Sequence Diagram:

<img width="1015" height="912" alt="image" src="https://github.com/user-attachments/assets/f8387e17-48bd-4532-ad37-eea2431950e0" />
<br>

#### Communication Diagram:

<img width="1047" height="852" alt="image" src="https://github.com/user-attachments/assets/dcc4160b-53fb-46b3-8627-b7338456f530" />
<br>

#### Package Diagram:

<img width="1190" height="512" alt="image" src="https://github.com/user-attachments/assets/645c5880-7f4d-4e9d-b1b5-2fb13581db35" />

<br>

### RESULT: 
Thus the Atm and banking System project was executed and the output was verified.
