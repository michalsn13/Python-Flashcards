## Guide for the project

**How to get started?**
 1. Install those Python libraries (if necessary): *psycopg2*, *psycopg.errors*, *re*, *datetime*, *logging*, *random*, *collections*, *time*
 2. Be sure that you have PostgreSQL with existing database.
 3. Put your database logging parameters in */Connection/'con_parameters.sample.py'* file.
 4. Rename the file to *'con_parameters.py'* (delete that *'sample'* part)
 5. Run *'prep.py'* successfully.
 6. Run *'app.py'* and follow the instructions.

**Main files:**
 * *menu.py*- with function menu() manages methods used in data classes in a more "user friendly" way, runs perticular code from given input
 * *app.py*- runs menu() from *menu.py* (if *'prep.py'* was run then it's the only code that needs to be run mannualy to start the app every time)
