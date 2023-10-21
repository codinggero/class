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

> In Flutter/Dart, a variable is a named storage location that holds data or values. Variables are essential for storing and manipulating data in your programs. To create a variable in Flutter/Dart, you follow these basic rules:

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

2. **Type Annotation** (Optional): You can explicitly specify the data type of a variable using a type annotation, or you can let Flutter/Dart infer the type based on the initializer. For example:

   ```dart
   int count = 5; // Type annotation specifies 'int'.
   var length = 10; // Dart infers the type as 'int'.
   ```

3. **Identifier Rules**: Flutter/Dart variable names (identifiers) must follow these rules:
   - Start with a letter (uppercase or lowercase) or underscore `_`.
   - After the first character, can include letters, digits, and underscores.
   - Cannot be a Flutter/Dart reserved word (keyword).
   - Must be unique within the same scope.

Here are some examples of variable declarations in Flutter/Dart:

```dart
var name = "Alice"; // Inferred type: String
var age = 25;       // Inferred type: int
var isStudent = true; // Inferred type: bool

final city = "New York"; // Inferred type: String
final population = 8_399_000; // Inferred type: int

const pi = 3.14159; // Inferred type: double

int count; // Declaring a variable without an initial value (null by default).
```

# **Flutter/Dart Constants vs Final Variables**

> In Flutter/Dart, both constants (created using `const`) and final variables (declared with `final`) are used to represent values that cannot be changed after they are initialized. However, there are important differences between the two:

**Constants (`const`)**:

- Constants are evaluated at compile-time, and their values are known at the time of compilation.
- They are primarily used for values that are known and fixed before the program runs, such as numeric constants, string constants, and expressions that can be determined at compile-time.
- Constants are more efficient in terms of performance because they are determined at compile-time and can be optimized by the Dart compiler.
- Constants can be used to create constant expressions, constant lists, and constant maps.

Example:

```dart
const double pi = 3.14159;
const int secondsPerMinute = 60;
const String welcomeMessage = "Hello, Dart!";
```

**Final Variables (`final`)**:

- Final variables are evaluated at runtime. They are assigned a value when the program runs, and once assigned, that value cannot be changed.
- Final variables are used for values that may be determined at runtime but remain constant during the program's execution.
- They are commonly used for values that are assigned once and should not change afterward, such as instance variables in classes.
- Final variables are more flexible compared to constants because they can be assigned values that are not known at compile-time.

Example:

```dart
final int age = 30;
final String appName = getApplicationName();
```

Here are some key considerations when choosing between constants and final variables:

- Use constants when the value is known at compile-time, as they are more efficient and can be optimized by the compiler.
- Use final variables when the value may be determined at runtime but should not change after initialization. This is common for instance variables, function-level constants, and values that are set based on calculations during program execution.

# **Dart Number**

> In Dart, numbers are used to represent numeric values. Dart provides two primary numeric data types for working with numbers:

1. **int (Integer)**:

   - The `int` data type is used to represent integers, which are whole numbers, both positive and negative.
   - Dart's `int` type can hold arbitrarily large integers, limited only by system memory.
   - You can perform common integer operations like addition, subtraction, multiplication, and division with `int` values.

   Example:

   ```dart
   int age = 30;
   int population = 1000000;
   ```

2. **double (Floating-Point)**:

   - The `double` data type is used to represent floating-point numbers, which are numbers with decimal points.
   - Dart's `double` type allows for both whole numbers and fractional parts.
   - You can perform operations involving real numbers, such as addition, subtraction, multiplication, division, and more.

   Example:

   ```dart
   double pi = 3.14159;
   double temperature = 25.5;
   ```

Dart also supports various operations and methods for working with numbers, including arithmetic operations (`+`, `-`, `*`, `/`, `%`), comparison operators (`<`, `>`, `<=`, `>=`, `==`, `!=`), and mathematical functions (e.g., `abs()`, `ceil()`, `floor()`, `round()`).

