# CAS Registry Utility

CAS Registry Numbers (CAS Numbers) are unique numerical identifiers assigned to chemical substances. They are managed by the [Chemical Abstracts Service](https://www.cas.org/).

An example is 58-08-2, which is the CAS Number for Caffeine.

This package contains a class to validate CAS Numbers by ensuring they're in the correct format and that they contains a valid check digit.

## Usage

```
// Get Simple true/false result
bool result = CasNumberValidator.IsValid("58-08-2");

// Get Validation Result object which contains
// a message with details if validation failed
IValidationResult = CasNumberValidator.Validate("58-08-2");
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

# References

- [Wikipedia entry on CAS Registry Number](https://en.wikipedia.org/wiki/CAS_Registry_Number)
- [CAS Registry FAQ](https://www.cas.org/support/documentation/chemical-substances/faqs)
- [Check Digit Verification of CAS Registry Numbers](https://www.cas.org/support/documentation/chemical-substances/checkdig)