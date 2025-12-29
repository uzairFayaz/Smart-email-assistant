
---

## Features

- AI-powered email reply generation
- Optional tone control (professional, polite, friendly, etc.)
- RESTful API
- Spring WebClient for external API calls
- Jackson for JSON parsing
- CORS enabled for frontend integration

---

## Tech Stack

- Java
- Spring Boot
- Spring WebFlux (WebClient)
- Lombok
- Jackson
- Gemini Generative AI API

---

## Configuration

Add the following to `application.properties`:

```properties
gemini.api.url=https://generativelanguage.googleapis.com/v1beta/models/gemini-pro:generateContent?key=
gemini.api.key=YOUR_GEMINI_API_KEY
