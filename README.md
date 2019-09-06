# Useful Regex for input validation
 See it in action https://mbotha.github.io/regex-validation
 
## Regex

### Email
```
^[-+.0-9A-Z_a-z]+@[-+.0-9A-Z_a-z]+\.[A-Za-z]{2,4}
```
### Telephone number
Matches a US phone numbe. 1 in the beginning is optional, area code is required, spaces or dashes can be used as optional divider between number groups. Also alphanumeric format is allowed after area code.
```
^([0-9]( |-)?)?(\(?[0-9]{3}\)?|[0-9]{3})( |-)?([0-9]{3}( |-)?[0-9]{4}|[a-zA-Z0-9]{7})$
 ```
