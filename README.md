# Templating lab

Create the following template functions.

vec_fill(T elem)

fills a 10 element vector with elem, elem + 1, elem + 2, etc.

returns the vector

order(T& a, T& b, T& c)

Makes a hold the largest value from the arguments, b hold the second largest value, and c hold the third largest value.

search(T begin, T end, int elem)

Uses iterators to search an arbitrary container of integers.

Write assert tests for each of these functions using at least three different template instantiations for each.
## TPQs
Investigate the standard library search function. Look at the various overloads and read what they do. The very first will be the simplest ;)

      a) Do the template parameter lists match the one you made? What makes them different?

      b) How does this function work differently from yours?

      c) Why do you think they made it work like this? Do you prefer this design?
