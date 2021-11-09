# Pattern Title

<!-- https://regexr.com/ -->
<!-- https://regexlib.com/REDetails.aspx?regexp_id=167 -->

This regular expression is designed for validating email address inputs. It has checks for ensuring that emails are being entered in the correct formats and are including the typical characters one might expect in an address. 

## Summary
	
^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]+)\.([a-zA-Z]{2,5})$

This is the expression I will be describing functionality for. It is essentially broken down into three different validations. Further elaboration below.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Character Escapes](#character-escapes)

## Regex Components
This expression can be broken down into 3 sections:
([a-zA-Z0-9_\-\.]+) checking for uppercase, lowercase and numeric characters
([a-zA-Z0-9_\-\.]+) checking for uppercase, lowercase and numeric characters
and ([a-zA-Z]{2,5}) checking for uppercase and lowercase characters

### Anchors
^ and $

### Quantifiers
+, + and {2,5}

### Bracket Expressions
[a-zA-Z0-9_\-\.]
and 
[a-zA-Z]

### Character Classes
[a-z]
[A-Z]
[0-9]

### Character Escapes
\- and \.

## Author

Jack is an amateur web developer taking a coding bootcamp and hopign to expand his skillset into being a career-ready developer!
[Github](https://github.com/Jcarps97)
