`CS 230 Project Software Design Template.docx` is a software design document. It explains the software requirement of software that the clinet `The Gaming Room` want to develop. 
Clinet wants to develop online webbased Game `Draw It or Lose It`. Game has to support multiple client platforms which include both desktop and mobile clinets.
On the clinet side, An game will include multiple teams. it will render images from a large library of stock drawings as clues, and team will guess in one minute. If the team does not guess the puzzle before time expires, the remaining teams have an opportunity to offer one guess each to solve the puzzle with a 15-second time limit.

The best part about this design is that design approach itself where we chose to save the image in 30 chunks. This approach has multiple benefits: 
<br>Low network bandwidth required per client on server.
<br>Server can support multiple concurrent connectiosn because of low memory usage.
<br>No memory required at client side to save the image, as client will render the image as soon it gets it. It does not have to wait to download the complete image.
<br>Dividing image into chunks is offline process so it does not interfere with server run time.

The other salient feature in the design document is the design that we prosoed on how we can deploy the application in cloud. And how we can leverage the cloud serveice like api gateway, containers. kubernetes to increase throughtput and High availablity of application.

Process of working through developing design document throughout the course has been extremely helpful. It forced us to think from clinet perspective and how we can help customer achieve best out of out technical competencies. It helped us to think about the initial problem statement, It helped us to think about the chosing the right server platform by letting us comapre differnet available operating platforms. It pushed us to think about the approach that is required for client server applications. While designing it helped us to analyze the memory/storage security requirements. And once we thought that we have all that is required to develop an application, than it again asked us to think about how we would port this application cloud to leverage all the salient featire that cloud just offers by default.

In all, it was exhaustive but fruitful excersize and helped us to think deeply about software design and various aspects that are involved with software designing.

If I have to revise one part of this document again, then I would like to revisit the security aspect of the game and would like to add all the salient features of security that cloud can offers us, like `Identity management`, `Security zoning`, `Key management`, etc. The better undertanding of the cloud security can help us enhance the security of application.

I think it will be an overstatement if I say that the most important thing while developing any software is to correctly understand the user requirements. It is also the most exhaustive and iterative process. Because users have an idea about the application but software design document helps in documenting an idea into concrete implementations.

My personnel approach to design an software will be along the lines of the software design document where it will discuss the problem statements in details, will propose multiple implementation with pros and cons of each implementation. It will emphasize upon the cost of development, cost of maintainability and other licensing cost. It will discuss the contrast between deploying the application on private or public cloud and cost associated to both in short term and long terms. While designing documents, we will always keep customers in loop to get their constant feedback and any change of ideas while application was being developed.



