# AngularWar

To deploy Angular Project in Tomcat w two option 

Case 1:Using dist folder

1.	ng build --base-href=/angular/
2.	In Tomcat --Create angular folder under webapps and copy files from under dist->xyz .
----------------------------------------------------------------------------
Case 2 Using war file


jar -cvf my-angular-app.war *  -- if u want to create war use this
