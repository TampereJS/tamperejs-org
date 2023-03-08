# Modules

TampereJS is split into smaller modules with clearly defined interfaces and acceptance tests, so
that each module can be iterated individually and separately without affecting others.

Each module has it's own directory with README file and it should be understandable in 5 minutes or
less. Additionally, any other resources it might have should be stored in the module directory.

## The structure of an module

Each module should contain following parts:

### Description

Short description of the module

### Purpose

Short description of what is the purpose of the module, why it exists. This is used a guiding goal
for making decisions about the module

### Interfaces

Any interfaces the module exposes for others to use. Each interface should be separated with a
subtitle so that it can be linked directly to.

### Dependencies

Any interfaces other modules expose that this module depends on. Each dependency should be separated
with a subtitle so that it can be linked directly to.

### Tests

Any tests that should pass in order for a change to be accepted. Each test should be separated with
a subtitle so that it can be linked directly to.
