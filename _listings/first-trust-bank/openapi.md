swagger: "2.0"
x-collection-name: First Trust Bank
x-complete: 1
info:
  title: First Trust Bank
  description: this-is-the-open-banking-driven-set-of-apis-for-first-trust-bank--providing-a-machine-readable-definition-of-what-is-available-via-their-open-banking-set-of-apis-
  termsOfService: https://www.openbanking.org.uk/open-licence/
  contact:
    name: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
  version: 1.0.0
host: openapi.firsttrustbank.co.uk
basePath: open-banking/v2.1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  personal-current-accounts/:
    get:
      summary: Get Current Personal Accounts
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can own multiple PCA products.
      operationId: getCurrentPersonalAccounts
      x-api-path-slug: personalcurrentaccounts-get
      responses:
        200:
          description: OK
      tags:
      - Current
      - Personal
      - Accounts