# Greeting Schema

- [1. Property `Greeting Schema > greeting`](#greeting)

**Title:** Greeting Schema

|                           |                                                                           |
| ------------------------- | ------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                  |
| **Required**              | No                                                                        |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

**Description:** A representation of a greeting event

| Property                 | Pattern | Type   | Deprecated | Definition | Title/Description        |
| ------------------------ | ------- | ------ | ---------- | ---------- | ------------------------ |
| + [greeting](#greeting ) | No      | string | No         | -          | A simple greeting string |

## <a name="greeting"></a>1. Property `Greeting Schema > greeting`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** A simple greeting string

**Examples:** 

```json
"john doe"
```

```json
"mike smith"
```

| Restrictions   |     |
| -------------- | --- |
| **Min length** | 1   |
| **Max length** | 255 |

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2024-07-31 at 10:53:22 +0000
