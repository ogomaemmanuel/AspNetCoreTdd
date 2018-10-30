Unit test frameworks help us write test in  a simplier , faster and easier way, they have GUI component, to show wether test have passed or failed, they are also accessible through plugins on IDE

In visual studio, are available through test explorer, test menu-&gt;windows-&gt;test explorer

**Available Testing Frameworks ASP Net Core**

* MSTest
* xUnit
* Nunit

**MsTest**

This is a microsoft Unit test framework and Is availabel through visual studio insatlation

Uses attribute \[TestClass\] to mark test classes

Uses attribute\[TestMethod\] to mark test methods

Uses atttribute\[TestInitialize\] to mark methods for test initilisation

Uses attribute \[TestCleanUp\] to mark methods for test test clean up

**Nunit**

It is the most popular unit  test framework

It is powerful, stand alone and fast

Uses the attribute \[TestFixture\] to mark classes as test classes

Uses attribute \[Test\] to mark methods as Test

\[TestCase\] is used to make one method run like multiple test

```
[TestCase(12,3, Result=4)]
[TestCase(12,2, Result=6)]
[TestCase(12,4, Result=3)]
public int DivideTest(int n, int d)
{
 return( n / d );
 }
```

It is well documented [link](http://nunit.org)

xUnit

It is focused on flexibility and extensibilty

It has no attributte to mark class as test calsses, this means test can be written anywhere in any class

Initilization of test is done through the constructor of the class and clearing up in the dispose method

It use attribute\[Fact\] to mark test methods

