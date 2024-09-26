Git install হয়েছে কি না তা cmd তে চেক করতে পারেন 
 
Git এ সাধারন্ত ২ ভাবে কাজ করা যায় – 
I.	Git GUI 		
II.	Git Terminal (Software engineer terminal ব্যবহার করে) 


Git= data management System
Github= server


Git 2 ভাবে কাজ করেঃ-
I.	Local (নিজের Pc থেকে file এ কাজ করা) 
II.	Remote (Cloud)
-----------------------------------------------------------------------------------
	Working directory -  Pc folder
	Repository – git যোগ করে file এর সাথে তখন 
	Staging Area -  জাচাই বাছাই করি এতে ।
	Git add – work থেকে staging area তে পাঠাবে
	 Git commit – Staging area থেকে যখন Local repository তে পাঠাই।
	Git push – Server এ file পাঠাতে ব্যবহার করা হয়।
	Git fetch – server থেকে file নামাতে চাইলে server থেকে Local এ
	Git clone – Server থেকে file pc তে নামাতে
	Git pull - Server থেকে direct work  directory তে update হয় file
	Git diff – work directory থেকে staging area তে file এর পাথক্য দেখাবে।
	Git diff Head - work  directory থেকে Local repository তে পাথক্য দেখাবে।
	Git marge – work  directory থেকে Local repository তে সকল file code এক করার জন্য ।
	Git checkout - Local repository থেকে file /code সরিয়ে work  directory তে নেয়ার জন্য ।


-----------Working Directory-----------

	git init  [git initialize]

[Team work এর জন্য name & email]

Global    [সকল project এর সাথে same name & email]
	git config  --global user.name (“Your name”)
	git config  --global user.email (“Your email”)

Local    [আলাদা আলাদা project এর সাথে name & email]
	git config  user. name “Your name”
	git config  user.email “Your email”

	git config --list   [email & name দেখা যায়]
----------Staging Area-------------

	git status     [file এর status দেখাবে]
	git add file name      [file add করবে]
	git add --all     [ একসাথে সব add হবে]
	git add .      [সব নেয় না]
	git add –A    [ একসাথে সব add হয়]
	git add *    [delete এর file তোলে না]

	git reset      [file আগের মত করে দেয়]
	git rm - -cached text name  [ ]
	git rm –r folder [ ]

	clear    [code clear করে ]

------------Commit---------------


	git commit      [ q দিয়ে commend form থেকে বাহির হওয়া যায়]

	git commit –m “Message” [commit হচ্ছে file এর change সম্পর্কে  লিখে  রাখা ]

	git log [commit log দেখা]
	git log --oneline [sort log দেখা]
	git checkout [ ]
	git checkout  master [ file আগের মত পেতে পারি]
	git diff [file এ কি change হয়েছে তা দেখায়]

	git rm text name [remove হয়]
	git reset HEAD~

	get reset - -hard [সব চলে আসবে]

	git show [কি upload করেছি তা দেখায়]

	[git add করলে তা git diff দিয়ে show হয় না তা ] git diff - -staged [দিয়ে দেখতে হয়]

	Git rm file_name [delete file]

	Git reset HEAD file_name    [full delete file]

	File ereat করতে হবে git hub এ then libk cmd তে দিতে হবে ।then push

করতে হবে।
	Git remote add origin Link…
	Git push –u origin  master
	Git push origin master –force
	Git remote –verbase

------------SSh---------------

	Control plan এ গিয়ে credentail manager এর ভিতরে Windows 
Credentails  এ ক্লিক করে git এর লিংক খুজে email remove করতে হবে। 
	ls - l [file name দেখাবে]


-----------git clone-------------

	git clone link  [git এর file destop এ আনতে পারছে]
	git clone line file name  [file name change করতে চাইলে]
	git fetch  [git থেকে কন file এর update করতে হলে]
	git pull  [file update হবে]

-----------git branching-----------------

	git  branch   “branch name”  [create]
	git  branch     [show branch]
	git checkout name  [যে branch এ যেতে চাই]
	git checkout  -b name  [একসাথে create এবং stay]
	git marge name   [move করা]
	git branch –D name  [branch delete]
	git stash
	git stash pop   []
	git stash apply   []
	git stash list
	git stash pop Serial num  [যে লাইনটা move হয় তা আসবে]
	git clean –f  [সব delete হয়ে যাবে]
	git clean –f –n   [সব delete হয়ে যাবে]

-----------Git ignore-----------

	touch .gitignore
	gitignore  text open করতে হবে এবং লিখতে হবে  *.psd

	fork [আরেক জন github থেকে copy করা]
	pull request
	git Localy initialition
	git globaly initialition

working থেকে stage  ----- all


----------git branch-----------

	branch –main/master/create
	git branch [কোন branch এ তা দেখাবে]
	git branch name [Create]
	git checkout development

	development branch
	git merge main –m  “massage”
	git merge development –m “massage”
---------Push--------------

	git push origin main
	git push origin staging

------------fetch------------

	git fetch     [এটা cloud এর main branch এ থাকতে হবে]
	git merge   [করতে হবে]

--------------Delete--------------

	rm  -fr .git   [file এর  ভিতরে initialize git file delete করে]


-----------Account Change----------------

Tesk bar এ -> Search -> credential manager এ গিয়ে git account delet করা দিতে হবে। 









