# refactoring
|Refactoring                               |Effort|How often used|Outcome                                         |Member(s)|
|------------------------------------------|------|--------------|------------------------------------------------|---------|
|Rename field/method                       |low   |often         |more consistent naming, better readability      |everyone |
|Extract method/function                   |meduim|often         |better readabilty, prepare for future code reuse|David    |
|Move method/type                          |low   |often         |better readability, more modular code           |David    |
|Componentization                          |medium|often         |separate code units with clear interfaces       |Håvard   |
|...                                       |...   |...           |...                                             |...      |
|Change static fields to singleton instance|high  |rarely        |makes code thread-safe; high effort due to having to rewrite much code to manage state and pass reference to given (singleton) object instance|no one(?)|
