# Modules

TampereJS is split into smaller modules with clearly defined interfaces and acceptance tests, so
that each module can be iterated individually and separately.

## Module structure

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
