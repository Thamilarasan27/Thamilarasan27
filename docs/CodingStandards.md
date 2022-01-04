# Backend Coding Standards

## Package Management
Packages in Spring Boot project is created based on the layers.
<li> Models </li>
<li> Repositories </li>
<li> Services </li>
<li> Controllers </li>

### Models
The package `com.zenitus.toto.Models` should contain all the Model classes. 
<li> The class name must be same as the table name in database. </li>
<li> If the table name or column name follows snake casing (eg. snake_casing), the name of the java class and identifiers must follow pascal casing (eg. PascalCasing). </li>
<li> All identifiers must be private. </li>

### Repositories
The package `com.zenitus.toto.Repositories` should contain all the Repository interfaces.

### Services
The package `com.zenitus.toto.Services` should contain all the Service classes.

### Controllers
The package `com.zenitus.toto.Controllers` should contain all the Controller classes.
<li> The Controllers must be Rest Controllers. </li>
<li>
  The base API should follow the following format, <code>/api/entity_name</code>
</li>

## Common
<li> All the class name must start in capital letter. </li>
<li> Objects of other layers must be private. </li>

---
