# travis_qmake_gcc_cpp98_coverity

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp98_coverity.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp98_coverity)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++98`
 * Libraries: `STL` only
 * Code coverage: none
 * Source: one single file, `main.cpp`

More complex builds:
 * Use of C++11: [travis_qmake_gcc_cpp11_coverity](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_coverity)
 * Use of C++14: [travis_qmake_gcc_cpp14_coverity](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity)

More complex builds:
 * No Coverity Scan: [travis_qmake_gcc_cpp98](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98)
