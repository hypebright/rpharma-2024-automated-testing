# From Annoying to Automated: Running Tests with GitHub Actions

R/Pharma 2024 presentation and materials for the lightning talk "From Annoying to Automated: Running Tests with GitHub Actions"⚡️.

![R/Pharma 2024 Lightning Talk](images/rpharma2024.png)

## Example test repo

You can find the example test repo [here](https://github.com/hypebright/RPharmaTest). On this repo, there are two GitHub Actions running whenever there's a push to the `main` branch or a push on a pull request to the `main` branch. The first action runs the tests and the second action checks the test coverage with `covr`.

⚠️ Note that you need to get a token from Codecov and add it to your GitHub repo secrets to get the test coverage action to work! Just follow the [instructions from the Codecov docs](https://docs.codecov.com/docs/adding-the-codecov-token).
