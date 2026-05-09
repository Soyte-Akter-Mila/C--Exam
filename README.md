# Product Inventory LINQ Console App

A straightforward C# console application that demonstrates how to use LINQ (Language Integrated Query) to perform complex multi-table joins on in-memory collections. 

This project simulates a basic relational database structure for a bicycle and cycling equipment store, connecting products to their respective models and categories.

## 📌 Features
* **In-Memory Data Seeding:** Initializes comprehensive collections of `Product`, `ProductCategory`, and `ProductModel` objects.
* **Relational Data Mapping:** Uses ID properties (`ProductCategoryID`, `ProductModelID`) to link separate entity classes together.
* **Multi-Collection LINQ Joins:** Demonstrates how to join three separate lists into a single anonymous type.
* **Console Output:** Iterates through the queried results and outputs formatted strings to the console window.

## 📁 Code Structure

* `Program.cs`: The main entry point of the application. Contains the seeded arrays and the core LINQ join query.
* `Product.cs`: The entity class defining a product's properties (ID, Name, Number, Color, Cost, Price, Size, Weight, CategoryID, ModelID).
* `ProductCategory.cs`: The entity class defining product categories (e.g., Bikes, Components, Clothing).
* `ProductModel.cs`: The entity class defining specific product models (e.g., Mountain-100, HL Road Frame).

## 🚀 How to Run

1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/yourusername/your-repo-name.git)