Here are some additional points to consider when working with numbers in Dart:

- Dart's `num` type is a supertype of both `int` and `double`. This means that you can use `num` to represent numbers when you want to work with integers and floating-point values interchangeably.

- Dart supports integer division using the `~/` operator. For example, `5 ~/ 2` yields `2`, as it returns the integer part of the division.

- Dart also provides the `isEven` and `isOdd` properties for `int` values to check whether a number is even or odd, respectively.

- Dart allows you to convert between `int` and `double` using the `.toDouble()` and `.toInt()` methods, respectively.

- Be mindful of the potential loss of precision when converting between `int` and `double`, as double-precision floating-point numbers have limitations in representing some integer values precisely.

- Dart provides mathematical constants like `double.pi` for π and `double.e` for the base of the natural logarithm (e).

Using `int` and `double`, you can work with a wide range of numeric values and perform various mathematical operations in Dart.

# **Dart String**

> In Dart, a `String` is a data type used to represent text and sequences of characters. Dart provides various methods and features for working with strings. Here's an overview of using strings in Dart:

1. **String Declaration**:

   - You can declare a string by enclosing text within either single (`'`) or double (`"`) quotes.
   - Dart doesn't differentiate between single and double quotes for defining strings; you can use either. For example:
     ```dart
     String name = "Alice";
     String message = 'Hello, Dart!';
     ```

2. **String Concatenation**:

   - You can concatenate strings using the `+` operator. This combines two or more strings into a single string.
     ```dart
     String firstName = "John";
     String lastName = "Doe";
     String fullName = firstName + " " + lastName; // Result: "John Doe"
     ```

3. **String Interpolation**:

   - String interpolation is a more concise way to build strings by embedding expressions within a string using `${...}`.
   - Dart evaluates the expressions and includes their values in the resulting string.
     ```dart
     String name = "Alice";
     String greeting = "Hello, $name!"; // Result: "Hello, Alice!"
     ```

4. **String Methods**:

   - Dart provides a variety of string methods to manipulate and query strings, such as:
     - `length`: Returns the length of the string.
     - `toUpperCase()`: Converts the string to uppercase.
     - `toLowerCase()`: Converts the string to lowercase.
     - `substring()`: Extracts a substring from the string.
     - `trim()`: Removes leading and trailing whitespace.
     - `split()`: Splits the string into a list of substrings based on a delimiter.

