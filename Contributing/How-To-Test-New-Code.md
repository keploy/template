# Standard tests

Since Keploy is a testing platform that tests itself! We don't write Unit, Integration and System tests. We record and replay the test-cases via Keploy. 

- Unit tests
- Integration tests
- System tests

Unit tests are used to test individual components of the code for example a function or procedure. These should be performed by both contributors and maintainers.

Integration tests are used to test the integration of the different units to ensure that the different functions/procedures and modules are interacting correctly. These should also be performed by both contributors and maintainers.

System tests involve testing the complete integrated system, this includes performance tests and guidelines on speed performance to ensure that any new features or bug fixes do not compromise system performance.

These tests need to be performed by the maintainer, and the maintainer may also use independent testers if possible. Failure of a system test, or poor performance and may result in non-acceptance, or a request to improve performance before the pull-request if performance is accepted.
