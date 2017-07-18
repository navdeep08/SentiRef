# SentiRef

SentiRef is a dataset of identified Emotional Scores in Refactoring Commit Messages of GitHub projects. SentiRef consists of 3,170 commit messages with 26,410 instances of following Refactoring Activities:

    1. Extract Method
    2. Extract Interface
    3. Extract Superclass
    4. Rename Method
    5. Rename Class
    6. Inline Method
    7. Push Down Attribute
    8. Push Down Method
    9. Pull Up Attribute
    10. Pull Up Method
    11. Extract And Move Method
    12. Move Attribute
    13. Move Method
    14. Move Class
    15. Move Class Folder

Building SentiRef
--- 
The process of buliding SentiStrength involves following steps:
1. Apply RefTypeExtractor to input projects
2. Apply SentiStrength to identify emotions in each Refactoring activity.

Evolve SentiRef
---
Researchers can contribute to SentiRef by considering different projects and analyze emotions in a broad range of refactoring activities. 
