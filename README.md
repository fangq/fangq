Some random thoughts related to programming

- Small is beautiful! This is a Unix philosophy that should be reminded for every programmer!
- To me, it is a "crime" to write a program that can only run on a specific OS or platform. I would never start a project on a toolchain that only runs on Windows or Mac.
- I hate slow programs. That's why I use GPU for MC simulations, that's why I prefer the adjoint method for Jacobians, that's also why I love OpenMP so much because it is the cheapest way to make a program fast.
- Be "lazy": Let the computer do everything, including
  - you **have to** know how to use code formatter (`astyle`, `mh_style`, `black`/`blue`, `perltidy`) to consistently reformat your code before every commit
  - you **have to** enable warnings `-Wall` or even `-pedantic` to let the compiler do the hard work and tell you which part it considers problematic, and fix every warning
  - if you don't know how to create automated testing to verify code features and detect regression after each commit, you are outdated
  - you **got to** know how to use memory checker (`valgrind`, `cuda-memcheck`, `compute-sanitizer`)! it is THE simplest way to expose serious issues in front of your eyes without asking you to do much, this is the least you can do - FIX EVERY MEMORY ERROR!
  - to make your code fast, **you'd better** know how to use a profiler (`valgrind --tool=cachegrind`, `Kcachegrind`, `ncu`, `nvprof`); in most cases, your slow runtime is likely due to a few lines of inefficient code, you need to find them
- Best way to learn a programming language is to learn it when you need it. You can't learn it by reading a book.
- Understand and respect open-source license is the VERY first step for anyone who is interested in doing open-source software
- Do not despise FORTRAN - it was, and still is the backbone of modern numerical computing, and MATLAB was built on it (MATLAB's matrix slicing with `:` came from FORTRAN)
- Fonts are the #1 visual elements in a modern graphics environment. It is more visible than window borders, shadows, and your wallpapers. Almost all graphics-savvy users start with designing their own fonts because they are tired of the ordinary ones.

<!--
**fangq/fangq** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
