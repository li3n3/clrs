Exercises:
1.1-1:
* Give a real-world example that requires sorting or a real-world example that
  requires computing a convex hull.
  * Sorting: a list of library books that need to be shelved according to some
    criterion (e.g. Dewey Decimal number, author, title).
    A convex hull would be a really interesting way of cat-herding actual cats.
    It's more or less just herding a bunch of points...

1.1-2:
* Other than speed, what other measures of efficiency might one use in a
  real-world setting?
  * Ease of use. Number of lines. Ease of translation into other formats.
    Reliability.

1.1-3:
* Select a data structure that you have seen previously, and discuss its
  strengths and limitations.
  * Dictionaries are great for reliably getting values out, given a key, and
    doing so reasonably efficiently (I think). They're terrible, however, at
    giving information back in order. If sorting is needed, you're gonna need to
    sort the whole dictionary, because it doesn't do it on its own.

1.1-4:
* How are the shortest-path and traveling-salesman problems given above similar?
  How are they different?
  * Both involve optimizing for least distance travelled. The shortest-path
    problem, however, involves only two points (the origin and destination
    points). The traveling-salesman problem involves a theoretically (though not
    practically) infinite set of points. The former also isn't NP-complete, while
    the latter is.

1.1-5:
* Come up with a real-world problem in which only the best solution will do. Then
  come up with one in which a solution that is "approximately" the best is good
  enough.
  * Only the best: buying a given product for the best price.
  * Approximately the best is good enough: a bridge (past a certain safety
    level). Finding the optimum amount of sleep to get each night.

******

1.2-3
* Give an example of an application that requires algorithmic content at the
  application level, and discuss the function of the algorithms involved.
  * One example would be a search engine: some algorithms would help find
    relevant web pages efficiently, while others would help surface the most
    "relevant" or "best" pages to the top of the list (even if it was something
    naïve like age of page, or wordcount of page).

1.2-2
* Suppose we are comparing implementations of insertion sort and merge sort on
  the same machine. For inputs of size n, insertion sort runs in 8n^2 steps,
  while merge sort runs in 64n lg n steps. For which values of n does insertion
  sort beat merge sort?
  * TODO: look up the math of this again; it's been years and years

1.2-3
* What is the smallest value of n such that an algorithm whose running time is
  100n^2 runs faster than an algorithm whose running time is 2^n on the same
  machine?
  * Also gonna need to review some math here.
