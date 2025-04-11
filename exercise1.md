When working on a C# application with a small team, setting up continuous integration (CI) is important to maintain code quality and ensure smooth delivery.

In the .NET ecosystem, common CI steps like linting, testing, and building are supported by robust tools. For linting, tools such as StyleCop Analyzers or Roslyn Analyzers help ensure coding standards and catch issues early.  For testing, popular frameworks include xUnit, NUnit, and MSTest, all of which integrate well with .NET test. The build process can be handled through dotnet build or MSBuild both of which are standard in .NET development.

In addition to Jenkins and GitHub Actions, there are other CI services to consider, such as Azure DevOps Pipelines, GitLab CI/CD, TeamCity, and CircleCI. Azure DevOps is especially well-suited for .NET projects due to its integration with the Microsoft stack.

Choosing between a cloud-based or self-hosted CI setup depends on several factors. Cloud-based CI is usually preferred for small teams as it requires less maintenance, scales easily, and provides quick setup. Self-hosted CI might be better for teams with strict security or compliance needs, or when more control over the environment is required.

To make the right decision, one should consider factors, including, budget, infrastructure expertise, integration needs, data security policies and how often builds and tests will run. For many small teams, a cloud-based CI setup offers the best balance between convenience and performance.