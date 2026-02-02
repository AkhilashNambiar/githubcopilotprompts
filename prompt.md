
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
````

***

### **2. Spring Boot – Versioned REST API with Pagination**

```markdown
Act as a senior Spring Boot developer.

Goal: Create a versioned REST API endpoint `/api/v1/customers`.
- Fields: id, firstName, lastName, email.
- Support pagination + sorting.

Task:
- Build entity, repo, service, controller.
- Return paged response with metadata.
```

***

### **3. .NET Web API – CRUD Controller**

```markdown
You are a .NET 8 Web API expert.

Goal: Generate a C# controller for managing `Order`.
- Use minimal APIs or controllers.
- CRUD with correct status codes.

Include:
- Order model.
- XML comments.
- In-memory repository.
```

***

### **4. Python FastAPI – Task Management API**

```markdown
Act as a Python FastAPI engineer.

Goal: Create a Task API with CRUD.
- Use Pydantic models.
- In-memory list for persistence.

Include:
- CRUD endpoints.
- Error handling.
- Response models.
```

***

## **2.2 Models + Data Access Layer (DAL)**

***

### **5. Spring Boot – Entity + Repository from Requirements**

```markdown
Goal: Implement a `UserAccount` entity + repository.
- Fields: id, username, email, passwordHash, createdAt, active.
- Add JPA + validation annotations.
- Repo methods: findByUsername, findByEmail, findByActiveTrue.
```

***

### **6. Spring Boot – Service Layer Logic**

```markdown
Goal: Create `UserAccountService`.
Rules:
- Username/email unique.
- Set createdAt + active=true for new accounts.

Include:
- Exception handling.
- JavaDoc documentation.
```

***

### **7. .NET – Repository Pattern for Products**

```markdown
Goal: Implement repository pattern.
- Product: Id, Name, Price, Stock.
- Use EF Core + DbContext.
- Async CRUD repository methods.
```

***

### **8. Python SQLAlchemy – Model + Repository**

```markdown
Goal: Create a SQLAlchemy ORM model and repository for `Customer`.
- Fields: id, name, email, created_at.
- Repo: add, get_by_id, get_all, delete.
- Use sessions safely.
```

***

## **2.3 Swagger JSON Integration**

***

### **9. Generate Spring Boot Controllers from Swagger JSON**

```markdown
Goal: Convert Swagger/OpenAPI JSON into controller stubs.

Task:
- Read OpenAPI.
- Generate controller skeletons for all paths.
- Add TODO markers for logic.
- Organize into multiple controllers.
```

***

### **10. Generate DTOs/Models from Swagger JSON**

```markdown
Goal: Auto-generate DTOs from OpenAPI schemas.
- Use Lombok.
- Add validation annotations.
- Add JavaDoc from schema descriptions.
```

***

## **2.4 Database Connectivity**

***

### **11. Spring Boot – MySQL Connectivity**

```markdown
Goal: Configure MySQL connection in application.yml
DB: localhost:3306/shopdb
User: shop_user
Pass: StrongPassword123

Include:
- Datasource properties
- Hibernate settings
- Comments explaining each
```

***

### **12. .NET – EF Core + SQL Server**

```markdown
Goal: Configure .NET Web API to connect to SQL Server.

Include:
- DbContext setup
- AddDbContext in Program.cs
- appsettings.json connection string
```

***

## **2.5 Unit Testing**

***

### **13. Spring Boot – JUnit + Mockito**

```markdown
Goal: Create unit tests for UserAccountService.

Test:
- createUser
- getUserById
- deactivateUser

Use:
- Mockito mocks
- Arrange–Act–Assert pattern
```

***

### **14. .NET – xUnit Tests**

```markdown
Goal: Write xUnit tests for OrdersController.
- Mock IOrderService with Moq.
- Test status codes + service interactions.
```

***

### **15. Python – Pytest + FastAPI TestClient**

```markdown
Goal: Write pytest tests for Task API.
- Test all CRUD.
- Include fixtures.
- Handle not found scenarios.
```

***

## **2.6 Hands-on Lab: Spring Boot CRUD**

***

### **16. Full Spring Boot CRUD Project**

```markdown
Goal: Build full Employee CRUD API.
- Entity + repo + service + controller
- H2 database
- Global exception handler
- README for instructions
```

***

### **17. Add Search Filters to CRUD API**

```markdown
Goal: Extend CRUD with search.
- Filter by role + partial lastName.
- Add new endpoints + examples.
```

