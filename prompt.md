### **1. Spring Boot – CRUD REST API**

```markdown
You are an expert Java Spring Boot backend engineer.

Goal: Generate a REST API for managing a `Product` entity.
Context:
- Fields: id (Long), name (String), description (String), price (BigDecimal)
- Use Spring Web, Spring Data JPA and an in-memory H2 database.
- Follow layered architecture.

Task:
1. Create entity + repository + service + controller.
2. Implement full CRUD.
3. Add comments explaining each layer.

Act as a senior Spring Boot developer.

Goal: Create a versioned REST API endpoint `/api/v1/customers`.
- Fields: id, firstName, lastName, email.
- Support pagination + sorting.

Task:
- Build entity, repo, service, controller.
- Return paged response with metadata.
``
