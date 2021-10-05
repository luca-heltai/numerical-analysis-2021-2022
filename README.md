 [![Creative Commons License](http://mirrors.creativecommons.org/presskit/logos/cc.logo.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

# Applied Mathematics: an Introduction to Scientific Computing

- Luca Heltai (<luca.heltai@sissa.it>)
- Gianluigi Rozza (<gianluigi.rozza@sissa.it>)

- Stefano Piani (<stefano.piani@sissa.it>)
- Giovanni Stabile (<giovanni.stabile@sissa.it>)

## Course information

This is a Joint course, between SISSA PhD in Mathematical Analysis, Modeling, and Applications, Laurea Magistrale in Matematica, Laurea Magistrale in Data Science and Scientific Computing, and Master in High Performance Computing.

All lectures will take place live in room 128-129, will be streamed online using the Zoom platform, and will be recorded live on YouTube.

The first lecture will be on the 5th of October 2021 at 16.30 in Room A-128/A-129 and on Zoom.

The following Zoom link will be used for all lectures:

https://sissa-it.zoom.us/j/85796873697?pwd=cm5HNGRidndvU05UTVAvRkdOdnNrdz09

Meeting ID: 857 9687 3697
Passcode: NumAna

[Recordings for lectures of 2021-2022](https://youtube.com/playlist?list=PLcvf2raG3YsEA25P3qC1LbGVAPRXGZLJI)

[Recordings for lectures of 2020-2021](https://www.youtube.com/playlist?list=PLArvQL9bsv1y6BhTNOthBj1hGijN3vuCh)

All course material is available at

https://github.com/luca-heltai/numerical-analysis-2021-2022 (this github repository)

If you are following the course, please (FILL THIS FORM)[https://forms.gle/8DyESWnfCmXMei3h8].

# Syllabus 2021-2022
Four Modules of 12h each (1.5 CFU for each module), for a total of 48h, 6 CFU

## Frontal Lectures

### Module 1 (Basis of Numerical Analysis - Part I - Prof. Luca Heltai)

- Well posedness, condition numbers
- Polynomial based approximations
  - Power basis interpolation, 
  - Lagrange interpolation
  - Weierstrass approximation theorem)
- Interpolatory Quadrature rules
  - Orthogonal polynomials and Gauss Quadrature Formulas
  - L2 projection
- Review of elementary PDEs
  - Introduction to Finite Difference Methods
  - Introduction to Finite Element Methods

### Module 2 (Basis of Numerical Analysis - Part II - Prof. Ganluigi Rozza)

- Least square methods
- Solution methods for Linear Systems
  - direct solvers
  - iterative solvers
- Eigenvalues/Eigenvectors
- Solution methods for non-Linear systems
- Review of ODEs

### Module 3 (Basis of Numerical Modeling - Prof. Gianluigi Rozza)

- Data assimilation in biomechanics, statistics, medicine, - electric signals
- Model order reduction of matrices
- Linear models for hydraulics, networks, logistics
- State equations (real gases), applied mechanics systems, - grow population models, financial problems
- Applications of ODEs
- example in electric phenomena, signals and dynamics of - populations (Lotke-Volterra)
- Models for prey-predator, population dynamics, automatic - controls
- Applications of PDEs, the poisson problem
  - Elastic rope
  - Bar under traction
  - Heat conductivity
  - Maxwell equation

### Module 4 (Numerical Analysis with Python - Prof. Luca Heltai)

- Introduction to Python, Numpy, Scipy
- Working with numpy arrays, matrices and nd-arrays
- Exercises on Condition numbers, interpolation, quadratures
- Using numpy for polynomial approximation
- Using numpy for numerical integration
- Using numpy/scipy for ODEs
- Solving non-linear systems of equations
- Using numpy/scipy for simple PDEs

### Students projects

Application of the Finite Element Method / Finite Difference Method to the solution of models taken from the course


### Further material provided during lectures by Prof. Gianluigi Rozza [https://people.sissa.it/~grozza/amnasc/]

## References and Text Books:

-   A. Quarteroni, R. Sacco, and F. Saleri. *Numerical mathematics*,
    volume 37 of Texts in Applied Mathe- matics. Springer-Verlag, New
    York, 2000.
    [\[E-Book-ITA\]](http://dx.doi.org/10.1007/978-88-470-0818-2) [\[E-Book-ENG\]](http://dx.doi.org/10.1007/b98885)
-   A. Quarteroni. *Modellistica Numerica per problemi differenziali*.
    Springer, 2008.
    [\[E-Book-ITA\]](http://dx.doi.org/10.1007/978-88-470-0494-8)
-   A. Quarteroni. *Numerical Models for Differential Problems*.
    Springer, 2009.
    [\[E-Book-ENG\]](http://dx.doi.org/10.1007/978-88-470-1071-0)
-   A. Quarteroni and A. Valli. *Numerical approximation of partial
    differential equations*. Springer Verlag, 2008.
    [\[E-Book-ENG\]](http://dx.doi.org/10.1007/978-3-540-85268-1)
-   S. Brenner and L. Scott. *The mathematical theory of finite element
    methods*. Springer Verlag, 2008.
    [\[E-Book-ENG\]](http://dx.doi.org/10.1007/978-0-387-75934-0)
-   D. Boffi, F. Brezzi, L. Demkowicz, R. Durán, R. Falk, and M.
    Fortin. *Mixed finite elements, compatibility conditions, and
    applications*. Lectures given at the C.I.M.E. Summer School held in
    Cetraro, Italy June 26–July 1, 2006. Springer Verlag, 2008.
    [\[E-Book-ENG\]](http://dx.doi.org/10.1007/978-3-540-78319-0)
-   D. Arnold. *A concise introduction to numerical analysis*. Institute
    for Mathematics and its Applications, Minneapolis, 2001.
    [\[E-Book-ENG\]](http://www.ima.umn.edu/~arnold/597.00-01/nabook.pdf)
-   A. Quarteroni, F. Saleri, P. Gervasio.* Scientific Computing with
    Matlab and Octave*. Springer Verlag, 2006.
    [\[E-Book-ENG\]](https://link.springer.com/book/10.1007/978-3-642-12430-3)
-   B. Gustaffson* Fundamentals of Scientific Computing, *Springer,
    2011
    [\[E-Book-ENG\]](https://link.springer.com/book/10.1007/978-3-642-19495-5)
-   Tveito, A., Langtangen, H.P., Nielsen, B.F., Cai, X. *Elements of
    Scientific Computing, *Springer, 2010
    [\[E-Book-ENG\]](https://link.springer.com/book/10.1007/978-3-642-11299-7)

Note that, when connecting from SISSA, all of the text books above are
available in full text as pdf files.

# Instructions for git aware students (and [MHPC](http://www.mhpc.it) students)

This repository contains, assignements, workspaces, and other material for the course P1.4

New material will be uploaded frequently,

Remember to set a second remote, either to our private seed

	git remote add P1.4_seed https://github.com/luca-heltai/numerical-analysis-2021-2022.git

or (if using ssh keys in your github account)

	git remote add P1.4_seed git@github.com:luca-heltai/numerical-analysis-2020-2021.git

and to update before the lectures:

	git pull P1.4_seed master

**Please consider contributing pull requests to correct typos, or better document the material in this repository!**

# Licencing

The content of this repository is distributed with a Creative Common licence. See
the file LICENCE.md in this directory for more information.

# Attribution

Some of the material in this repository was adapted from the python-lectures by [Robert Johansson](https://github.com/jrjohansson/scientific-python-lectures). Take a look at his repository for additional material and lectures.
