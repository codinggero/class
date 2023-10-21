# **What is Dart**

> Dart is an open-source, general-purpose programming language developed by Google. It was first announced in 2011 and has since gained popularity as the primary language for building applications with the Flutter framework. Dart is designed for a range of applications, including web development, server-side scripting, mobile app development, and even desktop applications.

**Key features and characteristics of Dart include:**

1. **Object-Oriented**: Dart is an object-oriented language, which means it supports concepts like classes, objects, and inheritance, making it well-suited for building modular and structured code.

2. **Strongly Typed**: Dart is a statically typed language, which means that variable types are known at compile-time. This helps catch type-related errors early in the development process, making the code more reliable.

3. **Just-In-Time (JIT) and Ahead-of-Time (AOT) Compilation**: Dart can be compiled in two ways. JIT compilation allows for fast development and hot reload capabilities, while AOT compilation generates highly optimized native code for better performance in production.

4. **Garbage Collection**: Dart features automatic memory management with a garbage collector that handles memory allocation and deallocation, reducing the risk of memory leaks.

5. **Concurrency**: Dart supports asynchronous programming using `async` and `await` keywords, making it well-suited for building applications that require non-blocking, event-driven code, such as web and mobile applications.

6. **Dart SDK**: The Dart SDK includes the Dart runtime, libraries, and tools necessary for developing Dart applications. It also includes a package manager called pub for managing dependencies.

7. **Web Development**: Dart can be used for web development and has a web framework called "Aqueduct" for building server-side applications.

8. **Flutter**: Dart is most well-known for its use in Flutter, a popular open-source UI framework developed by Google. Flutter allows you to build natively compiled applications for mobile, web, and desktop platforms using a single codebase.

9. **Community and Ecosystem**: While not as widely adopted as some other languages, Dart has a growing and active community. Developers have created a variety of packages and libraries that are available through the Dart Package Manager (pub.dev).

# **What is Flutter**

> Flutter is an open-source UI (User Interface) framework developed by Google that is used for building natively compiled applications for mobile, web, and desktop from a single codebase. It was first released in 2017 and has gained significant popularity among developers for its ability to create high-quality, visually appealing, and fast applications.

Key features and characteristics of Flutter include:

1. **Single Codebase**: With Flutter, you can write one set of code that runs on multiple platforms, including iOS, Android, web, and desktop. This significantly reduces development time and effort.

2. **Widgets**: Flutter uses a wide range of customizable widgets to build the user interface. Widgets are a fundamental building block of Flutter applications, and they can be combined to create complex UIs.

3. **Hot Reload**: Flutter's hot reload feature allows developers to see the results of their code changes in real-time, making it easier to experiment and iterate quickly.

4. **High Performance**: Flutter compiles to native code, which leads to high performance and smooth animations. It doesn't rely on a bridge to communicate with native components, as is the case with some other cross-platform frameworks.

5. **Expressive and Beautiful UI**: Flutter is known for its expressive and flexible UI, which can be customized to achieve unique and visually appealing designs. It also supports Material Design and Cupertino (iOS-style) widgets out of the box.

6. **Dart Programming Language**: Flutter uses the Dart programming language, which was also developed by Google. While Dart may not be as widely used as some other languages, it's easy to learn and work with.

7. **Growing Ecosystem**: The Flutter ecosystem is growing rapidly, with a wide range of packages and plugins available through the Dart Package Manager (pub.dev). This makes it easy to extend your app's functionality.

8. **Support for Web and Desktop**: Flutter has expanded its platform support beyond mobile and can be used to build web and desktop applications, in addition to mobile apps.

9. **Open Source and Community-Driven**: Flutter is an open-source project with an active and supportive community. This means there are ample resources and community-driven solutions available to developers.

10. **Official Support from Google**: As an official Google project, Flutter receives ongoing support and updates.

# **Flutter/Dart Data Types**

> Dart is the programming language primarily associated with Flutter, and it provides a variety of data types to work with different kinds of values. Here are some of the most common data types in Dart:

