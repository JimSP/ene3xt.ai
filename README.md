
# ene3xt.ai :: java code agent

**Generate complete Java projects from natural language descriptions and customizable templates.**  
GenHex combines **code generation powered by AI** and **template-based architecture with Freemarker**, enabling rapid development aligned with **Clean Code, DDD, and Hexagonal Architecture**.

---

## Overview

GenHex is designed for developers who want to bootstrap robust Java projects quickly, while keeping full control over structure and business logic. With GenHex, you can:

- Describe entities and business rules in **natural language**
- Use **custom Freemarker templates** to generate your code
- Build projects following industry best practices (SOLID, DDD, Clean Architecture)
- Test the tool visually via the frontend: [https://www.ene3xt.ai](https://www.ene3xt.ai)

---

## Features

- **Full Project Generation**
  - JPA Entities
  - DTOs with validations
  - Immutable Domain Models
  - Converters (DTO-Domain-JPA)
  - RESTful Controllers
  - Ports & Adapters (Hexagonal Architecture)
  - Services and Repositories
  - Unit and Integration Tests
  - Auto-generated `pom.xml`

- **Custom Template Support**
  - Upload and use your own `.ftl` Freemarker templates
  - Define output structure and file paths
  - Framework-agnostic: generate for any tech stack

- **AI-Generated Business Logic**
  - Natural language rules turned into method bodies
  - Example: “apply 10% discount if price > 100”
  - Code is generated respecting clean coding standards

- **Total Flexibility**
  - JSON-based configuration for full control
  - Customize packages, class names, attributes
  - Easy to reuse and version templates and descriptors

---

## How It Works

1. **Create a descriptor JSON** with your entities, domain models, DTOs, JPA mappings, and rules.
2. **Bind your templates** using the standard schema.
3. **Send the JSON to the REST API** or use the frontend.
4. **GenHex will generate a complete, working codebase** ready to compile and run.

---

## Live Demo (Frontend)

Try it directly on your browser:  
[https://www.ene3xt.ai](https://www.ene3xt.ai)

## Open API (Backend)
[https://api.ene3xt.ai:8443/swagger-ui/index.html](http://api.ene3xt.ai:8443/swagger-ui/index.html)
---


