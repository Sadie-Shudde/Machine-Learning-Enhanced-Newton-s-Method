# Machine-Learning-Enhanced-Newton-s-Method
This projects aims to see how classical root-finding methods compare to each other, and how they to Machine-Learning (ML) enhanced versions. The classical methods used consist of Bisection, Secant, and Newton-Raphson. The first ML enhanced version is Newton-Raphson were the ML model predicts better initial guesses.


Abstract. Root-finding algorithms are fundamental in the field of numerical
analysis. There are several different methods commonly used, and Newton-
Raphson, also known as Newton’s method, is one of them. It is used for its very
quick quadratic convergence near the root. However, Newton’s performance
depends greatly on the initial guess given. Poor initial guesses can cause the
method to diverge or converge slowly. Although mathematicians have different
methods and reasons for picking an initial guess, machine learning (ML) can
be used to provide a quicker and better initial guess by learning patterns. We
trained a neural network on 1,000 quadratic equations with random coefficients
and compared it to classical Newton-Raphson with random initial guesses. The
results showed that the ML-enhanced model reduced iterations by 44.0% (from
4.45 to 2.49 average iterations) and demonstrated 42.09% greater consistency.
Although both the classical and ML-enhanced methods showed a 100% success
rate, the ML model offers significant computational advantages for repeated
root-finding.
