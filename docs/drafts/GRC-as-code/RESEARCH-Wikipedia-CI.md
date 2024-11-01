# Wikipedia - Continuous Integration

[Source](https://en.wikipedia.org/wiki/Continuous_integration)

Key excerpts:

```
CI benefits include:

    Facilitates detecting bugs earlier

    Reduces effort to find cause of bugs;
    if a CI test fails then changes since last good build contain causing change;
    if build after each change then exactly one change is the cause[1]

    Avoids the chaos of integrating many changes

    When a test fails or a bug is found,
    reverting the codebase to a good state results in fewer lost changes

    Frequent availability of a known-good build for testing, demo, and release

    Frequent code commit encourages modular, less complex code

    Quick feedback on system-wide impact of code changes

    Supports collection of software metrics such as code coverage, code complexity
```

```
Risks of CI include:

    Build system setup requires effort

    Writing and maintaining an automated test suite requires effort

    Value added depends on the quality of tests

    High build latency (sitting in queue) limits value

    Implies that incomplete code should not be integrated which is counter
    to some developer's preferred practice
    
    Safety and mission-critical development assurance
    (e.g., DO-178C, ISO 26262) require documentation and review which may
    be difficult to achieve
```
