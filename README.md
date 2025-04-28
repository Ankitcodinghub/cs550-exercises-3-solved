# cs550-exercises-3-solved
**TO GET THIS SOLUTION VISIT:** [CS550 Exercises 3 Solved](https://www.ankitcodinghub.com/product/cs550-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118155&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS550 Exercises 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Exercises 3

Exercise 1 (Skolemization &amp; Herbrand Universes). The following formulas (on the signature {P,E} with two predicate symbol and ar(P) = ar(E) = 2) form the theory of Unbounded Dense Total Orders. The set R of real numbers is an example of such an order where P(x,y) denotes x &lt; y and E(x,y) denotes x = y. For each of the axioms, apply negation normal form, Skolemization and prenex normal form (in this order).

• ∀x. E(x,x)

• ∀x,y,z. (P(x,y) ∧ P(y,z)) → P(x,z)

• ∀x,y. P(x,y) → ∃z.P(x,z) ∧ P(z,y)

• ∀x,y. E(x,y) ↔ ¬(P(x,y) ∨ P(y,x))

• ∀x,y,z. (E(x,y) ∧ E(y,z)) → E(x,z)

• ∀x,y,z. (E(x,y) ∧ P(x,z)) → P(y,z)

• ∀x,y,z. (E(x,y) ∧ P(z,x)) → P(z,y)

What does Herbrand’s Theorem say about this set of axiom? Can you find an example?

Exercise 2 (Effectively Propositional Logic). Consider the class of formulas of first order logic built on a signature containing only constant symbols (arity 0 functions) and predicate symbols, and of the following form:

∀x1…∀xn. F(x1,…,xn)

where F is quantifier-free.

1. Show that this set of formula is closed under conjunction, disjunctionand negation for satisfiability, by which is meant that for arbitrary formulas F1 and F2, you can efficiently compute formulas in the above form that are equisatisfiable to F1 ∧ F2, F1 ∨ F2 and ¬F1.

2. Show there exists an algorithm to decide the satisfiability of such formulas.

Exercise 3. Consider the ternary propositional operation ite(x,y,z) (if x then y else z) defined by the following truth table:

x y z ite(x,y,z)

0 0 0 0

0 0 1 1

0 1 0 0

0 1 1 1

1 0 0 0

1 0 1 0

1 1 0 1

1 1 1 1

We consider expressions build only from variables and ite, without constants 0 and 1. We call them pure ite expressions.

1. Express x ∧ y and x ∨ y as a pure ite expression;

2. Let e denote an ite expression whose set of free variables is V = {x1,…,xn}. Let v be an assignment assigning all variables in V to 0 (false). What is the truth value of e under v?

3. Given an example of a function f : {0,1}n → {0,1} that is not expressible as a pure ite expression.

4. Each of the following completion of the statement are true?

The functions f : {0,1}n → {0,1} that can be expressed as pure ite expressions using variables x1,…,xn are precisely …

(a) the functions that are not constant, i.e., not equal to either thefunction f1(x1,…,xn) = 1 nor to the function f0(x1,…,xn) = 0

(b) all functions if n ≥ 3; functions expressible using only ∧,∨ in cases n = 1,2,3

(c) the functions that could be expressed using an expression withonly ∧ and ∨

(d) the functions f such that f(0,…,0) = 0

(e) the functions f such that f(0,…,0) = 0 and f(1,…,1) = 1

(f) the functions expressible using only ¬(x∧y) as a binary operation

(g) the functions such that f(x,…,x) = x for every x

(h) the functions such that f(x,…,x,f(x,…,x)) = x for every x For those answers that you chose, explain briefly why they are correct.

Exercise 4 (Resolution with Congruence). Consider a set D with a binary relation ≡ on D and a binary function t : D2 → D which satisfy the following properties:

assoc : x t (y t z) ≡ (x t y) t z

transE : (x ≡ y) ∧ (y ≡ z) → (x ≡ z)

sym : (x ≡ y) → (y ≡ x)

congL : (x1 ≡ x2) → (x1 t y ≡ x2 t y)

congR : (y1 ≡ y2) → (x t y1 ≡ x t y2)

Define another binary relation v on D by:

x v y ↔ x t y ≡ y (DefLE)

We claim that it follows that v is a transitive relation, that is:

x v y ∧ y v z → x v z (TransLE)

In other words, we wish to prove that the following holds in pure first-order logic, where all formulas are considered universally quantified:

{assoc,transE,sym,congL,congR,DefLE} |= TransLE (∗)

Note that, when representing the problem in first order logic, t1 ≡ t2 is just a notation for E(t1,t2) where E is some binary predicate symbol, t1 v t2 is a notation for L(t1,t2) where L is another binary predicate symbol, and t1 t t2 is a notation for f(t1,t2) where f is some binary function symbol.

Our goal is to use resolution for first-order logic to derive a formal proof of (∗) by deriving a contradiction.

A) (2pt) To begin the proof, write down a numbered sequence of clauses that you will need in your proof, corresponding to assoc,transE,… (whatever the initial set of clauses should be to prove (∗) by contradiction).

