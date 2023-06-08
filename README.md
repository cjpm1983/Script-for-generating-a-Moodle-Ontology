# Script-for-generating-a-Moodle-Ontology

![Alt text](img/onto.jpg?raw=true "Ontology")
 
 Python script for generating an rdf file from the courses and teachers data in Moodle. (ELINF - VLIRED) 

![Alt text](img/vlired.jpg?raw=true "VLired")

############################################## #### ##########################
#####Settings : Modify the parameters on the config.yml file according to your environment.

#Connection
dbus username: moodle
dbpass:moodle
database hostname: localhost
database name: "moodle"

moodlebaseurl: "https://sample.moodle.server.com/"


#Addresses to access the url of a course or a user's profile
#If you haven't changed it the default is /course/view.php?id:2
cprofile: "course/view.php?id="
#If you haven't changed it the default is /user/profile.php?id:14
top profile: "user/profile.php?id="

#Ontology Data
#Where the moodle.owl file will be stored In this case a folder was created
#static inside the site's public folder
repository : "" #/var/www/html/moodle.uclv.edu.cu/static
#http location of the ontology. In this case accessing the static folder created within the site
ontology: "https://sample.moodle.server.com/static/moodle.owl"

############################################## #### ########
