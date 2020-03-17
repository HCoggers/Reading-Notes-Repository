### Week 1, Tuesday  

1. Unit Test
    - A *unit test* is a test that runs on a single method in a program. They are used to make sure every individual aspect of a program works as intended.
    - Tests should be run from a __Separate__ file from the program they are testing, and given a reference to that original file
    - Visual Studio has a *Unit Test Program* to streamline this process, so you don't have to run a brand new console app for each test
2. Assert
    - *Assert* is a class in VS unit testing that provides methods such as `Assert.AreEqual()`, which tests if two values are equal.
3. xUnit
    - *xUnit* is a multi-platform unit testing tool for .Net
    - Using a class-library, you can reference xUnit in your unit tests
4. Fact
    - A unique convention in xUnit is Facts and Theories. *Facts* are tests which you always want to pass. 
    - If a Fact fails, it could mean the test itself is flawed. The conditions for Facts shouldn't change.
5. Theory
    - *Theories* are tests that depend mainly on the data being fed to them.
    - If a theory fails, it doesn't mean necessarily that the test is flawed, just that the variable data given to it didn't pass.
