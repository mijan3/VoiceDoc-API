| Requirement | Input/action | Expected result |
|---|---|---|
| FR-02 | Create a form with no title | Show validation error |
| FR-05 | Quantity is negative | Reject or flag the value |
| FR-05 | Required price is absent | Leave empty and request clarification |
| FR-06 | Change extracted quantity | Updated value appears in the draft |
| FR-07 | Draft has not been confirmed | No confirmed business record is created |
| FR-08 | Search for an existing customer | Matching records appear |


| Field | Type | Validation |
|---|---|---|
| Customer name | Text | Required |
| Product | Text | Required |
| Quantity | Integer | Greater than zero |
| Unit price | Number | Zero or greater |
| Payment status | Enumeration | Paid, Unpaid, Unknown |

