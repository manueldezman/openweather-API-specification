# OpenWeather API — OpenAPI Specification (Hackmamba Sprint Week 4)

This project is my Week 4 submission for the Hackmamba API Documentation Sprint. Week 4 focuses on creating an OpenAPI specification from scratch using visual editors and YAML, following the industry standard for API documentation.

## Live Link

https://manueldezman.github.io/openweather-API-specification/

## What I Documented

**Public API:** OpenWeather API  
**Endpoints Documented:** Multiple endpoints from the OpenWeather API service  
**Purpose:** Complete OpenAPI specification for weather data retrieval and forecasting

## How This Matches Week 4 Requirements

### OpenAPI Specification Components

- **API Overview**
  - Clear title, description, and version information
  - Contact and license information
  - Base server URL and endpoint structure

- **Endpoint Documentation**
  - HTTP methods (GET, POST, etc.) clearly defined
  - Complete endpoint paths with parameters
  - Operation IDs and tags for organization

- **Parameters**
  - Query parameters documented in detail
  - Path parameters with descriptions
  - Request body schemas where applicable
  - Each parameter includes: name, type, required/optional status, and description

- **Request Examples**
  - Sample curl requests for each endpoint
  - Real-world usage scenarios
  - Parameter value examples

- **Response Examples & Schema**
  - Complete JSON response samples
  - Detailed response schemas
  - HTTP status codes (200, 400, 404, etc.)
  - Error response definitions

- **Interactive Documentation**
  - Swagger UI integration for live API testing
  - Try-it-out functionality for exploring endpoints
  - Beautiful, user-friendly interface

## Key Features

✅ Valid OpenAPI 3.0 specification  
✅ Stoplight visual editor integration  
✅ Swagger UI for interactive documentation  
✅ Multiple endpoint coverage  
✅ Complete parameter and response documentation  
✅ Production-ready API reference  

## Technologies Used

- **OpenAPI 3.0** specification format
- **Stoplight** for visual specification editing
- **Swagger UI** for interactive documentation rendering
- **Jekyll** for GitHub Pages deployment
- **YAML** for specification definition

## How to Use

1. Visit the [live link](https://manueldezman.github.io/openweather-API-specification/) to explore the interactive documentation
2. Use Swagger UI to test API endpoints directly
3. Review the OpenAPI specification in `openweathermap.yaml` for technical details

## Project Structure

```
openweather-API-specification/
├── dist/                          # Built documentation files
│   ├── index.html                # Main Swagger UI page
│   ├── swagger-ui.js             # Swagger UI JavaScript
│   ├── swagger-ui.css            # Swagger UI styles
│   └── ...                       # Additional UI assets
├── openweathermap.yaml           # OpenAPI specification
├── _config.yml                   # Jekyll configuration
└── README.md                     # This file
```

## Learning Outcomes

Through this project, I gained understanding of:

- OpenAPI specification structure and best practices
- Visual API specification tools (Stoplight)
- Interactive documentation generation with Swagger UI
- Industry-standard API documentation patterns
- YAML syntax and schema definitions
- Proper endpoint organization and documentation

## Next Steps

Week 5 will continue building on these foundations to create even more comprehensive API documentation.

---

**Sprint:** Hackmamba API Documentation Sprint  
**Week:** 4 - OpenAPI Specification  
**Submission Date:** June 2026
