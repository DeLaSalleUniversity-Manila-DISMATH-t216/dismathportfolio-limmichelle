# dismathportfolio-limmichelle
dismathportfolio-limmichelle created by Classroom for GitHub
## WEEK 1:

- We introduced each other by telling our names, course, and favorite hobbies. 
- However, our professor discussed a brief introduction about Discrete Mathemiatics and ts advantage that made me interested because it will enhance my critical thinking.
- I have learned that there are different classifications of truth: authoritative, legal, scientific, probable, philosophical, and mathematical. 
- I have learned that the primary focus of Discrete Mathematics is "mathematical" truth.
- I learned the definition of logic which is the <i>basis of all mathematical reasoning, and of all automated reasoning</i> (Rosen, 2007).
- I learned about propositions, a declarative statement that is either true or false but not both, and its definitions - negation, conjunction, disjunction, exclusive or, conditional, and biconditional. 
- I learned to use the truth table to prove logical statements. 
- I am introduced to new symbols for logic; ¬ (negation), ∧ (conjunction or "AND"), ∨ (disjunction or "OR"), ⊕ (exclusive or),  → (conditional or implication), and ↔ (biconditional). 
- In addition, we were introduced to the concepts of converse, inverse, and contrapositive. 
- Converse (p → q ≠ q → p), Inverse (¬p → ¬q), Contrapositive (¬q → ¬p).
- In short the table will help summarized it.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

## WEEK 2:

- I learned that using truth table has its limitations and there is another way to prove logical statements by the use of logical equivalences.
- There are different logical equivalences:

  | Equivalence | Name |
  | :---------: | :--: |
  | p ∧ <b>T</b> ≡ p <p>p ∨ <b>F</b> ≡ p</p> | Identity Laws |
  | p ∨ <b>T</b> ≡ <b>T</b> <p>p ∧ <b>F</b> ≡ <b>F</b> | Domination Laws |
  | p ∨ p ≡ p <p>p ∧ p ≡ p | Idempotent Laws |
  | ¬(¬p) ≡ p | Double Negation Law |
  | p ∨ q ≡ q ∨ p <p>p ∧ q ≡ q ∧ p</p> | Commutative Laws |
  | (p ∨ q) ∨ r ≡ q ∨ (p ∨ r) <p>(p ∧ q) ∧ r ≡ q ∧ (p ∧ r)</p> | Associative Laws |
  | p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (q ∨ r) <p> p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (q ∧ r)</p> | Distributive Laws |
  | ¬(p ∧ q) ≡ ¬p ∨ ¬q <p>¬(p ∨ q) ≡ ¬p ∧ ¬q</p> | De Morgan's Law |
  | p ∨ (p ∧ q) ≡ p <p>p ∧ (p ∨ q) ≡ p</p> | Absorption Laws |
  | p ∨ ¬p ≡ <b>T</b> <p>p ∧ ¬p ≡ <b>F</b> | Negation Laws |

- After logical equivalances, we learned about Predicate Logic and Quantifiers.
- Predicate Logic deals with propositions that contains predicates, which refers to the <i>property of the subject or statement can have</i> (Rosen, 2007). 
- I learned that quantification is a process of producing a proposition from a propositional function. 
- We are introducted to two quantifiers: " <i><b>For all</i></b> " (∀) Universal Quantification & " <i><b>There exists</i></b> " (∃) Existential Quantification.
- We are given a homework to prove if Superman really exists by using the rule of inference.
- I learned that the rule of inference states that an argument is <b>valid</b> if it follows the pattern of the rules of inference.
- I also learned that <i>validity</i> and <i>truth</i> are two different things because an argument can be valid but not true. 
- The rules of inference are <b> Modus Ponens, Modus Tollens, Hypothetical Syllogism, Disjunctive Syllogism, Addition, Simplification, Conjunction, and Resolution </b>.

