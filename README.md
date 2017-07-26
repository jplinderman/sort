# sort
Stuff related to sorting algorithms

I have been creating or modifying internal and external sorting programs for decades. Most have been unexceptional, although they usually fixed bugs or removed artificial limitations (like the 512-byte record length limitation on the 1970s-era UNIX sort). A couple have been pretty darn good, usually because they built on the work of people who know a lot about sorting, like the original author of the UNIX sort, or Peter McIlroy's

    "Optimistic Sorting and Information Theoretic Complexity"
    SODA (Fourth Annual ACM/SIAM Symposium on Discrete Algorithms),
    pp 467-474, Austin, Texas, 25-27 January 1993.
   
With Peter's help, I integrated that sort into Perl's builtin sort function, where, unlike the previous quicksort implementation, it was stable, and absolutely positively could not go quadratic. I have since tinkered with the Perl sort code, but that's the subject of a different README.

I'm just getting started with github, so I'm not sure how this repository will be used. Possibly just as a place to drop files that I want to share with others.
