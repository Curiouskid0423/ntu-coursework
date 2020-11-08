# Notes on ML Foundation / Technique :rocket: 

## Course Notes

- Review **Theory of Generalization**   ([Lec22](https://www.youtube.com/watch?v=rUFqB5Z3YHQ&list=PLXVfgk9fNX2I7tB6oIINGBmW50rrmFTqf&index=22) - [Lec25](https://www.youtube.com/watch?v=rUFqB5Z3YHQ&list=PLXVfgk9fNX2I7tB6oIINGBmW50rrmFTqf&index=22)). Especially the "sketch of proof" of **VC bound**.
- In PLA where &nbsp;<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;sign(w^Tx))" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;sign(w^Tx))" title="sign(w^Tx))" /></a>&nbsp;, if X input is "linearly dependent", Y cannot be shattered. Reasoning [here](https://youtu.be/9kra9i6jS1g?t=4440) with proof by contradiction. 
- What is the relationship between **bias-variance tradeoff** and **VC dimension** ? 
    - Check out the UW CSE44 website (recorded below) and particular these slides: [Lec12: VC](https://courses.cs.washington.edu/courses/cse446/20wi/Lecture12/12_VC.pdf), and bias-variance [notes](https://courses.cs.washington.edu/courses/cse446/20wi/Section4/section4.pdf)
- Complexity evaluation theory such as VC Theory is slightly pedantic, especially for the Deep Learning era. Yet, the message out of the theory is still useful in tuning parameters. Check out more Deep Learning stuff from Stanford **CS229**.
- **Question**: The usefulness of VC dimension in **perceptron** currently is established on the existence of "breakpoints", where the bounding function can be expressed as a non-exponential polynomial, such that learning can be efficient and feasible. Yet, will the fact that "breakpoints" cannot "shatter" all possibilities of datapoints be a hazard to the probability of "*bad data*" **if "linearly separable" is no longer a given condition**, i.e models other than PLA or even pocket algorithm (which makes sense intuitively).
- **Question**: VC bound is the largest non-breakpoint, ie the largest number of data points which can be shattered. But what's the reason of specifying it?
- **Extended Learning**: Intuitively, since both our sample and the population comply to the same joint distribution P(x, y).

## External Learning Resources
- **UMich** EECS598 Statistical ML [Notes Website](https://web.eecs.umich.edu/~cscott/past_courses/eecs598w14/index.html) (Winter 2014)
    - [VC Theory resources](https://web.eecs.umich.edu/~cscott/past_courses/eecs598w14/notes/05_vc_theory.pdf) from UMich EECS 598 (Winter 2014)

    - [KL divergence and Hoeffding's Inequality](https://web.eecs.umich.edu/~cscott/past_courses/eecs598w14/notes/03_hoeffding.pdf) notes from UMich EECS 598 (Winter 2014)

- **Stanford** CS229 ML [Website](http://cs229.stanford.edu/syllabus-fall2020.html) Fall 2020
    - [Linear Algebra Reference](http://cs229.stanford.edu/notes2020fall/notes2020fall/linalg2.pdf)
    May be useful when learning Matrix Calculus, or reviewing concepts such as diagonalization.
- **Berkeley** Prof Shewchuk [CS189](https://people.eecs.berkeley.edu/~jrs/189/)
    - ML Foundation / ML Technique is modeled after **Caltech** [Learning from Data](https://work.caltech.edu/telecourse), so the aspect of ML teaching can be quite different from Berkeley.
    - [A Comprehensive ML Guide](http://snasiriany.me/files/ml-book.pdf) and Prof Sahai's lecture notes on [EECS189](https://www.eecs189.org).
    - Should be able to take advantage of some learning resources here already.
- Closely related resources to NTU ML Foundation & Technique
    - **Caltech** [Machine Learning Video Library](https://work.caltech.edu/library/index.html) (probably more similar to NTU's course) than Berkeley's.
    - **U Washington** [CSE446](https://courses.cs.washington.edu/courses/cse446/20wi/) Winter 20 Website. Interesting notes also closely modeled after **Learning From Data**.
- **EECS16A** Note 9 & 10 for linear algebra review.
