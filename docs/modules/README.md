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

Any interfaces the module exposes for others to use

### Dependencies

Any interfaces other modules expose that this module depends on

### Tests

Any tests that should pass in order for a change to be accepted
