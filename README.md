<img src="https://br.udacity.com/assets/iridium/images/nanodegree-overview/shared/nd-projects/nd004/project-3.jpg" alt="Logs Analysis Project" width="300px">

# Logs Analysis Project - Vinícius Arruda#
* [Full Stack Web Developer Nanodegree](https://classroom.udacity.com/nanodegrees/nd004)

### Intro ###

You've been hired onto a team working on a newspaper site. The user-facing newspaper site frontend itself, and the database behind it, are already built and running. You've been asked to build an internal reporting tool that will use information from the database to discover what kind of articles the site's readers like.

The database contains newspaper articles, as well as the web server log for the site. The log has a database row for each time a reader loaded a web page. Using that information, your code will answer questions about the site's user activity.

The program you write in this project will run from the command line. It won't take any input from the user. Instead, it will connect to that database, use SQL queries to analyze the log data, and print out the answers to some questions.

Project developed 

### Setup ###

* Installing VirtualBox:
VirtualBox is the program that runs your Linux virtual machine. Install the platform package for your operating system. You do not need the extension pack or the SDK. You do not need to launch VirtualBox after installing it.

* Installing Vagrant:
Vagrant is the program that will download a Linux operating system and run it inside the virtual machine. 

* Bringing up the database server:
Vagrant takes a configuration file called Vagrantfile that tells it how to start your Linux VM. Put this file into a new directory (folder) on your computer. Using your terminal, change directory (with the cd command) to that directory, then run vagrant up.

* Download the data:
Next, download the data and unzip the file called newsdata.sql. Put this file into the vagrant directory, which is shared with your virtual machine.
To build the reporting tool, you'll need to load the site's data into your local database. Review how to use the psql command in this lesson: (FSND version) (IPND version)
To load the data, cd into the vagrant directory and use the command psql -d news -f newsdata.sql.

* Running the code:
Run python3 newsdata.py from the command line to execute the program.

### Contact ###

* [vinicius.silva.arruda@gmail.com](mailto:vinicius.silva.arruda@gmail.com)
