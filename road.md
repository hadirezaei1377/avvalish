at first we define our tables in dbdiagram.io website and after define tables and relations(like one to many), genereate postgresql codes.

after that we write migration file for our db and by docker ps command we check it out that its running or not.
docker start postgresql , this container is up and running.
create db in terminal by docker:
createdb --username=root --owner=root simple_bank.
after this creatation we can see the tables of db by tablePlus