1. **Numbers**:

   - `int`: Represents integers, both positive and negative. For example, `int age = 30;`.
   - `double`: Represents floating-point numbers (numbers with a decimal point). For example, `double price = 9.99;`.

2. **Strings**:

   - `String`: Represents sequences of characters, such as text. For example, `String name = "John";`.

3. **Booleans**:

   - `bool`: Represents boolean values, which can be either `true` or `false`. For example, `bool isStudent = true;`.

4. **Lists**:

   - `List`: Represents an ordered collection of values. Dart supports both fixed-size and growable lists. For example, `List<int> numbers = [1, 2, 3];`.

5. **Maps**:

   - `Map`: Represents a collection of key-value pairs. For example, `Map<String, int> scores = {'Alice': 95, 'Bob': 89};`.

6. **Sets**:

   - `Set`: Represents an unordered collection of unique values. For example, `Set<String> uniqueColors = {'red', 'green', 'blue'};`.

7. **Dynamic**:

   - `dynamic`: Represents a type that can hold values of any type. It's a way to opt out of static type checking. For example, `dynamic x = 42;`.

8. **Object**:

   - `Object`: The ultimate base class for all Dart objects. All Dart objects are instances of the `Object` class.

9. **Null**:

   - `null`: Represents the absence of a value. It is often used to indicate that a variable has not been assigned a value yet.

10. **Enums**:

    - `enum`: Defines a fixed set of constants. For example:
      ```dart
      enum Color { red, green, blue }
      Color selectedColor = Color.red;
      ```

11. **Functions**:

    - Dart treats functions as first-class citizens, meaning you can assign functions to variables, pass them as arguments, and return them from other functions.

12. **User-Defined Classes**:

    - Dart allows you to create your own custom data types by defining classes.

13. **Type Definitions**:

    - You can create custom type definitions using `typedef`, allowing you to create more descriptive types for functions and callbacks.

## **Flutter/Dart Identifier**:

In Flutter/Dart, identifiers are names given to various program elements such as variables, functions, classes, and more. Identifiers must follow specific rules and conventions to be valid in Dart. Here are some key rules and conventions for Dart identifiers:

1. **Rules for Identifiers**:

   - Identifiers must start with either a letter (uppercase or lowercase) or an underscore `_`.
   - After the first character, identifiers can include letters, digits, and underscores.
   - Identifiers are case-sensitive. For example, `myVar` and `myvar` are considered different identifiers.
   - Identifiers cannot be Dart reserved words or keywords. For example, you cannot name a variable "int" or "while" because these are reserved words in Dart.

2. **Naming Conventions**:

   - Dart follows a convention of using "CamelCase" or "lowerCamelCase" for most identifiers. This means that the first letter of the identifier is lowercase, and the first letter of each subsequent concatenated word is uppercase. For example: `myVariableName`, `calculateTotalAmount`.
   - Class names should follow a similar convention but start with an uppercase letter. For example: `MyClass`, `PersonDetails`.
   - Constants should be named using all uppercase letters with underscores separating words. For example: `PI`, `MAX_LENGTH`.

3. **Underscores**:

   - It is common to use an underscore at the beginning of an identifier to indicate that it's a private variable or function. For example, `_privateVar`, `_calculateTotal`.

Here are some examples of valid and invalid Dart identifiers:

Valid Identifiers:

```dart
myVariable
myClass
calculateTotalAmount
_PI
MAX_LENGTH
_privateVar
```

Invalid Identifiers (due to various issues):

```dart
123invalid (starts with a digit)
while (a reserved keyword)
my-variable (contains a hyphen)
my variable (contains a space)
```

# **Dart Comments**:

> In Dart, you can use comments to add explanatory notes or remarks to your code. Comments are ignored by the Dart compiler and are solely meant for developers to document their code. Dart supports both single-line and multi-line comments. Here's how you can use comments in Dart:

