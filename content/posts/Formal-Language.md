+++
date = '2025-01-09T14:51:25-05:00'
title = 'Formal Language'
+++

# Formal language
From Wikipedia, the free encyclopedia

This article is about a technical term in mathematics and computer science. For any formal type of language usage, see [Literary language](https://en.wikipedia.org/wiki/Literary_language "Literary language"). For studies about natural languages, see [Formal semantics (natural language)](https://en.wikipedia.org/wiki/Formal_semantics_\(natural_language\) "Formal semantics (natural language)").

[![](https://upload.wikimedia.org/wikipedia/commons/a/aa/Syntax_tree.svg)](https://en.wikipedia.org/wiki/File:Syntax_tree.svg)

Structure of the syntactically well-formed, although thoroughly nonsensical, English sentence, _"Colorless green ideas sleep furiously"_ ([historical example](https://en.wikipedia.org/wiki/Colorless_green_ideas_sleep_furiously "Colorless green ideas sleep furiously") from [Chomsky](https://en.wikipedia.org/wiki/Chomsky "Chomsky") 1957)

In [logic](https://en.wikipedia.org/wiki/Logic "Logic"), [mathematics](https://en.wikipedia.org/wiki/Mathematics "Mathematics"), [computer science](https://en.wikipedia.org/wiki/Computer_science "Computer science"), and [linguistics](https://en.wikipedia.org/wiki/Linguistics "Linguistics"), a **formal language** consists of [words](https://en.wikipedia.org/wiki/Word "Word") whose [letters](https://en.wikipedia.org/wiki/Symbol_\(formal\) "Symbol (formal)") are taken from an [alphabet](https://en.wikipedia.org/wiki/Alphabet_\(formal_languages\) "Alphabet (formal languages)") and are [well-formed](https://en.wikipedia.org/wiki/Well-formedness "Well-formedness") according to a specific set of rules called a [formal grammar](https://en.wikipedia.org/wiki/Formal_grammar "Formal grammar").

The alphabet of a formal language consists of symbols, letters, or [tokens](https://en.wikipedia.org/wiki/Type%E2%80%93token_distinction "Type–token distinction") that concatenate into [strings](https://en.wikipedia.org/wiki/String_\(computer_science\) "String (computer science)") called words.[\[1\]](#cite_note-1) Words that belong to a particular formal language are sometimes called _well-formed words_ or _[well-formed formulas](https://en.wikipedia.org/wiki/Well-formed_formula "Well-formed formula")_. A formal language is often defined by means of a [formal grammar](https://en.wikipedia.org/wiki/Formal_grammar "Formal grammar") such as a [regular grammar](https://en.wikipedia.org/wiki/Regular_grammar "Regular grammar") or [context-free grammar](https://en.wikipedia.org/wiki/Context-free_grammar "Context-free grammar"), which consists of its [formation rules](https://en.wikipedia.org/wiki/Formation_rule "Formation rule").

In computer science, formal languages are used, among others, as the basis for defining the grammar of [programming languages](https://en.wikipedia.org/wiki/Programming_language "Programming language") and formalized versions of subsets of natural languages, in which the words of the language represent concepts that are associated with meanings or [semantics](https://en.wikipedia.org/wiki/Semantics "Semantics"). In [computational complexity theory](https://en.wikipedia.org/wiki/Computational_complexity_theory "Computational complexity theory"), [decision problems](https://en.wikipedia.org/wiki/Decision_problem "Decision problem") are typically defined as formal languages, and [complexity classes](https://en.wikipedia.org/wiki/Complexity_class "Complexity class") are defined as the sets of the formal languages that can be [parsed by machines](https://en.wikipedia.org/wiki/Parsing "Parsing") with limited computational power. In [logic](https://en.wikipedia.org/wiki/Logic "Logic") and the [foundations of mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics "Foundations of mathematics"), formal languages are used to represent the syntax of [axiomatic systems](https://en.wikipedia.org/wiki/Axiomatic_system "Axiomatic system"), and [mathematical formalism](https://en.wikipedia.org/wiki/Formalism_\(philosophy_of_mathematics\) "Formalism (philosophy of mathematics)") is the philosophy that all of mathematics can be reduced to the syntactic manipulation of formal languages in this way.

The field of **formal language theory** studies primarily the purely [syntactic](https://en.wikipedia.org/wiki/Syntactic "Syntactic") aspects of such languages—that is, their internal structural patterns. Formal language theory sprang out of linguistics, as a way of understanding the syntactic regularities of [natural languages](https://en.wikipedia.org/wiki/Natural_language "Natural language").



In the 17th century, [Gottfried Leibniz](https://en.wikipedia.org/wiki/Gottfried_Leibniz "Gottfried Leibniz") imagined and described the [characteristica universalis](https://en.wikipedia.org/wiki/Characteristica_universalis "Characteristica universalis"), a universal and formal language which utilised [pictographs](https://en.wikipedia.org/wiki/Pictographs "Pictographs"). Later, [Carl Friedrich Gauss](https://en.wikipedia.org/wiki/Carl_Friedrich_Gauss "Carl Friedrich Gauss") investigated the problem of [Gauss codes](https://en.wikipedia.org/wiki/Gauss_notation "Gauss notation").[\[2\]](#cite_note-2)

[Gottlob Frege](https://en.wikipedia.org/wiki/Gottlob_Frege "Gottlob Frege") attempted to realize Leibniz's ideas, through a notational system first outlined in _[Begriffsschrift](https://en.wikipedia.org/wiki/Begriffsschrift "Begriffsschrift")_ (1879) and more fully developed in his 2-volume Grundgesetze der Arithmetik (1893/1903).[\[3\]](#cite_note-3) This described a "formal language of pure language."[\[4\]](#cite_note-Herken1279-4)

In the first half of the 20th century, several developments were made with relevance to formal languages. [Axel Thue](https://en.wikipedia.org/wiki/Axel_Thue "Axel Thue") published four papers relating to words and language between 1906 and 1914. The last of these introduced what [Emil Post](https://en.wikipedia.org/wiki/Emil_Post "Emil Post") later termed 'Thue Systems', and gave an early example of an [undecidable problem](https://en.wikipedia.org/wiki/Undecidable_problem "Undecidable problem").[\[5\]](#cite_note-5) Post would later use this paper as the basis for a 1947 proof "that the word problem for semigroups was recursively insoluble",[\[6\]](#cite_note-6) and later devised the [canonical system](https://en.wikipedia.org/wiki/Post_canonical_system "Post canonical system") for the creation of formal languages.

In 1907, [Leonardo Torres Quevedo](https://en.wikipedia.org/wiki/Leonardo_Torres_Quevedo "Leonardo Torres Quevedo") introduced a formal language for the description of mechanical drawings (mechanical devices), in [Vienna](https://en.wikipedia.org/wiki/Vienna "Vienna"). He published "Sobre un sistema de notaciones y símbolos destinados a facilitar la descripción de las máquinas" ("On a system of notations and symbols intended to facilitate the description of machines").[\[7\]](#cite_note-7) [Heinz Zemanek](https://en.wikipedia.org/wiki/Heinz_Zemanek "Heinz Zemanek") rated it as an equivalent to a [programming language](https://en.wikipedia.org/wiki/Programming_language "Programming language") for the numerical control of machine tools.[\[8\]](#cite_note-Bruderer-8)

[Noam Chomsky](https://en.wikipedia.org/wiki/Noam_Chomsky "Noam Chomsky") devised an abstract representation of formal and natural languages, known as the [Chomsky hierarchy](https://en.wikipedia.org/wiki/Chomsky_hierarchy "Chomsky hierarchy").[\[9\]](#cite_note-9) In 1959 [John Backus](https://en.wikipedia.org/wiki/John_Backus "John Backus") developed the Backus-Naur form to describe the syntax of a high level programming language, following his work in the creation of [FORTRAN](https://en.wikipedia.org/wiki/FORTRAN "FORTRAN").[\[10\]](#cite_note-10) [Peter Naur](https://en.wikipedia.org/wiki/Peter_Naur "Peter Naur") was the secretary/editor for the ALGOL60 Report in which he used [Backus–Naur form](https://en.wikipedia.org/wiki/Backus%E2%80%93Naur_form "Backus–Naur form") to describe the Formal part of ALGOL60.

Words over an alphabet
----------------------



An _alphabet_, in the context of formal languages, can be any [set](https://en.wikipedia.org/wiki/Set_\(mathematics\) "Set (mathematics)"); its elements are called _letters_. An alphabet may contain an [infinite](https://en.wikipedia.org/wiki/Countable_set "Countable set") number of elements;[\[note 1\]](#cite_note-11) however, most definitions in formal language theory specify alphabets with a finite number of elements, and many results apply only to them. It often makes sense to use an [alphabet](https://en.wikipedia.org/wiki/Alphabet "Alphabet") in the usual sense of the word, or more generally any finite [character encoding](https://en.wikipedia.org/wiki/Character_encoding "Character encoding") such as [ASCII](https://en.wikipedia.org/wiki/ASCII "ASCII") or [Unicode](https://en.wikipedia.org/wiki/Unicode "Unicode").

A **word** over an alphabet can be any finite sequence (i.e., [string](https://en.wikipedia.org/wiki/String_\(computer_science\) "String (computer science)")) of letters. The set of all words over an alphabet Σ is usually denoted by Σ\* (using the [Kleene star](https://en.wikipedia.org/wiki/Kleene_star "Kleene star")). The length of a word is the number of letters it is composed of. For any alphabet, there is only one word of length 0, the _empty word_, which is often denoted by e, ε, λ or even Λ. By [concatenation](https://en.wikipedia.org/wiki/Concatenation "Concatenation") one can combine two words to form a new word, whose length is the sum of the lengths of the original words. The result of concatenating a word with the empty word is the original word.

In some applications, especially in [logic](https://en.wikipedia.org/wiki/Logic "Logic"), the alphabet is also known as the _vocabulary_ and words are known as _formulas_ or _sentences_; this breaks the letter/word metaphor and replaces it by a word/sentence metaphor.

A formal language _L_ over an alphabet Σ is a [subset](https://en.wikipedia.org/wiki/Subset "Subset") of Σ\*, that is, a set of words over that alphabet. Sometimes the sets of words are grouped into expressions, whereas rules and constraints may be formulated for the creation of 'well-formed expressions'.

In computer science and mathematics, which do not usually deal with [natural languages](https://en.wikipedia.org/wiki/Natural_language "Natural language"), the adjective "formal" is often omitted as redundant.

While formal language theory usually concerns itself with formal languages that are described by some syntactic rules, the actual definition of the concept "formal language" is only as above: a (possibly infinite) set of finite-length strings composed from a given alphabet, no more and no less. In practice, there are many languages that can be described by rules, such as [regular languages](https://en.wikipedia.org/wiki/Regular_language "Regular language") or [context-free languages](https://en.wikipedia.org/wiki/Context-free_language "Context-free language"). The notion of a [formal grammar](https://en.wikipedia.org/wiki/Formal_grammar "Formal grammar") may be closer to the intuitive concept of a "language", one described by syntactic rules. By an abuse of the definition, a particular formal language is often thought of as being accompanied with a formal grammar that describes it.

The following rules describe a formal language L over the alphabet Σ = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, +, =}:

*   Every nonempty string that does not contain "+" or "=" and does not start with "0" is in L.
*   The string "0" is in L.
*   A string containing "=" is in L if and only if there is exactly one "=", and it separates two valid strings of L.
*   A string containing "+" but not "=" is in L if and only if every "+" in the string separates two valid strings of L.
*   No string is in L other than those implied by the previous rules.

Under these rules, the string "23+4=555" is in L, but the string "=234=+" is not. This formal language expresses [natural numbers](https://en.wikipedia.org/wiki/Natural_number "Natural number"), well-formed additions, and well-formed addition equalities, but it expresses only what they look like (their [syntax](https://en.wikipedia.org/wiki/Syntax "Syntax")), not what they mean ([semantics](https://en.wikipedia.org/wiki/Semantics "Semantics")). For instance, nowhere in these rules is there any indication that "0" means the number zero, "+" means addition, "23+4=555" is false, etc.

For finite languages, one can explicitly enumerate all well-formed words. For example, we can describe a language L as just L = {a, b, ab, cba}. The [degenerate](https://en.wikipedia.org/wiki/Degeneracy_\(mathematics\) "Degeneracy (mathematics)") case of this construction is the **empty language**, which contains no words at all (L = [∅](https://en.wikipedia.org/wiki/%E2%88%85 "∅")).

However, even over a finite (non-empty) alphabet such as Σ = {a, b} there are an infinite number of finite-length words that can potentially be expressed: "a", "abb", "ababba", "aaababbbbaab", .... Therefore, formal languages are typically infinite, and describing an infinite formal language is not as simple as writing _L_ = {a, b, ab, cba}. Here are some examples of formal languages:

*   L = Σ\*, the set of _all_ words over Σ;
*   L = {a}\* = {a_n_}, where _n_ ranges over the natural numbers and "a_n_" means "a" repeated _n_ times (this is the set of words consisting only of the symbol "a");
*   the set of syntactically correct programs in a given programming language (the syntax of which is usually defined by a [context-free grammar](https://en.wikipedia.org/wiki/Context-free_grammar "Context-free grammar"));
*   the set of inputs upon which a certain [Turing machine](https://en.wikipedia.org/wiki/Turing_machine "Turing machine") halts; or
*   the set of maximal strings of [alphanumeric](https://en.wikipedia.org/wiki/Alphanumeric "Alphanumeric") [ASCII](https://en.wikipedia.org/wiki/ASCII "ASCII") characters on this line, i.e.,  
    the set {the, set, of, maximal, strings, alphanumeric, ASCII, characters, on, this, line, i, e}.

Language-specification formalisms
---------------------------------



Formal languages are used as tools in multiple disciplines. However, formal language theory rarely concerns itself with particular languages (except as examples), but is mainly concerned with the study of various types of formalisms to describe languages. For instance, a language can be given as

*   those strings generated by some [formal grammar](https://en.wikipedia.org/wiki/Formal_grammar "Formal grammar");
*   those strings described or matched by a particular [regular expression](https://en.wikipedia.org/wiki/Regular_expression "Regular expression");
*   those strings accepted by some [automaton](https://en.wikipedia.org/wiki/Automata_theory "Automata theory"), such as a [Turing machine](https://en.wikipedia.org/wiki/Turing_machine "Turing machine") or [finite-state automaton](https://en.wikipedia.org/wiki/Finite-state_automaton "Finite-state automaton");
*   those strings for which some [decision procedure](https://en.wikipedia.org/wiki/Decision_procedure "Decision procedure") (an [algorithm](https://en.wikipedia.org/wiki/Algorithm "Algorithm") that asks a sequence of related YES/NO questions) produces the answer YES.

Typical questions asked about such formalisms include:

*   What is their expressive power? (Can formalism _X_ describe every language that formalism _Y_ can describe? Can it describe other languages?)
*   What is their recognizability? (How difficult is it to decide whether a given word belongs to a language described by formalism _X_?)
*   What is their comparability? (How difficult is it to decide whether two languages, one described in formalism _X_ and one in formalism _Y_, or in _X_ again, are actually the same language?).

Surprisingly often, the answer to these decision problems is "it cannot be done at all", or "it is extremely expensive" (with a characterization of how expensive). Therefore, formal language theory is a major application area of [computability theory](https://en.wikipedia.org/wiki/Computability_theory "Computability theory") and [complexity theory](https://en.wikipedia.org/wiki/Computational_complexity_theory "Computational complexity theory"). Formal languages may be classified in the [Chomsky hierarchy](https://en.wikipedia.org/wiki/Chomsky_hierarchy "Chomsky hierarchy") based on the expressive power of their generative grammar as well as the complexity of their recognizing [automaton](https://en.wikipedia.org/wiki/Automata_theory "Automata theory"). [Context-free grammars](https://en.wikipedia.org/wiki/Context-free_grammar "Context-free grammar") and [regular grammars](https://en.wikipedia.org/wiki/Regular_grammar "Regular grammar") provide a good compromise between expressivity and ease of [parsing](https://en.wikipedia.org/wiki/Parsing "Parsing"), and are widely used in practical applications.

Operations on languages
-----------------------



Certain operations on languages are common. This includes the standard set operations, such as union, intersection, and complement. Another class of operation is the element-wise application of string operations.

Examples: suppose ![{\displaystyle L_{1}}](https://wikimedia.org/api/rest_v1/media/math/render/svg/0e79dc1b001f8b923df475ed14de023cbc456013) and ![{\displaystyle L_{2}}](https://wikimedia.org/api/rest_v1/media/math/render/svg/c6a952cfe42c86b7741f55a817da0e251793a358) are languages over some common alphabet ![{\displaystyle \Sigma }](https://wikimedia.org/api/rest_v1/media/math/render/svg/9e1f558f53cda207614abdf90162266c70bc5c1e).

Such [string operations](https://en.wikipedia.org/wiki/String_operations "String operations") are used to investigate [closure properties](https://en.wikipedia.org/wiki/Closure_\(mathematics\) "Closure (mathematics)") of classes of languages. A class of languages is closed under a particular operation when the operation, applied to languages in the class, always produces a language in the same class again. For instance, the [context-free languages](https://en.wikipedia.org/wiki/Context-free_language "Context-free language") are known to be closed under union, concatenation, and intersection with [regular languages](https://en.wikipedia.org/wiki/Regular_language "Regular language"), but not closed under intersection or complement. The theory of [trios](https://en.wikipedia.org/wiki/Cone_\(formal_languages\) "Cone (formal languages)") and [abstract families of languages](https://en.wikipedia.org/wiki/Abstract_family_of_languages "Abstract family of languages") studies the most common closure properties of language families in their own right.[\[11\]](#cite_note-12)


Closure properties of language families ( Op  where both  and  are in the language family given by the column). After Hopcroft and Ullman.

|Operation                            |   |Regular|DCFL|CFL|IND|CSL|recursive|RE |
|-------------------------------------|---|-------|----|---|---|---|---------|---|
|Union                                |   |Yes    |No  |Yes|Yes|Yes|Yes      |Yes|
|Intersection                         |   |Yes    |No  |No |No |Yes|Yes      |Yes|
|Complement                           |   |Yes    |Yes |No |No |Yes|Yes      |No |
|Concatenation                        |   |Yes    |No  |Yes|Yes|Yes|Yes      |Yes|
|Kleene star                          |   |Yes    |No  |Yes|Yes|Yes|Yes      |Yes|
|(String) homomorphism                |   |Yes    |No  |Yes|Yes|No |No       |Yes|
|ε-free (string) homomorphism         |   |Yes    |No  |Yes|Yes|Yes|Yes      |Yes|
|Substitution                         |   |Yes    |No  |Yes|Yes|Yes|No       |Yes|
|Inverse homomorphism                 |   |Yes    |Yes |Yes|Yes|Yes|Yes      |Yes|
|Reverse                              |   |Yes    |No  |Yes|Yes|Yes|Yes      |Yes|
|Intersection with a regular language |   |Yes    |Yes |Yes|Yes|Yes|Yes      |Yes|


### Programming languages



A compiler usually has two distinct components. A [lexical analyzer](https://en.wikipedia.org/wiki/Lexical_analyzer "Lexical analyzer"), sometimes generated by a tool like [`lex`](https://en.wikipedia.org/wiki/Lex_programming_tool "Lex programming tool"), identifies the tokens of the programming language grammar, e.g. [identifiers](https://en.wikipedia.org/wiki/Identifier "Identifier") or [keywords](https://en.wikipedia.org/wiki/Keyword_\(computer_programming\) "Keyword (computer programming)"), numeric and string literals, punctuation and operator symbols, which are themselves specified by a simpler formal language, usually by means of [regular expressions](https://en.wikipedia.org/wiki/Regular_expressions "Regular expressions"). At the most basic conceptual level, a [parser](https://en.wikipedia.org/wiki/Parser "Parser"), sometimes generated by a [parser generator](https://en.wikipedia.org/wiki/Parser_generator "Parser generator") like `[yacc](https://en.wikipedia.org/wiki/Yacc "Yacc")`, attempts to decide if the source program is syntactically valid, that is if it is well formed with respect to the programming language grammar for which the compiler was built.

Of course, compilers do more than just parse the source code – they usually translate it into some executable format. Because of this, a parser usually outputs more than a yes/no answer, typically an [abstract syntax tree](https://en.wikipedia.org/wiki/Abstract_syntax_tree "Abstract syntax tree"). This is used by subsequent stages of the compiler to eventually generate an [executable](https://en.wikipedia.org/wiki/Executable "Executable") containing [machine code](https://en.wikipedia.org/wiki/Machine_code "Machine code") that runs directly on the hardware, or some [intermediate code](https://en.wikipedia.org/wiki/Intermediate_code "Intermediate code") that requires a [virtual machine](https://en.wikipedia.org/wiki/Virtual_machine "Virtual machine") to execute.

### Formal theories, systems, and proofs



[![](https://upload.wikimedia.org/wikipedia/commons/d/da/Formal_languages.svg)](https://en.wikipedia.org/wiki/File:Formal_languages.svg)

This diagram shows the [syntactic](https://en.wikipedia.org/wiki/Syntax_\(logic\) "Syntax (logic)") divisions within a [formal system](https://en.wikipedia.org/wiki/Formal_system "Formal system"). [Strings of symbols](https://en.wikipedia.org/wiki/String_\(computer_science\) "String (computer science)") may be broadly divided into nonsense and [well-formed formulas](https://en.wikipedia.org/wiki/Well-formed_formula "Well-formed formula"). The set of well-formed formulas is divided into [theorems](https://en.wikipedia.org/wiki/Theorem "Theorem") and non-theorems.

In [mathematical logic](https://en.wikipedia.org/wiki/Mathematical_logic "Mathematical logic"), a _formal theory_ is a set of [sentences](https://en.wikipedia.org/wiki/Sentence_\(mathematical_logic\) "Sentence (mathematical logic)") expressed in a formal language.

A _formal system_ (also called a _logical calculus_, or a _logical system_) consists of a formal language together with a [deductive apparatus](https://en.wikipedia.org/wiki/Deductive_apparatus "Deductive apparatus") (also called a _deductive system_). The deductive apparatus may consist of a set of [transformation rules](https://en.wikipedia.org/wiki/Transformation_rule "Transformation rule"), which may be interpreted as valid rules of inference, or a set of [axioms](https://en.wikipedia.org/wiki/Axiom "Axiom"), or have both. A formal system is used to [derive](https://en.wikipedia.org/wiki/Proof_theory "Proof theory") one expression from one or more other expressions. Although a formal language can be identified with its formulas, a formal system cannot be likewise identified by its theorems. Two formal systems ![{\displaystyle {\mathcal {FS}}}](https://wikimedia.org/api/rest_v1/media/math/render/svg/ab025245b89b5d8e91a0f027632b0c1764ab2a9f) and ![{\displaystyle {\mathcal {FS'}}}](https://wikimedia.org/api/rest_v1/media/math/render/svg/23a8dd711a545583eab7b71b7cf80d57ee84344c) may have all the same theorems and yet differ in some significant proof-theoretic way (a formula A may be a syntactic consequence of a formula B in one but not another for instance).

A _formal proof_ or _derivation_ is a finite sequence of well-formed formulas (which may be interpreted as sentences, or [propositions](https://en.wikipedia.org/wiki/Proposition "Proposition")) each of which is an axiom or follows from the preceding formulas in the sequence by a [rule of inference](https://en.wikipedia.org/wiki/Rule_of_inference "Rule of inference"). The last sentence in the sequence is a theorem of a formal system. Formal proofs are useful because their theorems can be interpreted as true propositions.

#### Interpretations and models



Formal languages are entirely syntactic in nature, but may be given [semantics](https://en.wikipedia.org/wiki/Semantics "Semantics") that give meaning to the elements of the language. For instance, in mathematical [logic](https://en.wikipedia.org/wiki/Logic "Logic"), the set of possible formulas of a particular logic is a formal language, and an [interpretation](https://en.wikipedia.org/wiki/Interpretation_\(logic\) "Interpretation (logic)") assigns a meaning to each of the formulas—usually, a [truth value](https://en.wikipedia.org/wiki/Truth_value "Truth value").

The study of interpretations of formal languages is called [formal semantics](https://en.wikipedia.org/wiki/Formal_semantics_\(logic\) "Formal semantics (logic)"). In mathematical logic, this is often done in terms of [model theory](https://en.wikipedia.org/wiki/Model_theory "Model theory"). In model theory, the terms that occur in a formula are interpreted as objects within [mathematical structures](https://en.wikipedia.org/wiki/Structure_\(mathematical_logic\) "Structure (mathematical logic)"), and fixed compositional interpretation rules determine how the truth value of the formula can be derived from the interpretation of its terms; a _model_ for a formula is an interpretation of terms such that the formula becomes true.

*   [Combinatorics on words](https://en.wikipedia.org/wiki/Combinatorics_on_words "Combinatorics on words")
*   [Formal method](https://en.wikipedia.org/wiki/Formal_method "Formal method")
*   [Free monoid](https://en.wikipedia.org/wiki/Free_monoid "Free monoid")
*   [Grammar framework](https://en.wikipedia.org/wiki/Grammar_framework "Grammar framework")
*   [Mathematical notation](https://en.wikipedia.org/wiki/Mathematical_notation "Mathematical notation")
*   [String (computer science)](https://en.wikipedia.org/wiki/String_\(computer_science\) "String (computer science)")

1.   For example, [first-order logic](https://en.wikipedia.org/wiki/First-order_logic "First-order logic") is often expressed using an alphabet that, besides symbols such as ∧, ¬, ∀ and parentheses, contains infinitely many elements _x_0, _x_1, _x_2, … that play the role of variables.

1.   See e.g. Reghizzi, Stefano Crespi (2009). [_Formal Languages and Compilation_](https://books.google.com/books?id=AxH6cWm61i0C). Texts in Computer Science. Springer. p. 8. [Bibcode](https://en.wikipedia.org/wiki/Bibcode_\(identifier\) "Bibcode (identifier)"):[2009flc..book.....C](https://ui.adsabs.harvard.edu/abs/2009flc..book.....C). [ISBN](https://en.wikipedia.org/wiki/ISBN_\(identifier\) "ISBN (identifier)") [9781848820500](https://en.wikipedia.org/wiki/Special:BookSources/9781848820500 "Special:BookSources/9781848820500"). An alphabet is a finite set
2.   ["In the prehistory of formal language theory: Gauss Languages"](https://www.researchgate.net/publication/220530857). January 1992. Retrieved 30 April 2021.
3.   ["Gottlob Frege"](https://plato.stanford.edu/entries/frege/). 5 December 2019. Retrieved 30 April 2021.
4.   Martin Davis (1995). ["Influences of Mathematical Logic on Computer Science"](https://books.google.com/books?id=YafIDVd1Z68C&pg=PA290). In Rolf Herken (ed.). _The universal Turing machine: a half-century survey_. Springer. p. 290. [ISBN](https://en.wikipedia.org/wiki/ISBN_\(identifier\) "ISBN (identifier)") [978-3-211-82637-9](https://en.wikipedia.org/wiki/Special:BookSources/978-3-211-82637-9 "Special:BookSources/978-3-211-82637-9").
5.   ["Thue's 1914 paper: a translation"](https://core.ac.uk/download/pdf/297029993.pdf) (PDF). 28 August 2013. [Archived](https://web.archive.org/web/20210430011129/https://core.ac.uk/download/pdf/297029993.pdf) (PDF) from the original on 30 April 2021. Retrieved 30 April 2021.
6.   ["Emil Leon Post"](https://mathshistory.st-andrews.ac.uk/Biographies/Post/). September 2001. Retrieved 30 April 2021.
7.   Torres Quevedo, Leonardo. [Sobre un sistema de notaciones y símbolos destinados a facilitar la descripción de las máquinas, (pdf)](https://quickclick.es/rop/pdf/publico/1907/1907_tomoI_1634_01.pdf), pp. 25–30, Revista de Obras Públicas, 17 January 1907.
8.   Bruderer, Herbert (2021). ["The Global Evolution of Computer Technology"](https://books.google.com/books?id=Gh8SEAAAQBAJ&dq=leonardo+torres+quevedo+heinz+zemanek+formal+language&pg=PA1212). _Milestones in Analog and Digital Computing_. Springer. p. 1212. [ISBN](https://en.wikipedia.org/wiki/ISBN_\(identifier\) "ISBN (identifier)") [978-3030409739](https://en.wikipedia.org/wiki/Special:BookSources/978-3030409739 "Special:BookSources/978-3030409739").
9.   Jager, Gerhard; Rogers, James (19 July 2012). ["Formal language theory: refining the Chomsky hierarchy"](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3367686). _Philosophical Transactions of the Royal Society B_. **367** (1598): 1956–1970\. [doi](https://en.wikipedia.org/wiki/Doi_\(identifier\) "Doi (identifier)"):[10.1098/rstb.2012.0077](https://doi.org/10.1098%2Frstb.2012.0077). [PMC](https://en.wikipedia.org/wiki/PMC_\(identifier\) "PMC (identifier)") [3367686](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3367686). [PMID](https://en.wikipedia.org/wiki/PMID_\(identifier\) "PMID (identifier)") [22688632](https://pubmed.ncbi.nlm.nih.gov/22688632).
10.   ["John Warner Backus"](https://mathshistory.st-andrews.ac.uk/Biographies/Backus/). February 2016. Retrieved 30 April 2021.
11.   [Hopcroft & Ullman (1979)](#CITEREFHopcroftUllman1979), Chapter 11: Closure properties of families of languages.

Works cited

*   [Hopcroft, John E.](https://en.wikipedia.org/wiki/John_Hopcroft "John Hopcroft"); [Ullman, Jeffrey D.](https://en.wikipedia.org/wiki/Jeffrey_Ullman "Jeffrey Ullman") (1979). _[Introduction to Automata Theory, Languages, and Computation](https://en.wikipedia.org/wiki/Introduction_to_Automata_Theory,_Languages,_and_Computation "Introduction to Automata Theory, Languages, and Computation")_. Reading, Massachusetts: Addison-Wesley Publishing. [ISBN](https://en.wikipedia.org/wiki/ISBN_\(identifier\) "ISBN (identifier)") [81-7808-347-7](https://en.wikipedia.org/wiki/Special:BookSources/81-7808-347-7 "Special:BookSources/81-7808-347-7").

General references

*   A. G. Hamilton, _Logic for Mathematicians_, [Cambridge University Press](https://en.wikipedia.org/wiki/Cambridge_University_Press "Cambridge University Press"), 1978, [ISBN](https://en.wikipedia.org/wiki/ISBN_\(identifier\) "ISBN (identifier)") [0-521-21838-1](https://en.wikipedia.org/wiki/Special:BookSources/0-521-21838-1 "Special:BookSources/0-521-21838-1").
*   [Seymour Ginsburg](https://en.wikipedia.org/wiki/Seymour_Ginsburg "Seymour Ginsburg"), _Algebraic and automata theoretic properties of formal languages_, North-Holland, 1975, [ISBN](https://en.wikipedia.org/wiki/ISBN_\(identifier\) "ISBN (identifier)") [0-7204-2506-9](https://en.wikipedia.org/wiki/Special:BookSources/0-7204-2506-9 "Special:BookSources/0-7204-2506-9").
*   [Michael A. Harrison](https://en.wikipedia.org/wiki/Michael_A._Harrison "Michael A. Harrison"), _Introduction to Formal Language Theory_, Addison-Wesley, 1978.
*   [Rautenberg, Wolfgang](https://en.wikipedia.org/wiki/Wolfgang_Rautenberg "Wolfgang Rautenberg") (2010). _A Concise Introduction to Mathematical Logic_ (3rd ed.). New York: [Springer Science+Business Media](https://en.wikipedia.org/wiki/Springer_Science%2BBusiness_Media "Springer Science+Business Media"). [doi](https://en.wikipedia.org/wiki/Doi_\(identifier\) "Doi (identifier)"):[10.1007/978-1-4419-1221-3](https://doi.org/10.1007%2F978-1-4419-1221-3). [ISBN](https://en.wikipedia.org/wiki/ISBN_\(identifier\) "ISBN (identifier)") [978-1-4419-1220-6](https://en.wikipedia.org/wiki/Special:BookSources/978-1-4419-1220-6 "Special:BookSources/978-1-4419-1220-6").
*   [Grzegorz Rozenberg](https://en.wikipedia.org/wiki/Grzegorz_Rozenberg "Grzegorz Rozenberg"), [Arto Salomaa](https://en.wikipedia.org/wiki/Arto_Salomaa "Arto Salomaa"), _Handbook of Formal Languages: Volume I-III_, Springer, 1997, [ISBN](https://en.wikipedia.org/wiki/ISBN_\(identifier\) "ISBN (identifier)") [3-540-61486-9](https://en.wikipedia.org/wiki/Special:BookSources/3-540-61486-9 "Special:BookSources/3-540-61486-9").
*   Patrick Suppes, _Introduction to Logic_, D. Van Nostrand, 1957, [ISBN](https://en.wikipedia.org/wiki/ISBN_\(identifier\) "ISBN (identifier)") [0-442-08072-7](https://en.wikipedia.org/wiki/Special:BookSources/0-442-08072-7 "Special:BookSources/0-442-08072-7").

*   ["Formal language"](https://www.encyclopediaofmath.org/index.php?title=Formal_language), _[Encyclopedia of Mathematics](https://en.wikipedia.org/wiki/Encyclopedia_of_Mathematics "Encyclopedia of Mathematics")_, [EMS Press](https://en.wikipedia.org/wiki/European_Mathematical_Society "European Mathematical Society"), 2001 \[1994\]
*   [University of Maryland](https://en.wikipedia.org/wiki/University_of_Maryland,_Baltimore "University of Maryland, Baltimore"), [Formal Language Definitions](http://www.csee.umbc.edu/help/theory/lang_def.shtml)
*   James Power, ["Notes on Formal Language Theory and Parsing"](http://www.cs.nuim.ie/~jpower/Courses/parsing/) [Archived](https://web.archive.org/web/20071121142736/http://www.cs.nuim.ie/~jpower/Courses/parsing/) 21 November 2007 at the [Wayback Machine](https://en.wikipedia.org/wiki/Wayback_Machine "Wayback Machine"), 29 November 2002.
*   Drafts of some chapters in the "Handbook of Formal Language Theory", Vol. 1–3, G. Rozenberg and A. Salomaa (eds.), [Springer Verlag](https://en.wikipedia.org/wiki/Springer_Verlag "Springer Verlag"), (1997):
    *   Alexandru Mateescu and Arto Salomaa, ["Preface" in Vol.1, pp. v–viii, and "Formal Languages: An Introduction and a Synopsis", Chapter 1 in Vol. 1, pp. 1–39](https://www.cs.cmu.edu/~lkontor/noam/Mateescu-Salomaa.pdf)
    *   Sheng Yu, ["Regular Languages", Chapter 2 in Vol. 1](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.67.1248&rep=rep1&type=pdf)
    *   Jean-Michel Autebert, Jean Berstel, Luc Boasson, ["Context-Free Languages and Push-Down Automata", Chapter 3 in Vol. 1](http://citeseer.ist.psu.edu/248295.html)
    *   Christian Choffrut and Juhani Karhumäki, ["Combinatorics of Words", Chapter 6 in Vol. 1](http://www.liafa.jussieu.fr/~cc/PUBLICATIONS/CKTUCS.PS.gz)
    *   Tero Harju and Juhani Karhumäki, ["Morphisms", Chapter 7 in Vol. 1, pp. 439–510](http://users.utu.fi/harju/articles/morph.pdf)
    *   Jean-Eric Pin, ["Syntactic semigroups", Chapter 10 in Vol. 1, pp. 679–746](http://www.liafa.jussieu.fr/~jep/PDF/HandBook.pdf)
    *   M. Crochemore and C. Hancart, ["Automata for matching patterns", Chapter 9 in Vol. 2](http://www-igm.univ-mlv.fr/~mac/REC/DOC/B4.ps)
    *   Dora Giammarresi, Antonio Restivo, ["Two-dimensional Languages", Chapter 4 in Vol. 3, pp. 215–267](https://web.archive.org/web/20071008170115/http://bruno.maitresdumonde.com/optinfo/Spe-MP/dmds1998/2dlang/giammaresi-restivo-paper.ps)