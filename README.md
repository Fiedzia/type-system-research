This is small collection of links related to research about static vs dynamic typing.

Main point of this for me is to figure out not "*which is better*",
but "*does one contribute more then the other to software quality*".

Also those materials are really hard to find unless you know what exactly
are you looking for. PR's with more links to reasearch are welcome.

1. "**An experiment about static and dynamic type systems**", Stefan Hanenberg
    
    Two groups of students implement java parser, one using language with static, another with dynamic type system.
    
    Conclusion: "We measured two different points in the development: first, the fevelopment time until a minimal scanner has been implemented, and second the quality of the resulting software measured by the number of succesful testcases fullfilled by the parser. In none of there measured points the use of static type systems turned out to have a significan positive impact."
    
    Source: https://courses.cs.washington.edu/courses/cse590n/10au/hanenberg-oopsla2010.pdf

2.  "**The Unreasonable Effectiveness of Dynamic Typing for Practical Programs**", Robert Smallshire

    Anylysis of errors related to static vs dynamic type systems.

    Conclusion: Only about 3% of errors is related to type system issues, other factors are much more influential
  
    Source: https://vimeo.com/74354480


3. (opinion, pointing to value of other factors) "**Why do dynamic languages make it difficult to maintain large codebases?**", Eric Lippert 

    Conclusion: "it is not merely the dynamic nature of typing that increases the cost of maintaining a large codebase. That alone does increase costs, but that is far from the whole story. I could design you a language that was dynamically typed but also had namespaces, modules, inheritance, libraries, private members, and so on—in fact, C# 4 is such a language—and such a language would be both dynamic and highly suited for programming in the large."

    Source: http://arstechnica.com/information-technology/2014/06/why-do-dynamic-languages-make-it-difficult-to-maintain-large-codebases/

4. "**Static Typing Where Possible, Dynamic Typing When Needed: The End of the Cold War Between Programming Language**", Erik Meijer and Peter Drayton

    Overview of reasons for which developers want static and dynamic typing.

    Conclusion: "Dealing with uncertain assumptions, dynamism and (unexepected) change is becoming increasingly important in a loosely couple distributed world. Instead of hammering on the differences between dynamically and statically typed languages, we should instead strive for a peaceful integration of static and dynamic
aspect in the same language. Static typing where possible, dynamic typing when needed!"
