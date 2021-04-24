Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial consulting company that creates a variety of personal financial plans for their client's savings, retirement, investments, and insurance needs.  Their goal for this project was to implement a secure file transfer system for a web application that also performed a checksum verification to confirm the data was not altered.  Specifically, they wanted to implement a cryptographic algorithm with a key to handle the encryption and decryption of the data.  

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I feel the strongest part of my analysis was identifying the vulnerabilities associated with not utilizing encryption to transfer their data.  I identified the specific reasons they need to encrypt all data and highlighted which algorithm would be best suited for their needs.  The consideration for choosing an algorithm was made by analyzing the speed, simplicity, and security of each algorithm and fitting it with the requirements for their business.  It is important to code securely because vulnerabilities can occassionally not be immediately apparent and have an extremely damaging impact on the long term success of the business.  By ensuring all code follows secure coding best practices, a company is able to help minimize the risk of being connected to the internet.  Software security adds value to a comapny by protecting them from hacks that could damage trust in the bussiness, cost the company money, and potentially lead to legal issues. 

What about the process of working through the vulnerability assessment did you find challenging or helpful?

The hardest part of the vulnerability assessment for me was matching the information on the dependency report with features in the program.  Since the dependency report returned a relatively large number of vulnerabilities, it was important to read through all of them and determine how relevant they were to the program.  It was occassionally difficult to determine if the vulnerability identified would actually have any impact on the program.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

I approached the increase in layers of security by analyzing what the needs of the business were and determining what potential security vulnerabilities already existed.  I then thought hypothetically about what may be added to the program in the future and determined a course of action to limit future changes to the code.  Essentially, I tried to think of vulnerabilities before they existed to proactively be secure rather than reactively.  I would use similar strategies in the future.  Identify the functions of the application, identify potential future functions, research for known vulnerabilities, and plan my code to be modular to make future updates easy.  I think the single best secure practice the company could have for the future is performing regular security evaluations to make sure the security that has been implemented is still the most secure option. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

When the code was complete, I ran the code and evaluated the checksum with different data inputs to confirm it was working correctly.  I was able to check for new vulnerabilities by rerunning a dependency check to see if the new dependencies I added had any known issues.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

Knowing how to research and implement cryptographic and hashing algorithms will surely be a valuable skill in the future.  As encryption becomes more prevelant, keeping all data encrypted will become the norm.  Knowing how to encrypt and decrypt data correctly will mean that any future programs I develop will have the ability to guarantee the safe storage of customer information.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would showcase my ability to implement the cyrptographic and hashing algorithms and create modular code that can be updated independently.  I think these two skills are incredibly valuable when aiming to follow secure coding standards.