- <b> Note </b>
- A <i> if </i> B 
- where <p> A is <b> consequent </b> </p>  <p> B is <b> antecedent </b> </p>
- A <i> only if </i> B 
- where <p> A is <b> antecedent </b> </p>  <p> B is <b> consequent </b> </p>  

##WEEK 3
* We discusssed logical equivalences.
* Proving was not easy since you really need to be familiar with the laws like Identity, Domination, Negation, Double Negation, Idempotent, Commutative, Associative, Distributive, De Morgan's and Absorption. 
* I realized that I need more practice to completely comprehend this topic. 
* The superman homework was very challenging but it gave me an idea of what the quiz would be like.
* The Rules of Inference was also discussed this week and it's somehow similar to the laws:
  - Modus Ponens
  - Modus Tollens
  - Hypothetical Syllogism
  - Disjunctive Syllogism
  - Addition
  - Simplification
  - Conjunction
  - Resolution
|  **Type**  |  **Rule of Inference**  |  **Tautology**  |
| :-------: | :--------------: | :---------: |
| Modus Ponens |  p, p → q ∴ q  |  (p ∧ (p → q)) → q  |
| Modus Tollens |  ¬q, p → q ∴ ¬p |  (¬q ∧ (p → q)) → ¬p  |
| Hypothetical Syllogism |  p → q, q → r ∴ p → r  |  ((p → q) ∧ (q → r)) → (p → r)  |
| Disjunctive Syllogism |  p ∨ q, ¬p ∴ q  |  ((p ∨ q) ∧ ¬p) → q  |
| Addition |  p ∴ p ∨ q  |  p → p ∨ q  |
| Simplification |  p ∧ q ∴ p  |  (p ∧ q) → p  |
| Conjunction  |  p, q ∴ p ∧ q  |  ((p) ∧ (q)) → (p ∧ q)  |
| Resolution  |  p ∨ q, ¬p ∨ r ∴ q ∨ r  |  ((p ∨ q) ∧ (¬p ∨ r)) → q ∨ r  |

* We also tackled the Universal and Existential Quantifier. 
  - Universal quantifier - many mathematical statements assert that a property is true for all values of a variable in a particular domain.
  - Existential quantifier - it is true if and only if p(x) is true for at least one value of x in the domain.
* I also learned the defenition of an integer.


##WEEK 4
- This week we learned a method on how to construct proofs  which is called <b> Methods of Proof </b>
- Under <b> Methods of Proof </b> there are several ways on proving logical statemetns which are:
- Direct Proof
- Proof by Contraposition (Indirect)
- Vacuous and Trivial Proof
- Proof by Contradiction (Indirect)
- Proof by Equivalence 
- Mathematical Induction
- I learned Methods of Proof is damn hard especially if you still haven't figured out Rules of Inferences.
- So far Direct Proof until Contradiction were discussed, and it was an information overload.
- But Direct proof seems easy enough.
- I learned the defenition of an ODD and EVEN number again!

##WEEK 5
-We discussed Proof by Equivalence (HARD)  till Mathematical Induction.
- We solved some exercises or examples of Methods of Proof which was very helpful but still confusing. 
- Proviing by Bi-conditional is hard cause you need to prove it both sides of the premises and precedent.
- We refreshed Mathematical Induction from our ENGALG2

##WEEK 6
-We discuused about SUMMATION where in the notation for sum of am, am+1, ..., an is ∑ai=m ai where i is the index of summation.
  - Σ “sigma”
- Recursive Steps
  - 1. Basis step: specify the value at zero
  - 2. Recursive step: Find a rule for finding its value at an integer number from the values at smaller integers.
-Program Correctness is to ensure that a program gives the correct output 
 - Program Verification - A program is said to be correct if it produces the correct output for every possible input.
  - Partial Correctness
