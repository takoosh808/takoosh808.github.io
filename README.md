# Ruby #

<br/>

## What is Ruby?
<br/>

Ruby is a simple, dynamic language that's easy to read, due to its english-like structure. Ruby also takes advantage of a diverse and easy to use package system known as Gems. This allows for a flexible system that has add-ons that can easily extend the usage of programs.

<br/>

## Key Traits

1. Interpreter - Doesn't use compiler, just run the code
2. Object Oriented - Everything is an object
3. Readable Syntax- Near English syntax
4. Open Source - Free to use

<br/>

## Gems<br/>
**Common Gems**

1. Rails - Web framework
2. Rspec - Testing framework
3. Sinatra - Web framework
4. Devise - User authentication system

**Steps to Use Gems**
1. Install using 'Gem install __ '
2. Use in code using 'require __'

<br/>

## Data Types<br/>

**Integer**
- Definition: Whole Numbers
- EX: 42<br/>

**Float**
- Definition: Decimal Numbers
- EX: 3.14<br/>

**String**
- Definition: Objects of class strings, group of letters that represent a word or sentence.
- EX: "String"<br/>

**Symbol**
- Definition: Lightweight strings, preceded by colon.
- EX: :sk => "GeeksForGeeks"<br/>

**Boolean**
- Definition: Either true or false, lightweight, only stores one bit
- EX: True<br/>

**Nil**
- Definition: Null value for Ruby
- EX: Nil<br/>

**Array**
- Definition: Stores a list of data, data separate by a comma, can store any type of data
- EX: [1,2,3]<br/>

**Hash**
- Definition: Key-Value storage, assigned by =>
- EX: {"Fruit" => "Banana", "Vegetable" => "Cucumber"}<br/>


## Operations and Control Structures<br/>

**Operations**<br/>

**Range Operations**
- Definition: Allows for easy shorthand for repetitive tasks
- EX: ('a'..'e').to_a => ["a", "b", "c", "d", "e"]<br/>

**Method Missing**
- Definition: Placeholder method to display what was trying to be called<br/>

**Monkey Patching**
- Definition: Open existing classes and modify or add methods to class
- EX: Adding a method "shout" to String class to convert all letters in String to uppercase<br/>

**Begin/Rescue**
- Definition: Error Handling
- EX: Begin 1/0 Rescue ZeroDivisionError => e puts "Error: #{e.message}"

**Control Structures**<br/>

**IF/ELIF/ELSE**
- Definition: Three tiered control structure to handle cases that land in specific criteria
- EX: puts "X is 10" if x == 10<br/>

**Unless**
- Definition: Opposite of if
- EX: puts "X is 5" unless x == 5<br/>

**While/Until**
- Definition: Does an action until criteria is met
- EX: while i < 5 puts i i += 1<br/>

**Times/Each/Upto/Downto**
- Definition: Repeats a specific action like a for loop until a criteria is met
- EX: 5.downto(1)<br/>

**Case**
- Definition: Like switch statements, when matching certain criteria, do an action
- EX: case day when "monday" puts "Week Started!" when "friday" puts "Week Ended!"<br/>

**Controls**
1. Break: Exit loop early
2. Next: Skip to next iteration
3. Redo: Restart iteration<br/>

## Functions <br/>
**Format**
1. Define using def
2. Auto returns
3. Input in argument input<br/>

**Scoping**
- Lexical Scoping
- Depends on where you write the code, rather than when it is called<br/>
**Types**
1. Local: inside a method or code block
2. Instance(@): inside class or object
3. Class(@@): shared across instances
4. Global($): throughout whole file<br/>

**First-Class**
- Definition: Pass methods as variables
- EX: def doTwice(action) action.call action.call end

**Closure**
- Functions that remember scope even after scope is gone
1. Blocks
- Method called with parameter, parameter is remember outside of scope
2. Proc
- Separate method to keep scope
- EX: Proc.new { puts "Hi!" }
3. Lambda
- Stricter proc, keeps just lambda part of function out of scope
- EX: -> {count += 1}<br/>

## Custom Datatypes<br/>
**Struct**
- Definition: Group data together without making a class
- EX: Person = Struct.new(:name, :age)<br/>

**Classes**
- Definition: Custom classes with methods, getters, setters, and attributes
- attr_accessor for getters and setters<br/>

## Cool Things In Ruby<br/>
**Everything is an object!**
- Literally everything is an object in ruby and therefore has methods<br/>

**Flexible Syntax**
- Optional parenthesis and english like syntax
- EX: puts "hello" and puts ("hello") result in the same thing<br/>

**Keyword Arguments**
- Allows for defaults and makes input parameters very readable<br/>

**Chain Control Statements**
- EX: puts "It's true!" if condition raise "Nope" unless valid?<br/>

**LazyLoad Modules**
- Load code only when needed
- EX: autoload :MyModule, 'my_module.rb'<br/>

**Refinements(Scoped Monkey Patching)**
- Scoped modification of classes, uses modules to keep scope safe<br/>

**Try Ruby**
- Free and easy to use website to try ruby in [browser](https://try.ruby-lang.org/)<br/>

## Hello World Demo<br/>
[**Video**](https://github.com/takoosh808/takoosh808.github.io/blob/main/Screen%20Recording%202025-04-18%20221544.mp4)

