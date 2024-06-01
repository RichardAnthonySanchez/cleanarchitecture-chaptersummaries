# Component Cohesion

## Reuse/Release Equivalence Principle (REP)

Components that are reused together should be released together. This ensures updates are coherent across these pieces.

## Common Closure Principle (CCP)

Group things that change for the same reasons at the same times. This ensures components are maintainable and reflect the Single Responsibility Principle (SRP) at the component level.

## Common Reuse Principle (CRP)

Include classes/modules together only if they are frequently used together. This is similar to keeping all your specialized car tools together because when you use one, you're likely to use the others as well.

## Tension in Component Cohesion

Balancing these principles can be tricky because REP and CCP tend to make components larger, while CRP drives them to be smaller. Concerns change, so this balance is dynamic.

## Conclusion

When forming components, consider the balance between reusability and maintainability. Early in development, projects should optimize for maintainability. The opposite is true for mature projects. As priorities change, the balance of these three principles shifts.