- HOARE TRIPLE p{S}q
  - S is said to be partially correct with respect to the initial assertion p and the final assertion q if whenever p is true for the input values of S and S terminates, then q is true for the output values of S
  - Hoare Triple Notation: p{S}q
  - Composition Rule <br>
   p{S<sub>1</sub>}q <br>
   q{S<sub>2</sub>}r <br>
  -------------------- <br>
  ∴ p{S<sub>1</sub>:S<sub>2</sub>}q <br><br>

  
##WEEK 7
* We were introduced to the lesson about sets and cardinality.
 - SET THEORY
  - A set is an unordered collection of distinct objects, which may be anything (including other sets).
    - {f, a, e, n, i, c, l}
  - Empty Set { } = ∅ means no elements
    - {∅} not an empty set
  - Set Builder Notation {x | some property that x satisfies}
  - Membership
    - 1 ∈ {1, 2, 3, 4}
* We reviewed the lesson about quantifiers and nested quantifiers in preparation for our first quiz.
- *SET IDENTITIES TABLE*

|  LAW  |  IDENTITY  |
| :------: | :-----------------------------: |
|  Identity Laws  |  A ⋂ U ≡ A  <br>  A ⋃ ∅ ≡ A  |
|  Domination Laws  |  A ⋃ U ≡ U  <br>  A ⋂ ∅ ≡ ∅  |
|  Idempotent Laws  |  A ⋃ A ≡ A  <br>  A ⋂ A ≡ A  |
|  Complementation Law  |  (A¯)‾ ≡ A  |
|  Commutative Laws  |  A ⋃ B ≡ B ⋃ A  <br>  A ⋂ B ≡ B ⋂ A  |
|  Associative Laws  |  A ⋃ (B ⋃ C) ≡ (A ⋃ B) ⋃ C  <br>  A ⋂ (B ⋂ C) ≡ (A ⋂ B) ⋂ C  |
|  Distributive Laws  |  A ⋃ (B ⋂ C) ≡ (A ⋃ B) ⋂ (A ⋃ C) <br>  A ⋂ (B ⋃ C) ≡ (A ⋂ B) ⋃ (A ⋂ C)  |
|  De Morgan's Laws  |  (A ⋂ B)‾ ≡ A‾ ⋃ B‾  <br>  (A ⋃ B)‾ ≡ A‾ ⋂ B‾  |
|  Absorption Laws  |  A ⋃ (A ⋂ B) ≡ A  <br>  A ⋂ (A ⋃ B) ≡ A  |
|  Complement Laws  |  A ⋃ A‾ ≡ U  <br>  A ⋂ A‾ ≡ ∅  |

- SUBSETS ⊆
  - A set S is a subset of a set T (denotes S ⊆ T) if all elements of S are also elements of T
- POWER SET P(S) = {T|T ⊆ S} - A set of all subsets.
- CARDINALITY |S| - The number of element it contains
* A function f from A to B is an assignment of exactly one element of B to each element of A.
* Functions are also called mappings/transformations.
* Domain - set of real numbers
* Codomain - set of integers
* Range - actually occurring values
* Types of functions
 * One-to-one function (injective)
 * Onto function (subjective)
 * One-to-one and onto (bijective) - also called one-to-one correspondents
* A one-to-many relation is not a function.

##WEEK 8
-Algorithms - It is defined as a finite set of precise instructions for performing a computation or for solving a problem.
- Properties of Algorithms: Input, Output, Definiteness, Correctness, Finiteness, Effectiveness, Generality
-Pseudocode - serves as an intermediate step in the construction of programs implementing algorithms in one of a variety of different programming languages. 
            - for human reading, something like a draft before doing actual programming on the computer
Algorithm example: Finding the Maximum in a Finite Set
  - Procedure: ({a1, a2, a3,..,an} ∈ , Z)
  - Output: largest 8
  - Pseudocode
    1. max = a1;
    2. for i: 2 to n {
    3.   if(max < ai)
    4.       max = ai;}


