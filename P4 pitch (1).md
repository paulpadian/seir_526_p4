-   Name of App: "Homework Solutions" - Not final name
-   Name: Paul Padian
-   Tech utilization: Vue/Typescript/Express/PSQL

1.  How do you plan on learning/implementing this new technology?
	-I plan to look at documentation for VUE, I want to write with typescript in vue because they 			interact well together. I plan to implement a psql/express backend with the app and integrate them with vue.
2.  What is your goal with this project?
	- Presentation/5 day goal: implement a student and teacher class of user, students can submit homework in pdf/text/docx format and teachers can markdown in app with comments/tags on areas of student homework. Implement decent user experience on student side to make app utilizable.
	- Extended goal -Students can receive submission of comments with markdowns displayed inline w/highlighting and basic text editing. implement greater level of security, look into RUBY backend in final version. Test application in actual school setting w/ family members.
3.  Who is the user for your app?
	-	teachers and students w/ 2 different portals/flows

4.  Any potential roadblocks you think you might run into?
	-Document rendering and upload with markdown could be hard but I've been looking into preview components for VUE and trying to work with that. Could end up being text only input if scaled down but allow inline comments.

![ER diagram of students/teachers/assignments/submissions/classes](https://i.imgur.com/muwsL2v.png)

## Teacher Flow
| Route| Description |
|--|--|
| / | Splash Page
| /signin | Sign in as teacher
| /profile |display all classes/create a class  |
|/class|show all open assignments /link to assignment creation/|
| /assignment:id | show individual assignment with show all submissions |
| /submission:id| show individual submissions w/markup display |
![Teacher Profile](https://i.imgur.com/GLyHgEk.png)
 ![class view](https://i.imgur.com/xiznP83.png)
![enter image description here](https://i.imgur.com/5fNVwwQ.png)
## Student Flow
| Route| Description |
|--|--|
| / | Splash Page
|/signIn|sign in as student|
| /profile |display all classes available / current submissions |
|/class|show all open assignments|
| /assignment:id | show individual assignment with title |
| /submit| student submission page |
  
![student profile](https://i.imgur.com/Nozgu7r.png)![individual class view w/submission](https://i.imgur.com/vtkjobT.png)![submission view](https://i.imgur.com/8sIVsZd.png)

## Trello
[Trello Link Here](https://trello.com/b/DHuqyNsA/p4-planning)
