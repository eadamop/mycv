summary:      A summary of the member.
description:  A description of the member. Markdown syntax may be used for rich text representation.
returns:      A description of the returned value.

parameters:
  - name: a
    description:  A description of the parameter.
    throws:
      - ArgumentNullException
      - ArgumentOutOfRangeException
  - name: b
    description:  A description of the parameter.
    throws:
      - ArgumentNullException
      - ArgumentOutOfRangeException

type parameters:
  - name: T
    description:  A description of the type parameter.
  - name: U
    description:  A description of the type parameter.

throws:
  ArgumentNullException:
    description:  A reason of the exception that can be thrown by the member.
  ArgumentOutOfRangeException:
    description:  A reason of the exception that can be thrown by the member.

remarks: |
A long remarks regarding the member.
Markdown syntax may be used for rich text representation.
With code examples like
``cs
var result = DoSomething(a, b);
``

example: |
``cs
var result = DoSomething(a, b);
var tranformed = DoSomethingMore(result);
Console.WriteLine(tranformed);
``

see:
  - OverloadedDoSomething(type, type)
  - OverloadedDoSomething(type, type)
  - MyAnotherClass
