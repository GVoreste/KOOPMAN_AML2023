# Deep learning for universal linear embeddings of nonlinear dynamics “Koopman operator”

### Project for the Advance Machine Learning 2023 course

> * Authors:    **Alessandro Mollicone**, [**Giuliano Verrando**](https://github.com/GVoreste)
> * Professor:  [**Stefano Giagu**](https://github.com/stefanogiagu)
> * Assistant:  **Andrea Ciardello**
> * University: **["Sapienza Universita' di Roma"](https://www.phys.uniroma1.it/fisica/)**
> * Academic Year: **2022-2023**

---

---

The purpose of the project was to try to replicate the results of the work done in this [PAPER](https://www.nature.com/articles/s41467-018-07210-0), in which the authors focus on developing DNN representations of Koopman eigenfunctions that remain interpretable and parsimonious, even for high-dimensional and strongly nonlinear systems. All data and methodologies can be reconstructed using the code available at [GIT](https://github.com/BethanyL/DeepKoopman).

The authors make available all the data providing some matlab script to generate it or downloading it from [here](https://anl.app.box.com/s/9s29juzu892dfkhgxa1n1q4mj63nxabn).

> **N.B.** our Network notebook expect to find the data in a directory called `data` in the same location of the Network itself

The systems analized by the authors are:

1. a sytem with **discrete spectrum**
2. a **fluid flow** in a box
3. a **fluid** placed under the influence of an **attractor**
4. a non linear **pendulum**

this are all examples of non linear dynamics.