1. **Single-Line Comments**:

   Single-line comments start with two forward slashes (`//`) and continue until the end of the line. They are typically used for brief comments or explanations on a single line of code.

   ```dart
   // This is a single-line comment.
   var age = 30; // Variable for storing age.
   ```

2. **Multi-Line Comments**:

   Multi-line comments are enclosed within `/*` and `*/`. They can span multiple lines and are suitable for longer explanations, comments, or for temporarily "commenting out" blocks of code.

   ```dart
   /*
   This is a multi-line comment.
   It can span multiple lines.
   */
   var temperature = 25; /* Variable for storing temperature. */
   ```

3. **Documentation Comments**:

   Dart also supports documentation comments for generating code documentation using tools like DartDoc. Documentation comments start with `///` for single-line comments or `/**` for multi-line comments. They are often used to provide documentation for classes, methods, and libraries.

   ```dart
   /// This is a documentation comment for a function.
   /// It should describe the purpose of the function.
   int add(int a, int b) {
     return a + b;
   }
   ```

   Dart documentation comments can include special tags like `@param`, `@return`, and `@throws` to provide additional information about function parameters, return values, and exceptions.

4. **Nesting Comments**:

   Dart allows you to nest comments within one another. For example, you can have a single-line comment inside a multi-line comment or vice versa.

   ```dart
   /* This is a multi-line comment.
      You can use // inside it for a single-line comment. */
   var x = 42;
   ```

# **Dart Keywords**

> In Dart, keywords are reserved words that have special meanings and are used for specific purposes in the language. These keywords cannot be used as identifiers (variable names, function names, class names, etc.) because they have predefined roles in the language's syntax and semantics. Here is a list of Dart keywords as of my knowledge cutoff date in September 2021:

```dart
abstract
as
assert
async
await
break
case
catch
class
const
continue
covariant
default
deferred
do
dynamic
else
enum
export
extends
extension
external
factory
false
final
finally
for
Function
get
if
implements
import
in
interface
is
late
library
mixin
new
null
on
operator
part
rethrow
return
set
show
static
super
switch
sync
this
throw
true
try
typedef
var
void
while
with
yield
```

# **Dart Variable an Rule to Create Variable**

> In Dart, a variable is a named storage location that holds data or values. Variables are essential for storing and manipulating data in your programs. To create a variable in Dart, you follow these basic rules:

1. **Declaration**: To declare a variable, use the `var`, `final`, or `const` keyword, followed by the variable name, an optional type annotation, and an optional initializer (initial value). Here are the variable declaration forms:

   - **`var`**: Used for variables whose values can change (mutable).
     ```dart
     var variableName = initialValue;
     ```
   - **`final`**: Used for variables whose values are constant after they are initialized. These values cannot be changed (immutable).
     ```dart
     final variableName = initialValue;
     ```
   - **`const`**: Used for constant values that are known at compile-time and cannot be changed (immutable).
     ```dart
     const variableName = initialValue;
     ```

   For example:

   ```dart
   var name = "John";
   final age = 30;
   const pi = 3.14159;
   ```

2. **Type Annotation** (Optional): You can explicitly specify the data type of a variable using a type annotation, or you can let Dart infer the type based on the initializer. For example:

   ```dart
   int count = 5; // Type annotation specifies 'int'.
   var length = 10; // Dart infers the type as 'int'.
   ```

3. **Identifier Rules**: Dart variable names (identifiers) must follow these rules:
   - Start with a letter (uppercase or lowercase) or underscore `_`.
   - After the first character, can include letters, digits, and underscores.
   - Cannot be a Dart reserved word (keyword).
   - Must be unique within the same scope.

Here are some examples of variable declarations in Dart:

```dart
var name = "Alice"; // Inferred type: String
var age = 25;       // Inferred type: int
var isStudent = true; // Inferred type: bool

final city = "New York"; // Inferred type: String
final population = 8_399_000; // Inferred type: int

const pi = 3.14159; // Inferred type: double

int count; // Declaring a variable without an initial value (null by default).
```
