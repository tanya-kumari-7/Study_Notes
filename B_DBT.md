# DBT
1. Create a folder (which will be dbt project)
2. Go inside created folder and use (code .) to open visual studio
3. create vertual eenviroment (which is .venv)
4. activate .venv
	PS C:\Tanya\CodeRepo\dbt_2nd_project> .\.venv\Scripts\activate
5. Insatll requrement.txt file
	dbt-core==1.8.0
	dbt-postgres==1.8.0
6. Install requrement file
	(.venv) PS C:\Tanya\CodeRepo\dbt_2nd_project> pip install -r .\installs.txt
7. run dbt init to intialize the project 
	(.venv) PS C:\Tanya\CodeRepo\dbt_2nd_project> dbt init
8. enter db info 
	  dbname: mydatabase
      host: localhost
      pass: 
      port: 5432
      schema: public
      threads: 4
      type: postgres
      user: postgres
  target: dev
