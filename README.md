# CML-StrategicDesign-Addon
An adapted CML-Version which extends the existing grammar with missing strategic design patterns.

# What's CML
The Context Mapper Language (CML) is a textual domain-specific language (DSL) for modeling Domain-Driven Design systems. It captures strategic and tactical concepts and supports model-driven analysis and rapid prototyping via the Context Mapper toolchain. This repository builds on the existing CML-project (https://github.com/ContextMapper/context-mapper-dsl) createy by Stefan Kapferer and introduces additional strategic design constructs

# What’s new in this project
Context-map additions:
- Separate Ways relationship.
- Big Ball of Mud annotation.
  
Distillation pattern additions:
- Highlighted Core
- Segregated Core
- Abstract Core
- Cohesive Mechansims

# Why
Strategic decisions are often tacit. These extensions encode some of them directly in the model to improve transparency, comprehension, and evolution across teams.
The inclusion of the new strategic DDD-patterns is optional (and accordingly implemented in the code).

# License
Apache-2.0 (aligned with the originial CML)
