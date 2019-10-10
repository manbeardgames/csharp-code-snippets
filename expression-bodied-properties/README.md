# Expression Bodied Properties
This directory contains snippets for quickly creating expression bodied properties.  Each of these snippets uses the following pattern

```
private <type> <field_name>;
public <type> <property_name>
{
    get => <field_name>;
    set => <field_name> = value;
}
```

The following snippets are contained in this directory

| Snippet | Description |
| --- | --- |
| `boolexpbodprop` | Creates an expression bodied property with the type set as `bool` |
| `byteexpbodprop` | Creates an expression bodied property with the type set as `byte` |
| `charexpbodprop` | Creates an expression bodied property with the type set as `char` |
| `decimalexpbodprop` | Creates an expression bodied property with the type set as `decimal` |
| `doubleexpbodprop` | Creates an expression bodied property with the type set as `double` |
| `expbodprop` | Creates an expression bodied property. You can set the type |
| `floatexpbodprop` | Creates an expression bodied property with the type set as `float` |
| `intexpbodprop` | Creates an expression bodied property with the type set as `int` |
| `longexpbodprop` | Creates an expression bodied property with the type set as `long` |
| `sbyteexpbodprop` | Creates an expression bodied property with the type set as `sbyte` |
| `shortexpbodprop` | Creates an expression bodied property with the type set as `short` |
| `stringexpbodprop` | Creates an expression bodied property with the type set as `string` |
| `uintexpbodprop` | Creates an expression bodied property with the type set as `uint` |
| `ulongexpbodprop` | Creates an expression bodied property with the type set as `ulong` |
| `ushortexpbodprop` | Creates an expression bodied property with the type set as `ushort` |