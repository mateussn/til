# Formatting a number

Today I was working on a calculator APP and I needed to format the number printed on the screen, so I did a little search and found
DecimalFormat class. To use that class you just need to create an object and call format() method.

- Example:

```
float randomNumber = 4.143679053;
DecimalFormat decimalFormat = new DecimalFormat("#.000");
System.out.println(decimalFormat.format(randomNumber));
```

- Output: 4.143

So in the code snippet ("#.000") the zeros represents how many numbers of precision.

But in some cases you don't want to show additional numbers like:

- Output: 0.400

So you can use the hash instead of zeros, like that ("#.###"), the result:

- Output: 0.4
