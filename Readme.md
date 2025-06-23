# Run the Application:

- Open a terminal in the root directory of your project.

- Run the application using Maven: mvn spring-boot:run or Gradle: gradle bootRun

Open your web browser and go to http://localhost:8080/products.

You should see a web page displaying the list of products from the static ArrayList.

# This example demonstrates the basic flow:

- The ProductController handles the products request.

- It populates a List<Product> (our static data acting as the Model).

- It adds this list to the Spring Model object, making it accessible to the view.

- It returns the logical view name "products".

Thymeleaf resolves this to products.html and renders the data from the Model into the HTML table.

# Result

![image](https://github.com/user-attachments/assets/38722e04-d622-41af-9ea1-e68fa4d7d165)
