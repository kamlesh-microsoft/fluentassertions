**Before you file a bug, have you:**

* Tried upgrading to newest version of Fluent Assertions, to see if your issue has already been resolved and released?
* Checked existing open *and* closed [issues](https://github.com/fluentassertions/fluentassertions/issues?utf8=%E2%9C%93&q=is%3Aissue), to see if the issue has already been reported?
* Tried reproducing your problem in a new isolated project?
* Read the [documentation](https://fluentassertions.com/introduction)?
* Considered if this is a general question and not a bug?. For general questions please use [StackOverflow](https://stackoverflow.com/questions/tagged/fluent-assertions?mixed=1).

### Description

[Description of the issue]

### Complete minimal example reproducing the issue

Complete means the code snippet can be copied into a unit test method in a fresh C# project and run.
Minimal means it is stripped from code not related to reproducing the issue.

E.g.

```csharp
// Arrange
string input = "MyString";

// Act
char result = input[0];

// Assert
result.Should().Be('M');
```

### Expected behavior:

[What you expect to happen]

### Actual behavior:

[What actually happens]

### Versions

* Which version of Fluent Assertions are you using?
* Which .NET runtime and version are you targeting? E.g. .NET framework 4.6.1 or .NET Core 2.1.

### Additional Information

Any additional information, configuration or data that might be necessary to reproduce the issue.
