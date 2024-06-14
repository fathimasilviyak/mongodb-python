## Steps to follow:
<ol>
  <li>
    Connect to the mongodb server using the user name and password:
      
    mongosh -u root -p PASSWORD --authenticationDatabase admin local
  </li>
  <li>
    Switch the context to the training database.

    use training
  </li>
  <li>
    Create a collection called mycollection (to understand how to create a collection)

    db.createCollection("mycollection")
  </li>
  <li>
    Install the Pymongo driver: You need the Pymongo driver installed to access the MongoDB database from Python.

    python3 -m pip install pymongo
  </li>
  <li>
    Create the Python files mongo_connect.py, mongo_query.py, and mongo_glossary.py to connect to and query MongoDB.
  </li>
  <li>
    Run each python file using the command: python3 file_name.py
  </li>
  
</ol>


#### mongo_connect.py

<ul>
  <li>Create the connection url</li>
  <li>Connect to mongodb server</li>
  <li>Get database list</li>
  <li>Print the database names</li>
  <li>Close the server connecton</li>
</ul>


#### mongo_query.py
<ul>
  <li>Create the connection url</li>
  <li>Connect to mongodb server</li>
  <li>Select the 'training' database</li>
  <li>Select the 'python' collection</li>
  <li>Create a sample document</li>
  <li>Insert a sample document</li>
  <li>Query for all documents in 'training' database and 'python' collection</li>
  <li>Close the server connecton</li>
</ul>


#### mongo_glossary.py
<ul>
  <li>Create the connection url</li>
  <li>Connect to mongodb server</li>
  <li>Select the 'training' database</li>
  <li>Select the 'mongodb_glossary' collection</li>
  <li>Create documents</li>
  <li>Insert documents</li>
  <li>Query for all documents in 'training' database and 'mongodb_glossary' collection</li>
  <li>Close the server connecton</li>  
</ul>
