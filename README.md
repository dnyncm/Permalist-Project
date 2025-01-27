//Create a database
CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  title VARCHAR(100) NOT NULL
);


//Enter the data
INSERT INTO items (title)
VALUES ('Buy milk'), ('Finish homework');
