Coding standard 0
=================

PROPOSAL (ALPHA)!

Coding standard js-std are style guidelines for programming in JavaScript.

Document 2017-05-17T19:49:13Z

Minimal picktime 2018-01-01

Key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT",
"SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL"
in this document are to be interpreted as described in [RFC 2119][RFC 2119].

[RFC 2119]: http://www.ietf.org/rfc/rfc2119.txt

- Always compatibile with prev major version (MUST).
- Without semicolons (SHOULD).
- 4 spaces for indenting code (SHOULD).
- Class names "StudlyCaps" (SHOULD).
- Property names "camelCase" (SHOULD).
- Method names "camelCase" (SHOULD).
- Constans names "UPPER_CASE" with underscore separators (SHOULD).
- Soft limit for line length: 80 characters, hard limit: 120 characters (SHOULD).
- Encoding UTF-8 (MAY) (?).

Example class:

    class Foo
    {
        constructor()
        {
            // ...
        }

        get()
        {
            // ...
        }

        // ...
    }
