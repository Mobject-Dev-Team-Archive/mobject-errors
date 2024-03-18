# I_Error Interface

## Definition

|             |                |
| ----------- | -------------- |
| Namespace   | mobject-errors |
| Library     | mobject-errors |
| Inheritance |                |
| Implements  | I_Error        |

## Remarks

The Error abstract base class should be used to implement custom error classes. This provides inbuilt seralization functionality, and error comparison.

## Example

```declaration
FUNCTION_BLOCK MyError EXTENDS Error
VAR
END_VAR
```

```body
//... no code should go here.
```

## Methods

### SerializeWith(Serializer)

### IsSameAs(Error) : BOOL

## Properties

### ErrorType

Returns the error type of the error. Error types should relate to a library or application. For example, deserialization errors will be found in mobject-deserialization.

#### Return

| Datatype    | Description |
| ----------- | ----------- |
| T_MAXSTRING | Error Type  |

### Message

Returns the message of the error

#### Return

| Datatype    | Description   |
| ----------- | ------------- |
| T_MAXSTRING | Error Message |
