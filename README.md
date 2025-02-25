<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="Duckdb Dbt" />

  &#xa0;

  <!-- <a href="https://duckdbdbt.netlify.app">Demo</a> -->
</div>

<h1 align="center">Duckdb Dbt</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/vikasgrover2/duckdb-dbt?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/vikasgrover2/duckdb-dbt?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/vikasgrover2/duckdb-dbt?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/vikasgrover2/duckdb-dbt?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/vikasgrover2/duckdb-dbt?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/vikasgrover2/duckdb-dbt?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/vikasgrover2/duckdb-dbt?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  Duckdb Dbt 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/vikasgrover2" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

Describe your project

## :sparkles: Features ##

:heavy_check_mark: Feature 1;\
:heavy_check_mark: Feature 2;\
:heavy_check_mark: Feature 3;

## :rocket: Technologies ##

The following tools were used in this project:

- [Expo](https://expo.io/)
- [Node.js](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have following installed 
- [Git](https://git-scm.com) 
- [Make]
  ```bash
  choco install make
  ```

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/vikasgrover2/duckdb-dbt

# Access
$ cd duckdb-dbt

# Build the base spark image
$ ~\github\duckdb-dbt> docker build . -t spark-base

# To start the spark cluster
$ make run-scaled

# A 2 worker spark cluster should now be available at http://localhost:9090/

# To test a sample job
make submit app=word_non_null.py
# This will start a job that can be see under the completed applications

# To stop the cluster
$ make down
```

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.

&#xa0;

<a href="#top">Back to top</a>
