# I_Error Interface

## Definition

|             |                            |
| ----------- | -------------------------- |
| Namespace   | mobject-errors             |
| Library     | mobject-errors             |
| Inheritance | \_\_System.IQueryInterface |
| Implements  |                            |

## Remarks

The I_Error interface should be implemented by any error class.

## Example

```declaration
FUNCTION_BLOCK MyError IMPLEMENTS I_Error
VAR
END_VAR
```

```body
//... no code should go here.
```

## Properties

### Message

Returns the message of the error

#### Return

| Datatype    | Description   |
| ----------- | ------------- |
| T_MAXSTRING | Error Message |
