# openapi-axios-sample
openapi generate axios codes samples

reference: https://zenn.dev/offers/articles/20220620-openapi-generator

# Commands

## generate axios codes
```sh
docker run --rm -v "${PWD}:/local" openapitools/openapi-generator-cli generate \
  -i /local/openapi.yml \
  -g typescript-axios \
  -o /local/generated
```