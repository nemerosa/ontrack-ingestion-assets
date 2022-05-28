ontrack-ingestion-assets
========================

Public assets for promotions and validations, to be used in [Ontrack ingestion configurations](https://static.nemerosa.net/ontrack/release/latest/docs/doc/index.html#integration-github-ingestion-customization).

For example:

```yaml
validations:
  - name: build-run
    description: Complete CI build has run
    image: nemerosa/ontrack-ingestion-assets/validations/build.png
promotions:
  - name: BRONZE
    description: Build OK
    image: nemerosa/ontrack-ingestion-assets/promotions/bronze.png
    validations:
      - build-run
```
