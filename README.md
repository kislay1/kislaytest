# kislaytest

1)
An Internet website typically consists of two main components: the front-end and the back-end. These components work together to create the functionality and user experience of a website.  

a)Front-end:
The front-end, also known as the client-side, refers to the part of a website that users interact with directly. It involves the design, layout, and presentation of the website.The primary technologies used in front-end development are HTML , CSS , and JavaScript.  

b)The back-end, also known as the server-side, handles the behind-the-scenes functionality of a website. It involves the server infrastructure, database management, and the processing of user requests.
 The server is a computer or a network of computers that host the website. It receives requests from users' browsers, processes them, and sends back the appropriate response. It also manages security, session management, and other server-side operations.
The database is where the website stores and retrieves data. It can be a relational database (e.g., MySQL, PostgreSQL) or a NoSQL database (e.g., MongoDB, Firebase). The back-end interacts with the database to perform operations such as storing user information, retrieving product details, and processing form submissions.  

The front-end and back-end divisions communicate with each other to provide a seamless user experience. When a user interacts with the front-end, such as submitting a form or clicking a button, the request is sent to the back-end server. The server processes the request, interacts with the database if necessary, performs the required operations, and sends a response back to the front-end. The front-end then updates the user interface based on the response received, providing real-time feedback to the user.  


 2)
   In HTML, tags are used to define the structure and elements of a web page. Tags are enclosed within angle brackets  and are used to mark up different parts of the content. Each tag serves a specific purpose and has a particular function.
   
   a)Heading Tags: Heading tags define the headings or titles of sections within a webpage. They range from h1 to h6, with h1 being the highest level and h6 the lowest.
   
 
   
   b) Paragraph Tags: Paragraph tags are used to enclose blocks of text that form paragraphs. They are represented by the "p" tag.  
   

   c)Link Tags: Link tags create hyperlinks to other web pages or resources. They are represented by the a tag and use the href attribute to specify the destination URL.  


   d)Image Tags: Image tags are used to embed images within a webpage. They are represented by the img tag and utilize the src attribute to specify the image file's source.  
 
   e)List Tags: List tags are used to create ordered (numbered) or unordered (bullet-point) lists. They are represented by the ol, ul, and li tags.  


   f)Form Tags: Form tags are used to create interactive forms on a webpage. They are represented by the " form" tag and contain various input elements, such as text fields, checkboxes, radio buttons, etc.

3)  Here are some key differences between MySQL (a relational database management system) and NoSQL (a non-relational database management system):

Data Model:

MySQL: MySQL follows a structured and predefined schema with tables, columns, and relationships. It uses a tabular format to store and retrieve data.
NoSQL: NoSQL databases use flexible and dynamic data models. They can be document-based, key-value pairs, wide-column stores, or graph databases. The data is stored in a format suitable for the chosen data model.
Schema:

MySQL: MySQL databases have a fixed schema that defines the structure of the data in advance. Any changes to the schema require altering the table structure, which may impact existing data.
NoSQL: NoSQL databases are schema-less, allowing for flexibility in the data structure. New fields can be added or modified without requiring changes to the entire database.
Scalability:

MySQL: Scaling MySQL databases can be challenging, especially for handling large amounts of data and high traffic loads. Scaling typically involves vertical scaling (upgrading hardware) or sharding (partitioning data across multiple instances).
NoSQL: NoSQL databases are designed to scale horizontally with ease. They are well-suited for distributed environments and can handle large-scale data and high traffic by adding more servers to the cluster.
Query Language:

MySQL: MySQL uses SQL (Structured Query Language) to query and manipulate data. SQL provides a standardized and powerful language for relational databases.
NoSQL: NoSQL databases may have their own query languages or use APIs for data retrieval and manipulation. The query languages are often designed to be more flexible and tailored to the specific data model.
ACID Compliance:

MySQL: MySQL databases adhere to ACID (Atomicity, Consistency, Isolation, Durability) properties, ensuring data integrity and reliability. Transactions are supported, allowing for consistent and reliable data operations.
NoSQL: NoSQL databases may sacrifice some ACID properties for better performance and scalability. They often prioritize availability and partition tolerance (CAP theorem) over strict consistency.
Use Cases:

MySQL: MySQL is commonly used in applications that require strong data consistency, complex joins, and structured data. It is well-suited for traditional relational data models and complex queries.
NoSQL: NoSQL databases are often preferred for applications with rapidly evolving requirements, unstructured or semi-structured data, and high scalability needs. They excel in scenarios such as real-time analytics, content management systems, and distributed data storage.   

4)  MongoDB is a popular NoSQL database that follows a document-oriented data model. It stores data in flexible, JSON-like documents, allowing for dynamic schemas and easy scalability.  
MongoDB is designed to handle large volumes of unstructured or semi-structured data. Instead of using tables with rows and columns like traditional relational databases, MongoDB stores data in collections of documents. Each document is a self-contained unit that can have its own unique structure. These documents are typically represented using the JSON (JavaScript Object Notation) format, making it easy to work with data in various programming languages. One of the key features of MongoDB is its ability to scale horizontally. It supports automatic sharding, which means that as data grows, MongoDB can distribute it across multiple servers or clusters, allowing for high availability and performance. This makes MongoDB well-suited for handling large-scale applications with heavy read and write loads. MongoDB also provides powerful querying capabilities. It uses a flexible query language that supports various operators and expressions to retrieve, filter, and manipulate data. It also supports rich indexing features, allowing for efficient data retrieval based on specific fields or criteria. Additionally, MongoDB offers a range of advanced features such as replica sets for data redundancy and fault tolerance, as well as transactions to ensure data consistency in multi-document operations.Overall, MongoDB is a versatile and scalable DBMS technology that excels in scenarios where there is a need for flexibility in data structures, high scalability, and real-time data processing. It is widely used in modern web and mobile applications, content management systems, and big data analytics.
