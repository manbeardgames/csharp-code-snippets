# Full Properties
This directory contains snippets for quickly creating public properties with private backing fields.  Each of these snippets uses the following pattern

```
private <type> <field_name>;
public <type> <property_name>
{
    get { return <field_name> ;}
    set
    {
        if(<field_name> == value) { return; }
        <field_name> = value;
    }
}
```

The following snippets are contained in this directory

| Snippet | Description |
| --- | --- |
| `boolpropfull` | Creates a public property with a private backing field, with the type set as `bool` |
| `bytepropfull` | Creates a public property with a private backing field, with the type set as `byte` |
| `charpropfull` | Creates a public property with a private backing field, with the type set as `char` |
| `decimalpropfull` | Creates a public property with a private backing field, with the type set as `decimal` |
| `doublepropfull` | Creates a public property with a private backing field, with the type set as `double` |
| `floatpropfull` | Creates a public property with a private backing field, with the type set as `float` |
| `intpropfull` | Creates a public property with a private backing field, with the type set as `int` |
| `longpropfull` | Creates a public property with a private backing field, with the type set as `long` |
| `sbytepropfull` | Creates a public property with a private backing field, with the type set as `sbyte` |
| `shortpropfull` | Creates a public property with a private backing field, with the type set as `short` |
| `stringpropfull` | Creates a public property with a private backing field, with the type set as `string` |
| `uintpropfull` | Creates a public property with a private backing field, with the type set as `uint` |
| `ulongpropfull` | Creates a public property with a private backing field, with the type set as `ulong` |
| `ushortpropfull` | Creates a public property with a private backing field, with the type set as `ushort` |