1. {x t (y t z) ≡ (x t y) t z} (from assoc) 2. {¬(x ≡ y),¬(y ≡ z),(x ≡ z)} (from transE)

3. …

1 def sym(x: D, y: D) = {…}.ensuring( !(x ≡ y) || y ≡ x )

2 … // define the other axioms

3

4 def transitive(x: D, y: D, z: D) = {

5 require(x v y)

6 require(y v z)

7 sym(y t z, z)

8 congR(x, z, y t z)

9 assoc(x, y, z)

10 trans(x t z, x t (y t z), (x t y) t z)

11 congL(x t y, y, z)

12 transE(x t z, (x t y) t z, y t z)

13 transE(x t z, y t z, z)

14 }.ensuring(x v z)

Exercise 5 (Logic of Partial Functions). We wish to use first-order logic for our verification task, which requires proving validity of formulas. We use a first-order language (signature) with a relational symbol E, which we would like to represent equality and satisfy the laws of reflexivity, symmetry, and transitivity, as well as congruence laws (analogous to congL and congR in Problem ??): equal elements are related in the same way by all other relation symbols. We also need a way to represent a partial function ¯p(x,y) of two arguments: the function can have at most one result, but it can be undefined for certain pairs of elements. Applying ¯p when argument is undefined gives undefined result. We will analyze two possibilities for encoding such partial functions in first-order logic, with questions arising in each of them.

Encoding 1. We use a constant b to represent undefined element and a binary function symbol p(x,y) to represent the function ¯p (note that we use p to represent the function symbol, whereas ¯p represents the function that interprets it). The language of formulas in this part has only symbols {E,p,b}.

A) (1pt) Write down, as universally quantified first-order logic formulas,the congruence properties of p with respect to E, namely: if in the expression p(x,y) we change x to an E-related element or change y to an E-related element, the new result is E-related to p(x,y).

B) (1pt) Write down, as a universally quantified first-order logic formula,the property that applying p when one of the arguments is undefined results in an undefined value.

C) (1pt) Describe Herbrand universe (the set of ground terms) in thislanguage. Is it finite or infinite?

Encoding 2. We use a ternary relation symbol P(x,y,z) to represent the fact ¯p(x,y) = z when all values are defined. To represent that the function is not defined for a given x and y, relation interpreting P would simply not contain any (interpretation of) z such that P(x,y,z) is true. Let a be a constant denoting an arbitrary element of the universe. The language of formulas in this part has only symbols {E,P,a}.

D) (1pt) Write down, as universally quantified first-order logic formulas,the congruence properties of P with respect to E, namely: if elements x,y,z are related by P, then elements E-related to them are also related by P, as expected by a relation with properties of equality.

E) (1pt) Write down as a universally quantified formula, the propertythat P should represent a functional relation modulo E: for given pair of elements x,y, the result of ¯p, if it exists, is unique up to E.

F) (1pt) Consider the result of applying Skolemization of the properties inD) and E). How many new Skolem functions are introduced? Describe the Herbrand universe (the set of ground terms) in this language. Is it finite or infinite?

G) (3pt) Is there a terminating algorithm for checking, given two formu-las F1,F2 in prenex form with only universal quantifiers using symbols from {E,P,a}, whether Ax ∪ {F1} |= F2 holds, where Ax are the Skolemized versions of properties introduced in D) and E). If yes, sketch the algorithm. If no, argue why the problem is undecidable.