5. **String Escaping**:

   - You can use the backslash (`\`) to escape special characters within strings. For example, to include a literal double quote within a double-quoted string, use `\"`.
   - Dart also supports escape sequences like `\n` for a newline and `\t` for a tab.

6. **Raw String**:

   - Dart allows you to create raw strings by prefixing a string literal with an `r` character. This prevents escape sequences from being interpreted within the string.
   - Raw strings are useful when working with regular expressions or paths that contain backslashes.

   ```dart
   String path = r'C:\Program Files\Dart\bin'; // Raw string
   ```

7. **String Comparison**:

   - You can compare strings using equality operators (`==` and `!=`) or by using methods like `compareTo()` to perform case-insensitive or case-sensitive comparisons.

8. **Multiline Strings**:

   - Dart allows you to define multiline strings using triple single (`'''`) or triple double (`"""`) quotes. This is useful for representing strings that span multiple lines.

   ```dart
   String multiline = '''
     This is a
     multiline string.
   ''';
   ```

9. **Unicode and Characters**:

   - Dart fully supports Unicode characters, and you can represent characters using Unicode escape sequences like `\u{...}`.

   ```dart
   String unicodeString = "\u{1F60D}"; // Unicode for a smiley face emoji
   ```

# **Dart Lists**

> In Dart, a list is an ordered collection of objects, and it is one of the core data structures for storing multiple values of the same or different types. Dart provides several ways to create and work with lists. Here's an overview of Dart lists:

1. **Creating Lists**:

   - **List Literal**: You can create a list using square brackets `[]` and add elements separated by commas.

     ```dart
     List<int> numbers = [1, 2, 3, 4, 5];
     ```

   - **List Constructor**: You can use the `List` constructor to create a list and initialize it with elements.

     ```dart
     List<String> colors = List<String>.from(['red', 'green', 'blue']);
     ```

   - **Empty List**: You can create an empty list using the `List` constructor without any elements, and then add elements later.

     ```dart
     List<double> temperatures = List<double>();
     temperatures.add(25.5);
     temperatures.add(30.0);
     ```

2. **List Elements**:

   - Lists in Dart can hold elements of the same type or elements of different types.
   - Lists can store various data types, including numbers, strings, objects, and even other lists.

3. **Accessing Elements**:

   - You can access elements in a list using square brackets and a zero-based index.

     ```dart
     List<String> fruits = ['apple', 'banana', 'cherry'];
     String firstFruit = fruits[0]; // Accesses the first element (apple).
     ```

4. **List Operations**:

   - You can perform various operations on lists, including adding, removing, and updating elements.
   - Common list operations include:
     - `add()`: Add an element to the end of the list.
     - `remove()`: Remove a specific element.
     - `insert()`: Insert an element at a specified index.
     - `addAll()`: Add all elements from another list.
     - `removeAt()`: Remove an element at a specific index.

   ```dart
   List<int> numbers = [1, 2, 3];
   numbers.add(4); // Adds 4 to the end.
   numbers.remove(2); // Removes the element 2.
   numbers.insert(1, 5); // Inserts 5 at index 1.
   ```

5. **List Properties**:

   - Dart lists have several properties and methods for working with lists. Some common properties include:
     - `length`: Returns the number of elements in the list.
     - `isEmpty`: Returns `true` if the list is empty.
     - `isNotEmpty`: Returns `true` if the list is not empty.

   ```dart
   List<String> countries = ['USA', 'Canada', 'Mexico'];
   int count = countries.length; // Returns 3.
   bool empty = countries.isEmpty; // Returns false.
   ```

6. **Iterating Through a List**:

   - You can use loops like `for-in` or `forEach` to iterate through the elements of a list.

   ```dart
   List<int> numbers = [1, 2, 3, 4, 5];
   for (int number in numbers) {
     print(number);
   }
   ```

7. **List Operators**:

   - Dart provides operators like `+` for concatenating lists and `[]` for accessing elements.

   ```dart
   List<int> list1 = [1, 2];
   List<int> list2 = [3, 4];
   List<int> combinedList = list1 + list2; // Concatenates lists.
   int element = list1[0]; // Accesses the first element.
   ```

8. **List Generics**:

   - You can specify the type of elements a list can contain using generics.

   ```dart
   List<String> names = ['Alice', 'Bob', 'Charlie'];
   ```

Dart lists are versatile and commonly used for storing and manipulating collections of data, making them an essential data structure in Dart programming.

# **Dart Sets**

> In Dart, a `Set` is a collection that represents an unordered group of unique objects. Unlike a `List`, which allows duplicate elements and maintains their order, a `Set` enforces uniqueness and does not guarantee any specific order of its elements. Here's an overview of working with sets in Dart:

1. **Creating a Set**:

   - You can create a set in Dart using a set literal, which is enclosed in curly braces `{}`. Each element in the set is separated by commas.

   ```dart
   Set<String> colors = {'red', 'green', 'blue'};
   ```

   - You can also create an empty set using the `Set` constructor and add elements to it.

   ```dart
   Set<int> numbers = Set<int>();
   numbers.add(1);
   numbers.add(2);
   numbers.add(3);
   ```

2. **Set Properties and Methods**:

   - Dart sets have several methods and properties for working with sets. Some common ones include:
     - `add(element)`: Adds an element to the set if it doesn't already exist.
     - `remove(element)`: Removes a specific element from the set.
     - `contains(element)`: Checks if the set contains a specific element.
     - `length`: Returns the number of elements in the set.
     - `isEmpty`: Returns `true` if the set is empty.
     - `isNotEmpty`: Returns `true` if the set is not empty.

   ```dart
   Set<String> colors = {'red', 'green', 'blue'};
   colors.add('yellow');
   colors.remove('green');
   bool containsBlue = colors.contains('blue');
   int numColors = colors.length;
   ```

3. **Iterating Through a Set**:

   - You can use iteration techniques to loop through the elements of a set, such as a `for-in` loop or the `forEach` method.

   ```dart
   Set<int> numbers = {1, 2, 3, 4, 5};
   numbers.forEach((int number) {
     print(number);
   });
   ```

4. **Converting a List to a Set**:

   - You can convert a `List` to a `Set` to remove duplicates and enforce uniqueness.

   ```dart
   List<int> numbersList = [1, 2, 3, 2, 4, 5, 4];
   Set<int> uniqueNumbers = Set<int>.from(numbersList);
   ```

5. **Set Operations**:

   - Sets support common set operations, such as union, intersection, and difference, using methods like `union()`, `intersection()`, and `difference()`.

   ```dart
   Set<int> set1 = {1, 2, 3, 4};
   Set<int> set2 = {3, 4, 5, 6};
   Set<int> unionSet = set1.union(set2); // Union of set1 and set2.
   Set<int> intersectionSet = set1.intersection(set2); // Intersection of set1 and set2.
   Set<int> differenceSet = set1.difference(set2); // Difference of set1 and set2.
   ```

# **Dart Map**

In Dart, a `Map` is a collection of key-value pairs, where each key is unique, and it maps to a corresponding value. Maps are also known as associative arrays, dictionaries, or hash tables in other programming languages. Dart provides a convenient way to work with maps. Here's an overview of working with maps in Dart:

1. **Creating a Map**:

   - You can create a map in Dart using a map literal, which is enclosed in curly braces `{}`. Each key-value pair is separated by a colon `:`.

   ```dart
   Map<String, int> scores = {'Alice': 95, 'Bob': 89, 'Charlie': 78};
   ```

   - You can also create an empty map using the `Map` constructor and add key-value pairs to it.

   ```dart
   Map<String, double> prices = Map<String, double>();
   prices['apple'] = 1.99;
   prices['banana'] = 0.99;
   prices['cherry'] = 2.49;
   ```

2. **Map Properties and Methods**:

   - Dart maps have several methods and properties for working with maps. Some common ones include:
     - `length`: Returns the number of key-value pairs in the map.
     - `isEmpty`: Returns `true` if the map is empty.
     - `isNotEmpty`: Returns `true` if the map is not empty.
     - `keys`: Returns an iterable of the map's keys.
     - `values`: Returns an iterable of the map's values.

   ```dart
   Map<String, int> scores = {'Alice': 95, 'Bob': 89, 'Charlie': 78};
   int numScores = scores.length;
   bool hasScores = scores.isNotEmpty;
   Iterable<String> playerNames = scores.keys;
   Iterable<int> playerScores = scores.values;
   ```

3. **Accessing Values**:

   - You can access values in a map using the keys. Provide the key within square brackets (`[]`) to retrieve the associated value.

   ```dart
   Map<String, double> prices = {'apple': 1.99, 'banana': 0.99, 'cherry': 2.49};
   double applePrice = prices['apple'];
   ```

4. **Updating Values**:

   - To update the value associated with a key in a map, use the key to access the element and assign a new value to it.

   ```dart
   Map<String, int> scores = {'Alice': 95, 'Bob': 89, 'Charlie': 78};
   scores['Bob'] = 92; // Update Bob's score.
   ```

5. **Iterating Through a Map**:

   - You can use iteration techniques like a `for-in` loop or the `forEach` method to loop through the key-value pairs of a map.

   ```dart
   Map<String, int> scores = {'Alice': 95, 'Bob': 89, 'Charlie': 78};
   scores.forEach((key, value) {
     print('$key: $value');
   });
   ```

6. **Removing a Key-Value Pair**:

   - You can remove a key-value pair from a map using the `remove(key)` method, where `key` is the key you want to remove.

   ```dart
   Map<String, double> prices = {'apple': 1.99, 'banana': 0.99, 'cherry': 2.49};
   prices.remove('banana');
   ```

# **Differences Between Dart Sets , List and Map**

Dart provides three primary collection types: `Set`, `List`, and `Map`, each with distinct characteristics and use cases. Here are the key differences between `Set`, `List`, and `Map` in Dart:

**Set**:

1. **Uniqueness**:

   - A `Set` is an unordered collection that enforces uniqueness. Each element can only appear once in the set.

2. **Order**:

   - Sets do not guarantee any specific order for their elements. Elements are stored in an unordered manner.

3. **Access**:

   - Sets do not support direct access to elements by index, as they are unordered. You typically use iteration to find a specific element.

4. **Use Cases**:
   - Sets are suitable when you need to ensure that elements are unique and the order of elements doesn't matter.
   - They are commonly used for quickly checking for the presence of an element without allowing duplicates.

**List**:

1. **Order**:

   - A `List` is an ordered collection of elements, and each element is associated with an index, starting from 0. Lists maintain their insertion order.

2. **Duplicates**:

   - Lists can contain duplicate elements. The same value can appear multiple times in a list.

3. **Access**:

   - You can access elements in a list by their index using square brackets (`[]`).

4. **Use Cases**:
   - Lists are suitable when you need to maintain the order of elements, and duplicates are allowed, or when you want to access items by their position in the list.
   - They are commonly used for maintaining a specific order of elements.

**Map**:

1. **Key-Value Pairs**:

   - A `Map` is a collection of key-value pairs, where each key is unique and maps to a corresponding value.

2. **Access**:

   - You can access values in a map using keys. Provide the key within square brackets (`[]`) to retrieve the associated value.

3. **Use Cases**:
   - Maps are suitable when you need to associate data with specific keys. They are commonly used for representing relationships between values, such as dictionaries, configuration settings, or user profiles.
   - They allow for quick lookup of values based on specific keys.

In summary, here are the primary distinctions:

- Use a `Set` when you need to ensure elements are unique, and the order of elements doesn't matter. Sets are ideal for membership tests without duplicates.

- Use a `List` when you need to maintain the order of elements, and duplicates are allowed. Lists are suitable for accessing items by their position in the list.

- Use a `Map` when you need to associate data with specific keys and want to quickly look up values based on those keys. Maps are commonly used for key-value relationships.

# **Dart Enumeratio**

In Dart, enumerations (enums) allow you to define a collection of related constants or symbolic names. Enums provide a way to represent a set of discrete values, making your code more readable and less error-prone. Here's how you can define and use enums in Dart:

**Defining an Enum**:
To define an enumeration, use the `enum` keyword followed by the enum's name. Inside the enum, you list the constant values that the enum can represent.

```dart
enum Color {
  red,
  green,
  blue,
  yellow,
  // You can define more constants as needed.
}
```

In this example, the `Color` enum defines four constants: `red`, `green`, `blue`, and `yellow`.

**Using Enums**:
You can use enum values to represent specific states or options in your code. Enum values are accessed using the enum name followed by a dot notation:

```dart
Color selectedColor = Color.blue;
```

Enums are often used in scenarios where you have a fixed set of options or states. For example, you might use an enum to represent the days of the week:

```dart
enum Day {
  monday,
  tuesday,
  wednesday,
  thursday,
  friday,
  saturday,
  sunday,
}
```

And you can use the `Day` enum to work with days of the week:

```dart
Day today = Day.wednesday;

if (today == Day.saturday || today == Day.sunday) {
  print("It's the weekend!");
} else {
  print("It's a weekday.");
}
```
