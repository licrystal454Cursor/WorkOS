Example application that integrates both SSO and Directory Sync. 

To Run the application first navigate to the python-flask-sso-example directory

   ```bash
   $ cd python-flask-example-applications/python-flask-sso-example
   ```

Next, create and source a Python virtual environment. You should then see `(env)` at the beginning of your command-line prompt.

   ```bash
   $ python3 -m venv env
   $ source env/bin/activate
   (env) $
   ```

Install the cloned app's dependencies.

   ```bash
   (env) $ pip install -r requirements.txt
   ```

Finally, to run the application run 
```bash
   (env) $ pip install -r requirements.txt
   ```
   flask run -p 5001

This should take you to the home page where you can sign in using WorkOS.
Additionally, in the top right there is a button with the words "Directory Users" that you can click to see a list of users in the Directory.  