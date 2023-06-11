In Scala, all values have a type including functions and numerical values.

`Any` is the supertype of all types and have methods like `equals` , `toString` and `hashCode`. It has two subtypes - `AnyRef` and `AnyVal`. Values that are subtype of `AnyVal` can not be `null`. `Unit ` is equivalent of java `void` and has exactly one literal value - `()`

If Scala is used in context of JRE, `AnyRef` corresponds to `java.lang.Object`.

Casting is unidirectional. You can not cast a reference type to a subtype.

`Nothing` is the bottom type and no value has this type. It is used to signal non-termination, such as a thrown exception, program exit or an infinite loop.

`Null` is subtype of all reference types. It has single literal value `null`

`Members` are public by default. Use `private` access modifier keyword to hide them outside of the class.

Primary constructor parameters with `val` or `var` are public. Without `val` or `var` they are private values.


