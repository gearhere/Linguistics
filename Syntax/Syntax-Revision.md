# Syntax Revision

## I. Terminology

### 1. I-language

- When linguists talk about Language (also known as **i-language**), they are generally talking about the ability of humans to speak any (particular) language. Noam Chomsky also calls this **the Human Language Capacity**.
- Language (capital L): The psychological ability of humans to produce and understand a particular language. Also called the Human Language Capacity or i-Language.
- **Recursion**: The ability to embed structures iteratively inside one another. Allows us to produce sentences we’ve never heard before.

### 2. competence vs performance

- **Competence**: What you know about your language.

- **Performance**: The real-world behaviors that are a consequence of what you know about your language.
- **Performance** refers to the kinds of language that are actually produced and heard. **Competence**, by contrast, refers to what we know about our language; it is unimpeded by factors that might muddy the waters of performance.

### 3. universal grammar

- There are very good reasons to believe that a human facility for Language (perhaps in the form of a “Language organ” in the brain) is innate. We call this facility **Universal Grammar (or UG)**.
- Universal Grammar (UG): The innate (or instinctual) part of each language’s grammar.

### 4. category

- The word’s part of speech is also known as **syntactic category** or **word class**. The most common parts of speech are nouns, verbs, adjectives, adverbs, and prepositions.
  - **Parts of Speech** (a.k.a. Word Class, Syntactic Categories): The labels we give to constituents (N, V, Adj, Adv, D, P, C, T, Neg, Conj). These determine the position of the word in the sentence.

### 5. dominance

- Some nodes are higher in the tree than others. This reflects the fact that trees show a hierarchy of constituents. In particular, we want to talk about nodes that are higher than one another and are connected by a branch. The relation that describes two nodes that stand in this  configuration is called **domination (Domination is sometimes also called dominance.)**. A node that sits atop another and is connected to it by a branch is said to dominate that node.
- **Domination**: Node A dominates node B if and only if A is higher up in the tree than B and if you can trace a line from A to B going only downwards.

### 6. immediate dominance

**Immediately dominate**: Node A immediately dominates node B if there is no intervening node G that is dominated by A, but dominates B. (In other words, A is the first node that dominates B.)

### 7.  mother node; daughter node; sister node

- A is the **Mother** of B if A immediately dominates B.
- B is the **Daughter** of A if B is immediately dominated by A.
- **Sisters**: Two nodes that share the same mother.

### 8. constituent

- **Constituent**: A set of terminal nodes exhaustively dominated by a particular node.
  - **Exhaustive Domination**: Node A exhaustively dominates a set of terminal nodes {B, C, ..., D} provided it dominates all the members of the set (so that there is no member of the set that is not dominated by A) and there is no terminal node G dominated by A that is not a member of the set.

 ### 9. binding

- **Binds**: A binds B if and only if A c-commands B and A and B are coindexed.
  - Binding is a special kind of coindexation. It is coindexation that happens when one of the two NPs c-commands the other.
    - C-command (formal): Node A c-commands node B if every node dominating A also dominates B and neither A nor B dominates the other.
    - C-command (informal): A node c-commands its sisters and all the daughters (and granddaughters, and great-granddaughters, etc.) of its sisters.

- **Government**: Node A governs node B if A c-commands B, and there is no node G such that G is c-commanded by A and G **asymmetrically** c-commands B. 
  - Phrase-government: If A is a phrase, then the categories that count for G in the above definition must also be phrases.
  - Head-government: If A is a head (word), then the categories that count for G in the above definition must also be heads.

### 10. Binding Principles A,B,C

- **Principle A**: An anaphor must be bound in its binding domain.
  - Anaphor: An NP that obligatorily gets its meaning from another NP in the sentence.
- **Principle B**: A pronoun must be free in its binding domain.
  - Pronoun: An NP that may (but need not) get its meaning from another NP in the sentence.
- **Principle C**: An R-expression must be free.
  - R-expression: An NP that gets its meaning by referring to an entity in the world.

### 11. ergative language

These languages, called “ergative/absolutive” languages, mark the object of transitives and the subject of intransitives using the same case (absolutive); subjects of transitives are marked with a different case: **ergative**.



recursion

head

Subject: A DP that has the property indicated by the predicate phrase. What the sentence is about. In most sentences, this surfaces in the specifier of TP.

tense

D-structure

PRO

projection

---

## II. Rules, theories and their applications

### 1. c-command

- C-command (formal): Node A c-commands node B if every node dominating A also dominates B and neither A nor B dominates the other.
- C-command (informal): A node c-commands its sisters and all the daughters (and granddaughters, and great-granddaughters, etc.) of its sisters.

### 2. Binding Principles

- **Principle A**: An anaphor must be bound in its binding domain.
  - Anaphor: An NP that obligatorily gets its meaning from another NP in the sentence.
- **Principle B**: A pronoun must be free in its binding domain.
  - Pronoun: An NP that may (but need not) get its meaning from another NP in the sentence.
- **Principle C**: An R-expression must be free.
  - R-expression: An NP that gets its meaning by referring to an entity in the world.

### 3. argument and theta-roles

- **argument**：a participant involved in an event
- The **Arguments** are the entities that are participating in the predicate relation.
- - The syntactician’s definition of predicate is based on the mathematical notion of a “relation”. The predicate defines the relation between the individuals being talked about and the real world – as well as among themselves. The entities (which can be abstract) participating in the relation are called arguments.
- **Theta Role**: A bundle of thematic relations associated with a particular argument (DPs, PPs, or CPs).
- Argument criterion

### 4. x-bar theory

X-bar theory is a theory of syntactic category formation. It embodies two independent claims: one, that phrases may contain intermediate constituents projected from a head X; and two, that this system of projected constituency may be common to more than one category (e.g., N, V, A, P, etc.).



One-replacement points to a more deeply embedded structure for the NP.

### 5. govern 

**Government**: Node A governs node B if A c-commands B, and there is no node G such that G is c-commanded by A and G asymmetrically c-commands B. 

- Phrase-government: If A is a phrase, then the categories that count for G in the above definition must also be phrases.
- Head-government: If A is a head (word), then the categories that count for G in the above definition must also be heads.

### 6. EPP

**Extended projection principle**: Every sentence must have a subject.

### 7. Case filter

**The Case Filter**: 

- All DPs must be marked with a Case.
- If a DP doesn’t get Case the derivation will crash.

---

## III. Draw trees for 

### 1. Phrases and clauses 

短语 & 句子的树形图

### 2. Ambiguous structures



### 3. Passive construction



---

## IV. Questions: 

### 1. Why is language hierarchical rather than linear? (illustrate)



### 2. Exemplify head-to-head movement and NP movement with evidence from English or other languages. 



### 3. What is the difference between raising and control? Support your explanation with examples. 