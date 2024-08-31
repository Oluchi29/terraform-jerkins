# terraform-jerkins
this is a terraorm jenkins installation and other awes resources{IAC}
installing jerkins software on port 8080
creation of vpc
public and private subnet
routables
internet gateway
ec2 instances for public and private
.gitignore
all in terraform

for your jenkins configuration
ssh to your public ip on aws and ron it on vscode
run this command
sudo cat what is displayed on the jenkins page(/var/lib/jenkins/)
it displays a password
paste d password on ur jenkins page and start ur configuratios
username
password
fullname
email
then save
you will see the display welcome to jenkins
click on new item(on the left hand side)
enter item name e.g(project-jenkins-pipeline)
click on pipelinr
enter ok
click on try sample
select hello world
apply
save

click on build name
click on (#1 is green in color)
it displays console output
there it shows if the pipeline is successfully created

to check the pipeline created on vscode
on ubuntu prompt
cd /var/lib/jenkins/
enter
ls
cd jobs
ls
cd pipeline
ls
it displays the files created.

# jenkins is used for continious integration and deployment.
