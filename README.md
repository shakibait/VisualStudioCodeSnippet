# Code Snippets
 Visual studio +2010 Code Snippets customization

This is my favorites code snippets in visual studio

# Includes code snippets for:
- Class structure
- Mehtod structure
- Class object definition

# Installation
1. Copy *.snippet files in any directory you want.
2. In visual studio Tools menu > Code Snippets Manager
3. Select CSharp Language and Select My Code Snippets
4. Click on Import and select *.snippet files.
5. Enjoy

# Usage
## Class structure

Type pclass and double tap:

```csharp
public class MyClass
{
	// Your code
}
```
	
## Method structure
There is 2 type of methods:
1.  Static methods
Type ps for methods without parameter
	```csharp
	public static void Method()
	{
		//Your code
	}
	```
	Or you can type ps1 to 3 for methods with argument
	```csharp
	public static void Method(TYPE1 paramName1, TYPE2 paramName2, TYPE3 paramName3)
	{
		//Your code
	}
	```
2. Non static methods
	Also you can type pv (pv1, pv2, pv3) for non static methods
	```csharp
	public void Method(TYPE paramName)
	{
		//Your code
	}
	```

## Class Object Definition
Type obj and double tap:

    ClassName obj = new ClassName();