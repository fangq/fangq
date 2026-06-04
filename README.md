Some random thoughts related to programming

- Small is beautiful! This is a Unix philosophy that every programmer should be reminded of!
- To me, it is a "crime" to write a program that can only run on a specific OS or platform. I would never start a project on a toolchain that only runs on Windows or Mac.
- I hate slow programs. That's why I use the GPU for MC simulations, that's why I prefer the adjoint method for Jacobians, and that's also why I love OpenMP so much — because it is the cheapest way to make a program fast.
- Be "lazy": let the computer do everything, including:
  - you **have to** know how to use a code formatter (`astyle`, `mh_style`, `black`/`blue`, `perltidy`) to consistently reformat your code before every commit
  - you **have to** enable warnings — `-Wall` or even `-pedantic` — to let the compiler do the hard work and tell you which parts it considers problematic, and fix every warning
  - if you don't know how to create automated testing to verify code features and detect regressions after each commit, you are outdated
  - you **have got to** know how to use a memory checker (`valgrind`, `cuda-memcheck`, `compute-sanitizer`)! It is THE simplest way to expose serious issues right in front of your eyes without asking much of you — this is the least you can do: FIX EVERY MEMORY ERROR!
  - to make your code fast, **you'd better** know how to use a profiler (`valgrind --tool=cachegrind`, `Kcachegrind`, `ncu`, `nvprof`); in most cases, your slow runtime is likely due to a few lines of inefficient code, and you need to find them
- The best way to learn a programming language is to learn it when you need it. You can't learn it by reading a book.
- Understanding and respecting open-source licenses is the VERY first step for anyone interested in doing open-source software.
- Do not despise FORTRAN — it was, and still is, the backbone of modern numerical computing, and MATLAB was built on it (MATLAB's matrix slicing with `:` came from FORTRAN).
- Fonts are the #1 visual element in a modern graphics environment. They are more visible than window borders, shadows, and your wallpapers. Almost all graphics-savvy users start by designing their own fonts because they are tired of the ordinary ones.
- Call me old school — the VCL (Visual Component Library) and CLX libraries behind the Delphi/C++Builder/Kylix IDEs are still the best UI library design I have ever seen. Even after 30 years, there is still nothing as intuitive, clean, and beautiful as that — LCL for Lazarus is close (because it follows VCL), but it does not support C++ the way CLX did.
- Use open-source whenever you can! It is perpetual (and so is the license that lets you use it).
- Do not always chase the newest and shiniest frameworks. Use something that has endured the test of time. They have lasted for decades, and they will continue to survive for decades.

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
