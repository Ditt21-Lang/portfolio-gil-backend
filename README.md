# Portfolio CMS — Backend

Backend REST API for a personal portfolio website and Content Management System (CMS).

This repository handles application logic, content management, authentication, data persistence, and API communication with the frontend application.

## Tech Stack

- **Framework:** NestJS
- **Language:** TypeScript
- **Module System:** ES Modules (ESM)
- **Testing:** Vitest
- **Package Manager:** npm

## Project Structure

```text
src/
├── app.controller.ts
├── app.module.ts
├── app.service.ts
└── main.ts

test/                  # End-to-end tests
docs/
└── api/               # API documentation and OpenAPI specification
```

## Getting Started

### Prerequisites

- Node.js 22+
- npm

### Installation

Clone the repository:

```bash
git clone git@github.com:Ditt21-Lang/portfolio-gil-backend.git
cd portfolio-gil-backend
```

Install dependencies:

```bash
npm install
```

### Development

Start the development server:

```bash
npm run start:dev
```

The API will be available at:

```text
http://localhost:3000
```

## API Documentation

The project will use OpenAPI 3.1.0 as the official API contract between frontend and backend.

Planned documentation location:

```text
docs/api/openapi.yaml
```

## Related Repository

- [Portfolio CMS — Frontend](https://github.com/Ditt21-Lang/portfolio-gil-frontend)

## Development Guidelines

- Keep business logic organized into NestJS modules.
- Follow REST API conventions.
- Validate incoming requests on the backend.
- Keep API documentation synchronized with implementation.
- Write automated tests for application logic and API behavior.

## Project Status

Currently in initial backend setup.

Core API modules, database integration, authentication, and CMS functionality are planned for subsequent development.