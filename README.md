# Contacts (in Python)
* Creating a **Command Line Interface** to simulate a contact app.


## Libraries
* [MySQL](https://www.mysql.com/) (**Used as the database of choice**)
* [Mysql Connector](https://pypi.org/project/mysql-connector-python/)
* [Rich](https://rich.readthedocs.io/en/stable/introduction.html)
* [Tabulate](https://pypi.org/project/tabulate/)
* [Pyfiglet ](https://pypi.org/project/pyfiglet/0.7/)
* [Colorama  ](https://pypi.org/project/colorama/)


## Limitations  
* It is based on the command line ( no GUI ),
* Provides basic features for contact manipulation,



## Future Improvements
* Provide the user with more flexibility with their contacts app. (Kindly suggest, If you have something in mind),
* Provide a powerful **GUI-like app** (maybe using Tkinter),
* Reduce overall LOC.



## Update 1 (24/08/2023)
* The code now makes the required **database** and the **tables**,
* Error checking for creating the above-given parameters has also been added.




## Update 2 (24/08/2023)
* **show_all()** will first check if the table is **empty** before unpacking the variables (to avoid unpacking errors).



  
## Update 3 (29/08/2023)
* Added **close_server** function to close the SQL server when the user chooses to quit the application.



## Update 4 (08/09/2023)
* Now you can type **cls** and clear the terminal whenever you need to do so.




## Update 5 (08/09/2023)
* With the help of the **pyfiglet** library, Added a attractive banner called **Pycontacts**.




## Update 6 (24/05/2024) 
* Fixed some issues with the **regex patterns**,
* Updated the **requirements.txt**,
* Added more styling to the title "Pycontacts" and went for an 80s style. 




## Update 7 (08/03/2025) 
### Improvements to main.py:
  * Error Handling:
    * Added proper exception handling with try/except blocks
    * Ensures database connection closes properly on unexpected exits

  * UI Enhancements:
    * Added auto-reset for Colorama to prevent color bleeding between outputs
    * Added cross-platform terminal clearing support ( for  Windows and Linux/macOS systems ) 
    * Added color for error messages
    * Added fallback display if pyfiglet fails

### Improvements to database_operations.py:
  * Validation Functions:  
    * Implemented a get_validated_input() function to reduce repetition

  * Security Enhancements:
    * Replaced string formatting with parameterized queries

  * User Experience:
    * Added color coding for different message types (success, warning, error)



