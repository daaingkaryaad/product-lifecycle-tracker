# Technology Comparison and Preliminary Selection

## 5. Technology Comparison

### (1) Backend Framework

| Criterion | Fastapi | Django + DRF |
|---|---|---|
| **Suitability** | Lightweight, API-focused framework. | Full-featured framework for data-driven applications. |
| **Authentication and database** | Requires additional setup for authentication and database management. | Provides built-in authentication, ORM, and migrations. |
| **Development complexity** | Flexible, but requires more manual configuration. | More built-in tools, but additional framework complexity. |

### (2) Database

| Criterion | PostgreSQL | MongoDB |
|---|---|---|
| **Data structure** | Relational tables with defined relationships. | Flexible document-based structure. |
| **Data integrity** | Foreign keys, constraints, and ACID transactions. | Schema validation and ACID transactions, with relationships handled differently. |
| **Suitability** | Well suited for interconnected products, users, and lifecycle events. | Suitable for flexible product attributes and document-based storage. |

### (3) Component Interaction

| Criterion | Rest API | GraphQL |
|---|---|---|
| **Data retrieval** | Predefined endpoints and response structures. | Clients request specific fields through queries. |
| **Development complexity** | Simpler to implement and maintain. | Requires schemas and resolvers. |
| **Suitability** | Sufficient for registration, history, search, and reporting. | Useful for complex and flexible data queries. |

## 5.4. Preliminary Technology Selection

The proposed platform will use React for the frontend and Python for the backend. The backend framework remains under consideration between FastAPI and Django + DRF. 

PostgreSQL is preferred for its relational structure and data integrity; REST API is preferred for its simplicity and suitability for the planned functionality. 

These choices are preliminary and may be refined after user research and requirements analysis.