### DQL ###

SELECT email FROM users WHERE name='Chelsea Wetzel';
# Uppercase commands is optional
select email from users where name='Chelsea Wetzel'
# Single quotes required

# Split command up into multiple lines
SELECT email
FROM users
WHERE name = 'Chelsea Wetzel';
# Semicolon means it is the end of the statement

### DML ###

# add 
INSERT INTO <table name> (<column name>)
VALUES (<some values>);

INSERT INTO Category (CategoryName, Description)
VALUES ('Frozen', 'Ready-to-eat meals');
# Will allow you to create a new row in db

# update
UPDATE <table name> 
SET <column name> = <some value>
WHERE <column name> = <some value>;

UPDATE Category
SET Description = 'Desserts and ready-to-eat meals'
WHERE Id = 9;

# delete
DELETE FROM <table name>
WHERE <column name> = <some value>

DELETE FROM Category
WHERE Id=9;

