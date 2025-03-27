# ene3xt.ai :: Java Code Agent

**Generate complete Java projects from natural language descriptions and customizable templates.**  
GenHex combines **AI-powered code generation** with a **template-driven architecture (Freemarker)**, enabling rapid development aligned with **Clean Code, DDD, and Hexagonal Architecture**.

---

## Overview

GenHex is built for developers who want to bootstrap robust Java projects in seconds — while keeping full control over structure and business logic. With GenHex, you can:

- Describe entities and business rules using **natural language**
- Use **custom Freemarker templates** to generate your code
- Follow best practices: **SOLID**, **DDD**, and **Hexagonal Architecture**
- Explore visually through the frontend: [https://www.ene3xt.ai](https://www.ene3xt.ai)

---

## Features

- ✅ **Full Project Generation**
  - JPA Entities
  - DTOs with validations
  - Immutable Domain Models
  - Converters (DTO ⇆ Domain ⇆ JPA)
  - RESTful Controllers
  - Hexagonal Architecture (Ports & Adapters)
  - Service and Repository Layers
  - Unit and Integration Tests
  - Auto-generated `pom.xml` (Java 17 & Spring Boot)

- 🔁 **Custom Template Support**
  - Upload and use your own `.ftl` Freemarker templates
  - Fully control the folder structure and output paths
  - Framework-agnostic: adapt to any stack or architecture

- 🤖 **AI-Generated Business Logic**
  - Define custom rules using natural language
  - Example: _“apply 10% discount if price > 100”_
  - LLM-generated logic inserted directly into your code

- ⚙️ **Flexible Descriptor System**
  - JSON-based configuration with fine-grained control
  - Customize package names, class structure, validations, and more
  - Reusable and versionable descriptors and templates

---

## How It Works

1. **Create a descriptor JSON** with your entities, DTOs, JPA definitions, and business rules.
2. **Map the templates** to be used via schema configuration.
3. **Send the JSON** to the REST API or use the visual frontend.
4. **Download the result** – a complete `.zip` project, ready to compile and run.

---

## Live Demo (Frontend)

Try the visual interface on your browser:  
🌐 **[https://www.ene3xt.ai](https://www.ene3xt.ai)**

---

## Open API (Backend)

Access the OpenAPI (Swagger UI) documentation for direct API integration:  
🔗 **[http://api.ene3xt.ai:8443/swagger-ui/index.html](http://api.ene3xt.ai:8443/swagger-ui/index.html)**

The backend supports standard POST operations where you can submit your JSON descriptor and receive a `.zip` file containing the generated project.

---

## Roadmap

- [x] Core code generation engine
- [x] AI-assisted business rule logic
- [x] Custom template support (Freemarker)
- [x] Frontend for visual interaction
- [ ] VSCode extension
- [ ] Template marketplace
- [ ] GitHub Actions integration
- [ ] CLI & Local runner

---

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## Author

Developed by **Alexandre M S Lima**  
Let’s build better tools for developers. Feedback, ideas or questions?  
📬 Reach out via [https://www.ene3xt.ai](https://www.ene3xt.ai)

---

## Tags

`Java` `Spring Boot` `Hexagonal Architecture` `Code Generation` `LLM` `AI` `Freemarker` `Clean Code` `Open Source` `Dev Tools`
