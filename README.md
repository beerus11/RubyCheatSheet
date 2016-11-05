Ruby CheatSheet!
===================

# Table of Contents
1. [Strings](#Strings)
2. [Arrays](#arrays)
3. [Loops](#loops)
4. [Methods](#methods)
5. [Class](#class)
6. [Exception Handling](#exception)
7. [File Handling](#file)
8. [MultiTHreading](#thread)
9. [Web Programming](#web)
10. [Miscellaneous](#misc)

##Strings
```
#Expression Substitution
x,y,z=12,36,72
puts "The value of x is  #{x}."
puts "The value of x+y is #{x+y}."
puts "The value of x+y+z is #{x+y+z}."

#String BuiltIn Methods
myStr = String.new("THIS IS TEST STRING")

#Change case
puts myStr.downcase
puts myStr.upcase
puts myStr.swapcase

first_name="Anurag"
last_name="Goel"
full_name="#{first_name} #{last_name}"
puts full_name

#Print string size
puts full_name.size
#Count Characters in String
puts full_name.count("Aa")

puts full_name.start_with?("Anurag")

puts "Index : "+full_name.index("Goel").to_s

#Strip String
string ="   Anurag Goel  "
puts string.lstrip
puts string.rstrip
puts string.strip

#String Adjust
puts full_name.rjust(25,".")
puts full_name.ljust(25,".")
puts full_name.center(25,".")

#Chop String
puts full_name.chop
puts full_name.chomp('el')

#split string
puts full_name.split("")
puts full_name.split("a")

#Reverse String
puts full_name.reverse

```
