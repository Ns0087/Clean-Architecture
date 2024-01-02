# Clean-Architecture
Clean Architecture Design Pattern

Clean Architecture which is also known as Domain-Driven Design has evolved with considerable improvements in the last several years. Some architecture names used for clean architecture over the years are given below:

* Hexagonal Architecture (https://en.wikipedia.org/wiki/Hexagonal_architecture_(software))
* Onion Architecture
* Domain-Driven Design (DDD) or Domain Centric Architecture
* vertical Slice Architecture
* Clean Architecture

The above mentioned architectures have similar design principles that have the primary idea to keep the core business logic and application domain at the center of the solution structure. In this architecture, we make core application business logic and domain or entities independent of the presentation layer and data access layer.

Therefore, the whole idea of this architecture is to allow the core part, which consists of complete business logic and application entities, adaptive and flexible enough to deal with changing technology and interfaces. Additionally, the core application remains the same and independent of presentation layers, infrastructures, and databases.

This architecture saves huge time because the core application business logic and entity are independent of framework, presentations, databases, and external parts. Subsequently, the architecture is sustainable and is loosely coupled core business logic and entity with presentation layer or framework. 

## Basic Principles
The primary idea in Clean Architecture is to make the solution adaptive, keep the core business or application logic use cases independent of frontend and external frameworks. In summary, we can outline the following outcomes of clean architecture,

### 1. Independent of UI
Using clean architecture, we should be able to change UI or presentation layers easily without changing the application layer and so on. UI can be from any front-end framework, or console UI, any web, and can be replaced without changing the other layers or rest of the system.
### 2. Database Independent
The architecture should be flexible enough to swap the database without affecting the application use cases and entities. The solution can switch the dataset to MS SQL, MySQL, Oracle, MongoDB, or something else.
### 3. Independent of External agency/libraries/Drivers
The business rules should be independent of external parties or agencies.
### 4. Framework Independent
The core business or application rules should be independent of the existence of frameworks, libraries for the future. We can include the frameworks but as tools, and the solution should not be completely relied on those.
### 5. Testable
The architecture should comply with the testing of the core application and business cases and rules without the UI, database, Web server, or any external component.

## Clean Architecture Diagram

![alt text](https://www.c-sharpcorner.com/article/what-is-clean-architecture/Images/What%20is%20Clean%20Architecture1.png "Clean Architecture Diagram")
