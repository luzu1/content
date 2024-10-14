---
Title: "How to Create UML Class Diagrams?"
Subtitle: "Learn how to create UML class diagrams. Discover how to visually and effectively represent the structure of your programs. Master the technique now!"
Tags: ["uml", "class-diagram"]
Authors: ["DF27ARTS"]

---

## How to Create a UML Class Diagram?

A class diagram is one of the most important tools in the UML (Unified Modeling Language) used to visualize classes and their relationships in an OOP (Object-Oriented Programming) system. A class diagram shows the system's classes, their attributes, methods, and relationships like inheritance and association. In this article, we’ll go through step-by-step examples of how to create a UML class diagram.

## Step-by-Step Guide to Creating a UML Class Diagram

We’ll create a class diagram step by step. There are many platforms online to help you create class or other types of diagrams. For this example, we’ll use the free website [draw.io](https://app.diagrams.net) one of the most popular tools for creating UML diagrams. If you enjoy working with VS Code, the [draw.io](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio) for VS Code allows you to create UML diagrams directly within your development environment.

### 1. Create a UML Diagram File

The following video will help you understand how to create a new file in draw.io and save it to your [google drive](https://drive.google.com).

<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/XmSUk7qeXdg" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen
></iframe>

If you don’t see **diagrams.net** in your Google Drive's "New" section, it means the application is not yet integrated with your Drive account. To integrate **draw.io** with your Drive, follow these steps: 

1. Click the `+ Nuevo`, and a tab will open where you can choose the file type to create.
2. In this tab, click the **Plus** button to open another tab with more options.
3. In this new tab, click **Connect more apps**, which will open a small page where you can download and add more apps to your Drive account.
4. On this page, type (draw.io) in the search bar. When the app appears, click on it to see more details and press **Install**. Once installed, you can access it from your Google Drive.

### 2.  Identify the Necessary Classes
The second step in creating a UML class diagram is identifying the classes you'll need for your project. A class is an abstract representation of an object that has specific attributes and behaviors. For our example, we'll model the necessary classes for a book-selling application, essentially a library.

The main classes for this application are:

1. **Library**: The library class will be the main class of the application, containing all the books.
2. **Book**: The book class represents a book and all its features, aggregated into the library class.
3. **Person**: This class will serve as an abstract class to represent common attributes shared between the Seller and Customer classes.
4. **Seller**: The seller class will be a subclass of the person class but with more specific attributes to represent a seller.
5. **Customer**: The customer class will also be a subclass of the person class, but we'll add some new features to better represent a customer.

### 3. Define the Attributes and Methods

The third step is to define the attributes and methods for each class. Below, we'll define these attributes for all the classes in our application.

![https://res.cloudinary.com/dleo66u17/image/upload/v1691009711/Captura_de_pantalla_2023-08-02_155300_nhlqka.png](https://res.cloudinary.com/dleo66u17/image/upload/v1691009711/Captura_de_pantalla_2023-08-02_155300_nhlqka.png)

 As you can see in this example, we must define each class along with its attributes and methods. The text above the central line are the attributes, and the text below it are the methods. The basic structure of a class diagram is as follows:

-   To declare the attributes of our class, use the following symbols:
    - (+) Public: Represents that the attribute or method can be accessed from anywhere in the application.
    - (-) Private: Represents that the attribute or method can only be accessed within the same class.
    - (#) Protected: Represents that the attribute or method can only be accessed within the same class or by its child classes (subclasses).
- Attributes are declared with the following syntax:
```
+ attributeName: dataType
```
- Methods of the class are declared like this:
```
+ methodName(parameterName: dataType): returnType
```

This is the conventional structure for creating a class diagram, but it's important to note that there is no exact structure, as this depends on each project. Also, note that the colors used for the classes are not strictly conventional; they are simply used to differentiate between different types of classes, but you can use any colors you want or none at all.

### 4. Establish Relationships

The fourth and final step in creating a class diagram is to establish the relationships between the classes, as shown in the example below:

![https://res.cloudinary.com/dleo66u17/image/upload/v1691172317/Captura_web_4-8-2023_13135_app.diagrams.net_kmisyp.jpg](https://res.cloudinary.com/dleo66u17/image/upload/v1691172317/Captura_web_4-8-2023_13135_app.diagrams.net_kmisyp.jpg)

In this example, the abstract **Person** class is related to its child classes or subclasses, **Seller** and **Customer**, using a solid line with a triangular arrow. The main **Library** class is related to the other classes it contains, **Book**, **Seller**777, and **Customer**, using a solid line with a diamond arrow and a black background.

> It's important to highlight that when designing the UML diagram for your application, it won't be static. As you start generating the code and want to add more attributes or classes that you didn't initially consider, you can do so. Just keep in mind that the UML diagram should represent all the attributes, methods, and interactions of your application as accurately as possible.

## Applications to Create UML Class Diagrams

There are several applications or websites you can use to create UML class diagrams or any other types of diagrams. Many of them allow access to **Google Drive** to save files. It is recommended to save your designs in cloud storage like Google Drive, GitHub, etc., so they are more secure. Below are the three most commonly used applications for designing diagrams of any kind:

1. **Draw.io**:  [draw.io](https://app.diagrams.net) is a free, open-source tool that offers a wide range of templates, including UML class diagrams or any other type, such as object diagrams or database diagrams. It allows you to save files in various locations such as Google Drive, GitHub, or your local storage.
2. **Visual Paradigm**: [visual paradigm](https://www.visual-paradigm.com)  is a comprehensive UML modeling application with an intuitive graphical interface that allows you to create class diagrams as well as other types of 
3. **Lucidchart**: [lucidchart](https://www.lucidchart.com/pages/es) allows users to create UML diagrams easily and quickly. It’s a good option for small or large teams and offers a wide range of features.

## Conclusion

UML class diagrams are an essential tool for modeling object-oriented systems. Declaring them correctly and using the right tools depending on the type of project allows us to visualize the structure of our system more effectively, contributing to a more efficient and successful software development process. You’ll find more valuable information on the [4Geeks](https://4geeks.com/es).
