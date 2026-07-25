# Errata 4169 - RFC 7230

- **RFC Title:** Hypertext Transfer Protocol (HTTP/1.1): Message Syntax and Routing
- **RFC Publication Date:** June 2014

```
Section 7 says:


     #element => [ ( "," / element ) *( OWS "," [ OWS element ] ) ]



     1#element => *( "," OWS ) element *( OWS "," [ OWS element ] )



   Empty elements do not contribute to the count of elements present.

   For example, given these ABNF productions:



     example-list      = 1#example-list-elmt

     example-list-elmt = token ; see Section 3.2.6



   Then the following are valid values for example-list (not including

   the double quotes, which are present for delimitation only):



     "foo,bar"

     "foo ,bar,"

     "foo , ,bar,charlie   "
     
// state how to fix the above text here
```

## Issue description

Section 7 of RFC 7230 defines ABNF rules for HTTP list elements and provides example valid values for `example-list`. One of the listed example values does not actually conform to the `1#element` rule as defined, creating an inconsistency between the ABNF grammar and the stated examples. This affects how implementations should parse and validate lists of elements in HTTP messages.
