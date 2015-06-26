This project was created by typing -

brew install play (Mac OS X)

play new play-project

Pick Java project

cd play-project

play eclipsify

Right click on the project, select Properties then Java Build Path
In the Libraries tab, click Add Class Folder…
Check target/scala-2.9.1/classes and target/scala-2.9.1/classes_managed (yes, even though 
this was not a Scala project!)

Reference -

http://stackoverflow.com/questions/8273330/how-to-edit-a-play-2-0-project-using-eclipse