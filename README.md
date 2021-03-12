# test-fest-2021
A repository for the refactoring legacy code live coding session at TestFest 2021

## Refactoring Legacy Tests
Test code is an important artifact and as such should be treated like an applications code. This is especially true in a CI (Continous Integration) / CD (Continous Deployment) environment because these environments rely on the feedback from automated tests for the lifetime of the application. This means unmaintainable, unscalable test code impacts the application as much as the production code.

Sometimes there might be a need for you to refactor existing tests where you’ve not been involved in the creation or maintenance of these and so your understanding of their implementation and/or original intention might be quite minimal. So where should you start? How can you begin to make the code cleaner, easier to maintain, and read by applying principles like DRY (Don’t Repeat Yourself) and KISS (Keep It Simple, Stupid)?

During this session we will be looking at an existing UI test suite, identifying what needs to be changed and why refactoring one test at a time.

### About
This refactoring tests challenge was taken from the [Ministry of Testing ui-automation-Week](https://github.com/ministryoftesting/ui-automation-week/tree/main/dotnet/MoTAutomationWeekDotNet/Challenge_2)
