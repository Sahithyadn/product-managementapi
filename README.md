 Product API - Spring Boot with MongoDB
This is a Spring Boot REST API for managing products using MongoDB as the database.

🔗 Live API: Product API
🎥 Demo Video: Watch Here
🌐 GitHub Repository: Product API GitHub

📌 Features
🗄️ Uses MongoDB as the database
🌐 RESTful API for CRUD operations on products
🔥 Built with Spring Boot
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yashdongre12/product.git
cd product
2️⃣ Configure MongoDB in application.properties
Update your MongoDB credentials in src/main/resources/application.properties:

spring.data.mongodb.host=bytexldb.com
spring.data.mongodb.port=5050
spring.data.mongodb.database=db_43asngdub
spring.data.mongodb.username=user_43asngdub
spring.data.mongodb.password=p43asngdub
spring.data.mongodb.authentication-database=admin
3️⃣ Run the Application
mvn spring-boot:run
🛠️ API Endpoints
Method	Endpoint	Description
GET	/api/products	Get all products
GET	/api/products/{id}	Get product by ID
POST	/api/products	Add a new product
PUT	/api/products/{id}	Update a product by ID
DELETE	/api/products/{id}	Delete a product by ID
📜 Product Model
{
  "id": "string",
  "name": "string",
  "price": "number"
}
💡 Contributing
Feel free to contribute by submitting issues or pull requests.

image 
![image](https://github.com/user-attachments/assets/9906f905-9ba4-4083-a797-b94ead75cda7)
![image](https://github.com/user-attachments/assets/843c941f-7dee-444a-8a8c-5393866fe2e2)
