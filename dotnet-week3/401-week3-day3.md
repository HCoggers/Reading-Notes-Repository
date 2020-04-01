### Week 3, Wednesday
## Model Validation Attributes
Model validation allows you to create your own custom validation attributes for the user input you're dealing with, but it also has plenty of useful, built in validations that may already satisfy your needs. Assign these attributes above your Model properties to have any incoming data cleanly validated.
- `[CreditCard]` Validates that the property has a credit card format.
- `[Compare]` Validates that two properties in a model match.
- `[EmailAddress]` Validates that the property has an email format.
- `[Phone]` Validates that the property has a telephone number format.
- `[Range]` Validates that the property value falls within a specified range.
- `[RegularExpression]` Validates that the property value matches a specified regular expression.
- `[Required]` Validates that the field is not null.
- `[StringLength]` Validates that a string property value doesn't exceed a specified length limit.
- `[Url]` Validates that the property has a URL format.
- `[Remote]` Validates input on the client by calling an action method on the server. See [Remote] attribute for details about this attribute's behavior.

Keep in mind there are some html elements that reduce your need for input validation, not all html tags are semantic!
#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)