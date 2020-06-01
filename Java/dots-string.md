# How many dots there are in that String?
Today I needed to limit the number of dots accepted on the screen of my calculator project, the calculator must only accept 1 dot.

The solution that I found is rather simple:

Just use the indexOf() method, that returns the position of the first occurrence of a specified character(s) in a string.

There are 4 types of index method:
```
public int indexOf(String str)
public int indexOf(String str, int fromIndex)
public int indexOf(int char)
public int indexOf(int char, int fromIndex)
```
- str -------> the string to search for.
- fromIndex -> Position index to start searching.
- char ------> A single characte.

This method returns an int value, that is the index of the first occurrence of the character in the string, or -1 if it never occurs.

my implementations was like this, when I press '.' button on calculator a method is called and this comparassion is perfomed:
```
if(string.indexOf('.', string.indexOf('.') + 0) != -1) {
            
            System.out.println("Beep!! You cant do it!");
}else{

            // prints '.' on screen

}
```
