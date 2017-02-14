# ALPS - An LTL Proof System.
__The goal of this project is to create a tool to verify proofs on _concurrent programs_. We aim to produce a tool that accepts a _small_ concurrent program, a proof statement about the program and verifies the provided proof on the program.__

Model checker v. proof checker
-------------------------------
Currently an existing way to analyse concurrent programs is using model checkers, like [SPIN] (https://en.wikipedia.org/wiki/SPIN_model_checker). These basically test all possible states in the state diagram and verify LTL statements by brute force.

A Proof Checker on the other hand would take a proof on the program and tries to verify it. The difference to the model checker would be that the program is never run, instead the logics behind the proof will be checked. Thus our hopes are that this will help students (and others) to understand concurrency and the difficulties that comes with it. 
