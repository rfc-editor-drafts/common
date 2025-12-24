# Common

Data reference for editor tools / automations

## File Schemas

### abbreviations.json
```
Array<
  Object{
    term: String
    full: String
    wellknown?: Boolean
    note?: String
  }
>
```

### names.json
```
Array<
  Object{
    description: String
    match: Array<String>
  }
>
```
