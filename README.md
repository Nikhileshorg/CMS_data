**For this exercise, I have created dummy data for procedure attirbute, procedure success and procedure outcome. While creating, I have made sure that there are missing values in the data, which is similar in the real world data. As, I am not very experienced in the Procedures and its nomenclature, I have assumed only the following features into my dataset. **


**Data Dictionary**


Procedure_attributes:
1. Procedure_ID : Unique for every record. (Primary Key)
2. Procedure : I taken few examples from wikipedia about types of procedures and used those. I have used around 13 different procedures.
3. Time( in hours) : Time taken to complete the procedure.
4. Severity : Serverity of the Procedure. ( Have 4 categories : Low, Medium, High and Nulls)
5. Gender : Gender of the Patient undergoing procedure. ( Male, Female, Nulls)
6. Anesthesia : Was the patient administried with Anesthesia (Yes, No)
7. Diabetes : Does the patient has diabetes or not. (Yes, No, Nulls)

Procedure_success:

1. Procedure_ID : Unique for every record. (Primary Key)
2. Outcome : For every procedure, what is the outcome ?


Procedure_outcomes:

1. Procedure_ID :  Unique for every record. (Primary Key)
2. Severity of post procedure complications : Does the patient has any complications after procedure. (High, Low, Nulls)
3. Recurrence of original condition : Does the patient has recurred with the original condition. (Yes, No, Nulls)
4. Pain : Does the patient has pain after the procedure. (Yes, No, Nulls)


Link to my Github respository : https://github.com/Nikhileshorg/CMS_data

Based on the problem statment given, this is a classification type of problem. I have choosen xgb as the algorithm and Hyperopt as the optimization technique. I have tried Lightgbm as well but due to less data, it was not giving good accuracy scores. Based on the dataset. This is a classification type of problem.





