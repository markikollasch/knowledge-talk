# How do we know it's right?

<style>
em {
  font-style: inherit !important;
  color: lightgreen;
}

strong {
  font-weight: inherit !important;
  color: skyblue;
}
</style>

# Let me qualify that

How do we know we have implemented what we intended?

How do we gain confidence in the correctness of our work?

# How do we know anything?
. . .

*Proof*: demonstrating that some fact is necessarily true. Distinguish between proven and unproven.

. . .

**Inference**: observing that some fact is plausibly true. Distinguish between more reasonable and less reasonable guesses.

<div class="notes">
Maybe stop and ask for guesses
</div>

# **Inference**
- Experiments and observations increase confidence incrementally
- Can never attain perfect certainty
- But we can get it pretty high
- Applicable to virtually everything
- We do it by instinct

<div class="notes">
I infer that the sun will rise tomorrow
</div>

# *Proof*
- An absolute, incontrovertible assertion
- Supported by axioms and a formal logic system
- Most things cannot be proven
- Or else we don't know how to prove them
- If it's proven, it's perfectly reliable forever

<div class="notes">
Axioms themselves are known and unprovable

Computational models are subject to proof

Curry-Howard Correspondence
</div>

# Some things to note
- *Proof* and **inference** are complementary approaches
- You can inferentially validate things that have been proven
- You can prove things that you learned by inference
- Even though they are stronger, proofs are not usually as "convincing" as inference

<div class="notes">
You can use both proof and inference.

It's not usually necessary to inferentially validate proofs

Just because something has been proven doesn't mean we believe it, cognitively,
but it helps to see it first
</div>

# But don't take my word for it
> The properties of the numbers known today have mostly been **discovered by observation**,
> and discovered long before their truth has been *confirmed by rigid demonstrations*.

<cite>Leonhard Euler</cite>

# Applicability to software?

- Components of software systems can be **observed**
- All high-level programming languages are *formal logic* systems
- Therefore we can both **infer** and *prove* correctness

<div class="notes">
Languages can make programs more provable

Architecture can make programs more observable
</div>

# This sounds familiar

Automated testing can **observe** a program and compare it to expectations

Static typing can reject any program that isn't *proven* to be free of type errors

<div class="notes">
This is proof and inference in practice.
</div>

# How to increase confidence?

. . .

Test all attributes of the program  
(**Test-driven development** catches more)

Statically prove absence of classes of errors  
(*Stronger type systems* like Rust and Haskell do more)

<div class="notes">
Infer more by ensuring every desired attribute of the program is testable and tested (test-driven development)

Prove more by using languages that permit the expression and validation of stronger invariants (like Rust, Haskell, Elm)
</div>

# Questions?
