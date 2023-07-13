# Deep learning for universal linear embeddings of nonlinear dynamics “Koopman operator”

### Project for the Advance Machine Learning 2023 course

> * Authors:    **Alessandro Mollicone**, [**Giuliano Verrando**](https://github.com/GVoreste)
> * Professor:  [**Stefano Giagu**](https://github.com/stefanogiagu)
> * Assistant:  **Andrea Ciardello**
> * University: **["Sapienza Universita' di Roma"](https://www.phys.uniroma1.it/fisica/)**
> * Academic Year: **2022-2023**

---

---

The purpose of the project was to try to replicate the results obtained in this [PAPER](https://www.nature.com/articles/s41467-018-07210-0), in which the authors focused on developing DNN representations of Koopman eigenfunctions that remain interpretable and parsimonious, even for high-dimensional and strongly nonlinear systems. All data and methodologies can be reconstructed using the code available at [GIT](https://github.com/BethanyL/DeepKoopman).

The authors make available all the data providing some matlab scripts to generate them. Alternatively, is possible to download them from [here](https://anl.app.box.com/s/9s29juzu892dfkhgxa1n1q4mj63nxabn).

> **N.B.** our Network notebook expects to find the data in a directory called `data` in the same location of the Network itself

The systems analized by the authors are:

1. A system described by a **discrete spectrum**
2. A **fluid** flowing in a **box**
3. A **fluid** flowing on an **attractor**
4. A non-linear **pendulum**

These are all examples of non-linear dynamics.
