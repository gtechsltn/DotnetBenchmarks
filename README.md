# .NET Benchmarks

## Overview

Welcome to my .NET Benchmarks repository! This repository is dedicated to benchmarking performance in .NET applications. Whether you're optimizing code, comparing different implementations, or evaluating the impact of changes, this collection of benchmarks will help you make informed decisions about the performance of your .NET projects.

## Table of Contents

- [Getting Started](#getting-started)
  - [Running Benchmarks](#running-benchmarks)
- [Benchmarking Guidelines](#benchmarking-guidelines)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with .NET benchmarks, follow these steps:

1. **Clone the Repository:**

```bash
git clone https://github.com/TrevorMcCubbin/DotnetBenchmarks.git
cd DotnetBenchmarks
```

Install .NET 8 SDK:
Make sure you have the .NET Core SDK installed.

### Running Benchmarks

To run Json Benchmarks in .Net 8:

```bash
dotnet run -c release --project .\src\DotnetBenchmarks.Json\DotnetBenchmarks.Json.csproj
```

To run a comparison of various benchmarks between .Net 8 and .Net Framework 4.8:

```bash
dotnet run -c release --project .\src\DotnetBenchmarks.FrameworkFaceOff\DotnetBenchmarks.FrameworkFaceOff.csproj --framework net8.0
```

Explore Results:
After running the benchmarks, explore the generated reports and analyze the performance metrics.

## Benchmarking Guidelines

When contributing benchmarks or analyzing results, please follow these guidelines:

    Isolate Benchmarks:
    Ensure that each benchmark is isolated and representative of a specific scenario or functionality.

    Repeatable Results:
    Benchmarks should be repeatable, providing consistent results across multiple runs.

    Documentation:
    Clearly document the purpose and methodology of each benchmark. Include relevant details about the test environment.

    Avoid Premature Optimization:
    Focus on meaningful optimizations rather than premature optimizations. Consider the trade-offs between readability and performance.

    Report Issues:
    If you encounter any issues or unexpected behavior in benchmarks, please report them using the GitHub Issues page.

## Contributing

We welcome contributions! To contribute to this repository:

- Fork the repository and create a new branch for your feature or bug fix.
- Make your changes and ensure all tests and benchmarks pass.
- Submit a pull request with a clear description of your changes.

## License

This project is licensed under the GNU 3 License - see the [LICENSE](LICENSE.txt) file for details.

Happy benchmarking! 🚀

# References

.NET Performance Analysis: Newtonsoft.Json vs System.Text.Json in .NET 8

https://trevormccubbin.medium.com/net-performance-analysis-newtonsoft-json-vs-system-text-json-in-net-8-34520c21d054

https://github.com/gtechsltn/DotnetBenchmarks

.NET Performance #2: Newtonsoft vs. System.Text.Json

https://medium.com/@tobias.streng/net-performance-series-2-newtonsoft-vs-system-text-json-2bf43e037db0

https://github.com/gtechsltn/NET7-Performance
