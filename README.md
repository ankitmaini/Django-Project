We will write a web app called Learning Log that allows the isersw to log the topics they are interested in and to make journal entries as they learn about each topic. The Learning Log home page should describe the site and invite users to either register or log in. Once logged in, a user should be able to create new topics, add new entries and read and edit existing entries.

# Creating a Virtual Environment
## A virtual environment is a place on the system where we can install packages and isolate them from all other Python packages. Separating one project's libraries from other projects is beneficial and will be necessary when Learning Log is deployed to a server.


# Setting up the virtul environment
1. We made a new directory named learning_log.
2. Navigated to the learning_log directory.
3. Then typed:
             python -m venv ll_env
4. After the virtual environment is created, we switch to it by typing:
              ll_env\Scripts\Activate


# Installing Django
1. Activated the virtual environment.
2. Typed:
        pip install Django
        to install Django in the virtual environment.
3. 