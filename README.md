# hms-python
Hospital Management System with PYTHON

			HOSPITAL MANAGEMENT SYSTEM IN PYTHON

			**Developed By Mayank Vishwakarma**

#Configure

```json
{
  "database": "database.db",
  "port": 5601,
  "host": "localhost"
}
```

How to run?

- Requires Latest version of Python installed ( Recommended Python3 ).

- Open Command Prompt as administrator.

- Check the version of Python with command " python --version ".

- Check the version of Pip with command " pip --version ".

- Run command to upgrade pip " python -m pip install --upgrade pip ".

- Run command to install needed modules " pip install flask && pip install flask_restful ".

- Go to the directory location (for e.g. " H: " {if H symbol is shown} then use " cd hms-python-master ").

- Run command to install packages " python setup.py install ".

- Run command to start server " python server.py ".

- Then go to " http://localhost:5601/ " manually or run Browser.py file in directory.

- admin page ****** username - admin ****** password - admin


				INTRODUCTION
			
Today, management has been automated in all hospitals.
➢ This has resulted in a drastic improvement in the efficiency of the management
system.
➢ It has brought in transparency in scheduling.
➢ It has also helped to minimize frauds.

What we have designed is a stand-alone management system where patients are
listed in a database and can be retrieved with the help of the unique Patient ID
during the process of Appointment.

The patients & doctor information can be added easily & responsively to the database and
can be edited as per the admin choice. Appointment can be set easily with accuracy to time.
They are not been deleted after their completion for future security purposes.

This model makes use of:

1. Python – Acts as a medium between MySQL and the web. It processes the
data that is inputted by the user into the web and returns the appropriate
output.
2. MySQL – Stores the Database / Inventory and the Temporary
database which contains all the details about patient, doctor and appointments.
3. Flask – It is a web development framework used by Python to host the web
server.
4. Flask RESTful – It is an application program interface (API) that uses HTTP requests
to GET, PUT, POST and DELETE data.
5. JINGA2 - It is a template used by flask to generate the web pages.
