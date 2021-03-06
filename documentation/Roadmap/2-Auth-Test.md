# Roadmap

## Authentication Test

- Create a `.env.testing` file

    ```shell
    cp .env .env.testing
    ```

  > This file will be used instead of the `.env` file when running PHPUnit tests or executing Artisan commands with the
  > `--env=testing` option.

- Creating a feature test

    ```sh
    sail artisan make:test AuthTest
    ```

- Execute your first test

    ```sh
    sail artisan test --env=testing
    ```
- Execute the tests for Feature suite

    ```sh
    php artisan test --testsuite=Feature --stop-on-failure
    ```

## References

- https://dev.to/seankerwin/laravel-8-rest-api-with-resource-controllers-5bok
