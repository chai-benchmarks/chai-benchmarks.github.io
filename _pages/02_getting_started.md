---
layout: page
title: Getting Started
permalink: /gettingstarted/
---

  Clone the repository:

  ```
  git clone https://github.com/chai-benchmarks/chai.git
  cd chai
  ```

  Export environment variables:

  ```
  export CHAI_OCL_LIB=<path/to/OpenCL/lib>
  export CHAI_OCL_INC=<path/to/OpenCL/include>
  ```

  Select desired implementation:

  ```
  cd OpenCL2.0
  ```

  Select desired benchmark:

  ```
  cd BS
  ```

  Compile:

  ```
  make
  ```

  Execute:

  ```
  ./bs
  ```

  For help instructions:

  ```
  ./bs -h
  ```

