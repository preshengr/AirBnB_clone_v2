## AirBnB_clone_v2 - MySQL

### Project Description
The **AirBnB_clone_v2** project aims to develop a MySQL database for an Airbnb clone. This project is a collaborative effort between two team members: Stanley Anyumba and Margaret Wangechi.

### Background Context
In this project, we'll focus on the following key aspects:

1. **Environment Variables**: These variables play a crucial role in configuring our application. Here are the relevant environment variables:
   - `HBNB_ENV`: Specifies the running environment (e.g., "dev" or "test").
   - `HBNB_MYSQL_USER`: MySQL username.
   - `HBNB_MYSQL_PWD`: MySQL password.
   - `HBNB_MYSQL_HOST`: MySQL hostname.
   - `HBNB_MYSQL_DB`: MySQL database name.
   - `HBNB_TYPE_STORAGE`: Type of storage used ("file" using FileStorage or "db" using DBStorage).

### Files in the Repository
Let's explore the files and directories within the **AIRbnb_clone_v2** repository:

1. **`0-setup_web_static.sh`**: Sets up the web static environment.
2. **`1-pack_web_static.py`**: Creates a `.tgz` archive from the contents of the `web_static` folder.
3. **`Update 1-pack_web_static.py`**: An updated version of `1-pack_web_static.py`.
4. **`100-clean_web_static.py`**: Deletes outdated archives.
5. **`Update 100-clean_web_static.py`**: An updated version of `100-clean_web_static.py`.
6. **`101-setup_web_static.pp`**: Puppet script to set up the web static environment.
7. **`Create 101-setup_web_static.pp`**: An additional version of the Puppet script.
8. **`2-do_deploy_web_static.py`**: Deploys the web static files to the servers.
9. **`Update 2-do_deploy_web_static.py`**: An updated version of `2-do_deploy_web_static.py`.
10. **`3-deploy_web_static.py`**: Creates and distributes an archive to the web servers.
11. **`Update 3-deploy_web_static.py`**: An updated version of `3-deploy_web_static.py`.
12. **`console.py`**: Interactive command interpreter.
13. **`setup_mysql_dev.sql`**: SQL script to set up the development MySQL database.
14. **`setup_mysql_test.sql`**: SQL script to set up the test MySQL database.
15. **Directories**:
    - `models`: Contains relevant Python models.
    - `tests`: Includes test files.
    - `web_flask`: Web framework related files.
    - `web_static`: Web static files.

### Resources
For further exploration and learning, consider the following resources:

- [cmd module](https://docs.python.org/3/library/cmd.html)
- [unittest module](https://docs.python.org/3/library/unittest.html)
- [args/kwargs](https://docs.python.org/3/tutorial/controlflow.html#more-on-defining-functions)
- [SQLAlchemy tutorial](https://docs.sqlalchemy.org/en/20/tutorial/index.html)
- [How To Create a New User and Grant Permissions in MySQL](https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql)
- [Python3 and environment variables](https://docs.python.org/3/library/os.html#os.environ)
- [SQLAlchemy MySQL 8.0 SQL Statement Syntax](https://dev.mysql.com/doc/refman/8.0/en/sql-syntax.html)

Feel free to explore these files and dive into the world of Python ORM! 😊🐍🔍
