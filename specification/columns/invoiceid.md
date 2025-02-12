# Invoice ID

An Invoice ID is .....

The InvoiceID column adheres to the following requirements:
Is an optional column, allows NULL and MUST be used if a cloud service provider has invoiceID prepopulated in their billing data.

* The InvoiceID column SHOULD be present in a [*FOCUS dataset*](#glossary:FOCUS-dataset).
* This column MUST be of type String and MAY contain null values.

See [Appendix: Origination of cost data](#originationofcostdata) section for examples of [Provider](#provider), [Publisher](#publisher) and
Invoice ID values that can be used for various purchasing scenarios.

## Column ID

InvoiceID

## Display Name

Invoice ID

## Description



## Content Constraints

| Constraint      | Value           |
|:----------------|:----------------|
| Column type     | Dimension       |
| Feature level   | Mandatory       |
| Allows nulls    | False           |
| Data type       | String          |
| Value format    | \<not specified> |

## Introduced (version)

1.2
