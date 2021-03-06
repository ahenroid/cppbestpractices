# C++ Best Practices at Puppet Labs

**Table of Contents**

- [Getting Started Resources](01-Getting-Started.md#getting-started-resources)
  - [The C++ Language](01-Getting-Started.md#the-c-language)
    - [Study Guide](01-Getting-Started.md#study-guide)
    - [Language References](01-Getting-Started.md#language-references)
    - [Community](01-Getting-Started.md#community)
    - [Practitioner Knowledge](01-Getting-Started.md#practitioner-knowledge)
    - [Tooling](01-Getting-Started.md#tooling)
  - [Starting a Project](01-Getting-Started.md#starting-a-project)
    - [Libraries](01-Getting-Started.md#libraries)
    - [cpp-project-template](01-Getting-Started.md#cpp-project-template)
    - [Vanagon](01-Getting-Started.md#vanagon)
    - [Cross-platform development](01-Getting-Started.md#cross-platform-development)
- [Style Guide](02-Style-Guide.md#style-guide)
  - [Header Files](02-Style-Guide.md#header-files)
  - [Namespaces](02-Style-Guide.md#namespaces)
  - [Exceptions vs Error-Handling](02-Style-Guide.md#exceptions-vs-error-handling)
  - [TODO: Still under development.](02-Style-Guide.md#todo-still-under-development)
- [FAQ](03-FAQ.md#faq)
  - [Q: Writing loops](03-FAQ.md#q-writing-loops)
  - [Q: Variable modifiers](03-FAQ.md#q-variable-modifiers)
  - [Q: Arguments and return types in class methods](03-FAQ.md#q-arguments-and-return-types-in-class-methods)
  - [Q: How do I use polymorphic objects?](03-FAQ.md#q-how-do-i-use-polymorphic-objects)
  - [Q: How do I share ownership of an object between multiple classes/data structures?](03-FAQ.md#q-how-do-i-share-ownership-of-an-object-between-multiple-classesdata-structures)
  - [Q: When does it make sense to use new/delete?](03-FAQ.md#q-when-does-it-make-sense-to-use-newdelete)
- [Rants](04-Rants.md#rants)
  - [Potential Tools](04-Rants.md#potential-tools)
    - [Dynamic Analysis](04-Rants.md#dynamic-analysis)
    - [STL debug support in GDB](04-Rants.md#stl-debug-support-in-gdb)
    - [cling](04-Rants.md#cling---an-interactive-c-interpreter)
  - [Libraries](04-Rants.md#libraries)
    - [Selection Criteria](04-Rants.md#selection-criteria)
    - [Using libraries in a project](04-Rants.md#using-libraries-in-a-project)
    - [Interesting Candidates](04-Rants.md#interesting-candidates)

## Maintenance

Maintainers: Michael Smith <michael.smith@puppet.com>

Tickets: Can be opened in Github Issues.
