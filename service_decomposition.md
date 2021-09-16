## Service Decomposition

### Reasons to de-compose a monolith into services

* To preserve stability for a core API from a higher churn rate area
  * Higher rate of growth of area can iterate independently from core and faults are isolated
  * This requires separate infrastructure, team, resources etc. to be weighed against the benefits
