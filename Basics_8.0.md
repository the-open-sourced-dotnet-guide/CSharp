## Introduction

The Basics of C# using version 8.0.

## Prerequisites

- [ ] \(Optional) Visual Studio 2019 (any edition) or newer
- [ ] \(Optional) .NET Core 3.0 or newer

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Table of Contents](#table-of-contents)
4. [The structure of a C# file using HelloWorld.cs as an example](#the-structure-of-a-c-file-using-helloworldcs-as-an-example)
5. [Keywords](#keywords)
6. [Datatypes](#datatypes)
   1. [Simples Types](#simples-types)
7. [Enumerations](#enumerations)
8. [Conditionals](#conditionals)
   1. [Operators](#operators)
9. [Classes](#classes)
10. [By Value and By Reference Types](#by-value-and-by-reference-types)
   1. [Structs](#structs)
11. [Anonymous Types](#anonymous-types)
12. [Dynamic Types](#dynamic-types)
13. [Arrays and Lists](#arrays-and-lists)
   1. [Arrays](#arrays)
   2. [Lists](#lists)
14. [Exceptions](#exceptions)
15. [Credits and Citations](#credits-and-citations)
   1. [Citations](#citations)

## The structure of a C# file using HelloWorld.cs as an example

All C# files have the extension CS. For example `Program.cs` in the ["Hello, World"](http://www.foo.com) example.

TODO: Namspace (Your project and referencing), Program.cs, Main() method, parameters

## Keywords

## Datatypes

When programmers say datatype they generally mean what kind of data can the variable handle. For example `bool isFemale = false;`

There are two kinds of variables. ["value and reference types"]("#By Value and By Reference Types").

Of those type kinds there are a couple of types inside of those. All of which we will go over the details later. Don't expect to memorize all of these right off the bat however some should be intuitive as to what they mean. [1]("#Citations_datatypes")

### Simples Types

Signed inegral: `sbyte`, `short`, `int`, and `long`. Signed means it can be a negative or a positive number however at the cost of half the size of an unsigned. Two examples of a signed `int` are: `42` and `-1`. The differene between each of these is how large of a number they can hold. Specifically, it's how many bits it is.

Here is a table showing a list of these:

Datatype | Range | Bit Size
---------|-------|---------
`sbyte` | -128 to 127 | 8
`short` | -32,768 to 32,767 | 16
`int` | -2,147,483,648 to 2,147,483,647 (2.1 billion) | 32
`long` | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 ([9.2 quintillion]("https://en.wikipedia.org/wiki/9,223,372,036,854,775,807")) | 64

Unsigned inegral's are unsigned. Meaning they are only positive numbers however are double in size. So, for instance, the `sbyte` value of `-128 to 127` is, instead, `0-255` for `byte` (note the lack of the `s`).

## Enumerations

An `enum` is a ["value type"]("#By Value and By Reference Types") that allows for you to define you own list.
For example:

```c#
enum EyeColor 
{
   Blue,
   Green,
   Hazel,
   Brown
}
```

and you would reference it like so:

```c#
private void Foo() {
   EyeColor Sarah_EyeColor = EyeColor.Blue;
}
```

## Conditionals

### Operators

## Classes

## By Value and By Reference Types

### Structs

## Anonymous Types

## Dynamic Types

## Arrays and Lists

### Arrays

### Lists

## Exceptions

## Credits and Citations

### Citations

- [1](https://docs.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/types-and-variables)
- [2](https://softwareengineering.stackexchange.com/a/221897) - Arrays versus Lists.
- 
