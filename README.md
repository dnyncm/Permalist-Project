//Create a database call permalist

//Create a table
CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  title VARCHAR(100) NOT NULL
);


//Insert the data
INSERT INTO items (title)
VALUES ('Buy milk'), ('Finish homework');

//npmi to install nodes

//Use nodemon to run index.js
