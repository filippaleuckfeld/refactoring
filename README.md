# refactoring
|Refactoring|Effort|How often used|Outcome|
|-----------|------|--------------|-------|
|Rename field|low|often|more consistent naming, better readability|
|Generalize type|medium|moderately|Enables code-sharing, better maintainability because of less code| 
|Change static fields to singleton instance|high|rarely|makes code thread-safe; high effort due to having to rewrite much code to manage state and pass reference to given (singleton) object instance|
