# ArrowCatcher 💘
A hard-coded assistive and automated diagram chaser for many of the jewels (theorems) of Homological Algebra.  

_Not only do we help you chase diagrams, but catch them too!_

Hard-coded in the sense that it's not a fully-fledged / generic proof assistant or automated theorem prover.  It only handles some (well-known) structures such as $R$-modules over a commutative ring $R$.
For example, there is a hard-coded rule defining what it means to be an epimorphism in a category.   Another thing I will hard-code is that a functor applied to a commutative diagram yields another commutative diagram (in the codomain category of the functor), and we do not attempt to piece together a proof that the resulting diagram is commutative from the definitional commutative triangles comprising the usual definition of functor.

This will be the backend kernel (written in D) to a Qt / C++ GUI frontend.  
