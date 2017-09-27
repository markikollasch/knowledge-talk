# How do we know it's right?

# Let me qualify that...

How do we know we have implemented what we intended?

How do we gain confidence in the correctness of our work?

# How do we know anything?
Proof: demonstrating that some fact is necessarily true. Distinguish between proven and unproven.

Inference: observing that some fact is plausibly true. Distinguish between more reasonable and less reasonable guesses.

# Inference
- Experiments and observations increase confidence incrementally
- Can never attain perfect certainty, but we can get it pretty high
- Applicable to virtually everything
- We do it by instinct

<div class="notes">
I infer that the sun will rise tomorrow
</div>

# Proof
- An absolute assertion supported by a formal logic system
- Final and incontrovertible
- Most things cannot be proven
- Or else we don't know how to prove them

<div class="notes">
Say something about Curry-Howard Correspondence
</div>

# Some things to note
- Proof and inference are complementary approaches
- You can inferentially validate things that have been proven
- You can prove things that you learned by inference
- Proofs are not usually as "convincing" as observation

<div class="notes">
You can use both proof and inference.

It's not usually necessary to inferentially validate proofs

Just because something has been proven doesn't mean we believe it, cognitively
</div>

# But don't take my word for it
> The properties of the numbers known today have mostly been discovered by observation,
> and discovered long before their truth has been confirmed by rigid demonstrations.

<cite>Leonhard Euler</cite>

# What's this have to do with programming?
<div class="left">
- Components of software systems can be observed
- So we can infer that our programs are correct in some ways
- Some designs make components more observable
</div>

<div class="right">
- All high-level programming languages are formal logic systems
- So we can prove that our programs are correct in some ways
- Some languages make more things provable
</div>

# This sounds familiar
<div class="left">
Inference in practice: automated testing means the test runner rejects any program that it observes contradicting its expectations
</div>
<div class="right">
Proof in practice: static typing means the compiler rejects any program that it fails to prove to be free of type errors
</div>

# So how can we increase our confidence?
<div class="left">
Infer more by ensuring every desired attribute of the program is testable and tested (test-driven development)
</div>
<div class="right">
Prove more by using languages that permit the expression and validation of stronger invariants (like Rust, Haskell, Elm)
</div>

# Questions?
