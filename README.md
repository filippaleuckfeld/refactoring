# refactoring
|Refactoring                               |Effort|How often used|Outcome                                         |Member(s)|
|------------------------------------------|------|--------------|------------------------------------------------|---------|
|Rename field/method                       |low   |often         |more consistent naming, better readability      |everyone |
|Extract method/function                   |medium|often         |better readabilty, prepare for future code reuse|David    |
|Move method/type                          |low   |often         |better readability, more modular code           |David    |
|Componentization                          |high  |often         |separate code units with clear interfaces       |Håvard   |
|Remove Duplicated Code					   |medium|sometimes     |reduced code redundancy, improved maintainability, codebase will be easier to modify and update. | Filippa |
|Generalize type                           |medium|moderately    |enables code-sharing, better maintainability because of less code| Alexander|
|...                                       |...   |...           |...                                             |...      |
|Change static fields to singleton instance|high  |rarely        |makes code thread-safe; high effort due to having to rewrite much code to manage state and pass reference to given (singleton) object instance|no one(?)|
