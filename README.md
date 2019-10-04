##Set Up

## Prerequisites

After cloning the repo, install the dependencies present in requirements.txt file using the following command :

```
pip3 -r install requirements.txt
```
## Running the Application
I have used a virtual environment called **myvenv**. 
```
To activate virtual environment use following command in the homedirectory:

> source myvenv/bin/activate
```

There's already a database included in the repo ( db.sqlite3 ). So, there's no need of migrations. You can directly run the server using :
```
> python3 manage.py runserver
```

If you get any errors, probably your system is still using the default inbuilt python3.
You can use the below command which serves the same purpose as above :
```
> myvenv/bin/python3 manage.py runserver
```
