# NLP-Test-Prioritization

With [natural language tests](https://en.wikipedia.org/wiki/Manual_testing), it's very time consuming to have too similar or redundant test cases, as every test case usually involves a human testing the response of a system.
To avoid this waste of time we need to

    1. prioritize the more important tests, and

    2. avoid redundant test cases.

This repository aims to do this by embedding the test descriptions and then clustering their embeddings, thereby recognizing similar tests and even identify tests that are redundant.
