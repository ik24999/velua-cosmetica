# Common Patterns

## Skeleton Projects

When implementing new functionality:
1. Search for battle-tested skeleton projects
2. Use parallel agents to evaluate options (security, extensibility, relevance, implementation)
3. Clone best match as foundation
4. Iterate within proven structure

## Design Patterns

### Repository Pattern
Encapsulate data access behind a consistent interface:
- Standard operations: findAll, findById, create, update, delete
- Business logic depends on abstract interface, not storage mechanism
- Enables easy swapping of data sources and simplifies testing

### API Response Format
Consistent envelope for all API responses:
- success/status indicator
- data payload (nullable on error)
- error message field (nullable on success)
- metadata for paginated responses (total, page, limit)
