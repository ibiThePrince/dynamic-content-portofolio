## Branching stategy
  *There's our branching strategy*
  **This list may be not up to date.**

- **basic**
    Branch prefixe to the family of the basic form of the project. reffers to '[Project's forms section](SPEC.md#project-forms)'.
- **complete**
    Branch prefixed to family of the complete form of the project. reffers to '[Project's forms section](SPEC.md#project-forms)'.

1. **basic/main:** 
    is the most recent and functionnal basic forms of the project
2. **basic/develop:**
    The development branch where features under development are merged. This is where new features are integrated and tested before being merged into the basic/main branch.
3. **basic/feature/{feature-name}:** 
    Branches for developing specific features for the basic. Each feature can be developed in a separate branch, then merged into the development branch once completed.
4. **basic/bugfix/{bug-name}:** 
    Branches for fixing specific bugs. Each bug fix can be developed in a separate branch and then merged into the development branch once fixed.
5. **basic/documentation:**
     A branch dedicated to the project documentation. Documentation updates can be made here before being merged into the main branch.

This is to explain Explains the branching strategy for managing different functional forms of the project.