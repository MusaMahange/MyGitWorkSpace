to run the code you first need to have wampserver on your machine or something similar.

you need create a database on myPhpAdmin called project
make sure that the username for PhPMyAdmin is root and that there is no password.

you need create a table called users which has 'email_adress' field, 'first_name' field, 'last_name' field, 'school' field, 'occupation' 
field and a 'password' field. make email_adress the primary key.

you need create a table called marks which has 'entry_id' field, 'email_adress' field, 'mark' field, 'assessment_name' field,
'course' field. make 'entry_id' the primary key and set it to auto increment.

you need create a table called info which has 'course' field, 'assessment_name' field,
'weighting' field, and 'total' field.

you need create a table called plagiarism which has 'email_adress' field, 'course' field,
'assessment_name' field, and 'plagiarized' field.

then you need to unzip the coms folder and place it on the wamp/www directory

then on your web browser type localhost/coms then you will be at the home page.

--------------------------------------------------------------------------------

note:

mark - should be set to integer.
weighting - should be set to integer
total - should be set into integer
entry_id - should be set to integer
plagiarized - should be set to boolean

all other columns should be set to VARCHAR
--------------------------------------------------------------------------------

example1 inputs:

email_adress: ntulisiyabonga@gmail.com
first_name: siyabonga
last_name: ntuli
school: computer science
occupaion: student
password: 12345

example2 inputs:

email_adress: musa@gmail.com
first_name: musa
last_name: mahange
school: computer science
occupaion: course coordinator
password: 12345


------------------------------

example3:

email_adress: ntulisiyabonga@gmail.com
mark: 40
assessment_name: tes1
course: comms3002
total: 60
weighting:12 
