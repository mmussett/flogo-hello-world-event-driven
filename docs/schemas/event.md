# Greeting Schema Schema

```txt
https://https://github.com/mmussett/flogo-hello-world-event-driven/schemas/event.schema.json
```

A representation of a greeting event

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                    |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [event.schema.json](event.schema.json "open original schema") |

## Greeting Schema Type

`object` ([Greeting Schema](event.md))

# Greeting Schema Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                          |
| :-------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [greeting](#greeting) | `string` | Required | cannot be null | [Greeting Schema](event-properties-greeting.md "https://https://github.com/mmussett/flogo-hello-world-event-driven/schemas/event.schema.json#/properties/greeting") |

## greeting

A simple greeting string

`greeting`

* is required

* Type: `string`

* cannot be null

* defined in: [Greeting Schema](event-properties-greeting.md "https://https://github.com/mmussett/flogo-hello-world-event-driven/schemas/event.schema.json#/properties/greeting")

### greeting Type

`string`

### greeting Constraints

**maximum length**: the maximum number of characters for this string is: `255`

**minimum length**: the minimum number of characters for this string is: `1`

### greeting Examples

```json
"john doe"
```

```json
"mike smith"
```