***

### **18. Generate Swagger Documentation**

```markdown
Goal: Add Swagger/OpenAPI to Employee CRUD API.
- Add dependencies
- Add controller-level annotations
- Provide UI access instructions
```

***

### **19. Add Unit Tests**

```markdown
Goal: Add tests for:
- Repository (H2)
- Service (Mockito)
- Controller (@WebMvcTest)
```

***

### **20. Refactor to Clean Architecture**

```markdown
Goal: Restructure API into:
- domain
- infrastructure
- application
- api

Move logic out of controllers.
```

***

# **3. GitHub Copilot for Front-End Development (20 Prompts)**

***

## **3.1 HTML/CSS – Form Generation**

### **21. Semantic Contact Form**

```markdown
Goal: Create a semantic, accessible contact form.
- Fields: Name, Email, Subject, Message.
- Add client-side validation.
- Minimal CSS for spacing.
```

***

### **22. Multi-Step Registration Form**

```markdown
Goal: Generate HTML for a 3-step form.
Steps:
- Personal info
- Address
- Account info
Add IDs/classes for JS-driven navigation.
```

***

### **23. Accessible Login Form**

```markdown
Goal: Create a login form with error regions.
- ARIA live region support
- Inline error message containers
- Simple CSS
```

***

### **24. Signup Form with Required Indicators**

```markdown
Goal: Create signup form.
Required: Name, Email, Password
Optional: Phone, Company
Add visual required markers.
```

***

## **3.2 Bootstrap/Tailwind Layouts**

***

### **25. Bootstrap – Two-Column Layout**

```markdown
Goal: Build responsive 2-column layout with Bootstrap.
- Sidebar + content
- Navbar on top
- Mobile stacking
```

***

### **26. Bootstrap – Product Card Grid**

```markdown
Goal: Build responsive card grid.
Columns:
- XS: 1
- SM: 2
- LG: 4
Use placeholders.
```

***

### **27. Tailwind – Hero Section**

```markdown
Goal: Create responsive hero layout.
Left: text + button
Right: image
Use Tailwind gradient and spacing utilities.
```

***

### **28. Tailwind – Pricing Table**

```markdown
Goal: Build pricing table with 3 plans.
Highlight the “Pro” plan.
Stack on mobile.
```

***

## **3.3 React Components**

***

### **29. React – Controlled Login Form**

```markdown
Goal: Create React login form using useState.
- Controlled inputs
- Inline validation
- Error messages
```

***

### **30. React – Searchable List**

```markdown
Goal: Create filterable user list using hooks.
- Search box
- Filter user props
```

***

### **31. React – Reusable Modal**

```markdown
Goal: Build modal component with:
- isOpen
- onClose
- overlay click
```

***

### **32. React – Tabs Component**

```markdown
Goal: Build simple tabs.
Tabs: Profile, Settings, Security.
Use useState for active tab.
```

***

## **3.4 Hooks, Props, Event Handlers**

***

### **33. React – Custom Hook for Inputs**

```markdown
Goal: Implement custom hook useInput.
Fields: firstName, lastName, email.
Add validation + console output.
```

***

### **34. React – Button Variants**

```markdown
Goal: Reusable Button component.
Props: variant, onClick, children, disabled.
Variants: primary, secondary, danger.
```

***

### **35. React – Async Submit Form**

```markdown
Goal: Form with async API call simulation.
- Loading state
- Error message
- useState + async handler
```

***

### **36. React – Keyboard Accessible Card**

```markdown
Goal: Add keyboard handler on Enter/Space.
Use role + tabIndex for accessibility.
```

***

## **3.5 Hands-on Lab: Responsive Login Forms**

***

### **37. HTML/CSS/JS Login Form**

```markdown
Goal: Responsive login form with JS validation.
Rules:
- Valid email
- Password ≥ 8 chars
Show inline error messages.
```

***

### **38. React – Responsive Login Form**

```markdown
Goal: Login form with React hooks + validation.
- Disable submit if invalid
- Responsive CSS
```

***

### **39. Tailwind React – Login Card**

```markdown
Goal: Tailwind login UI.
- Card layout
- Red error state styling
- Fully responsive
```

***

### **40. Extend Login Form (Remember Me + Forgot Password)**

```markdown
Goal: Add Remember me + Forgot password features.
- Update state
- Align elements neatly
- Maintain accessibility
```

