<!DOCTYPE html>
<html lang="en">
<head>
<style>
  :root {
    --background-1: #f0f4f7;
    --background-2: #dfe6ea;
    --background-3: #e2e8ec;
    --background-4: #e0eaf1;
    --text-color-1: #2f2f2f;
    --text-color-2: #444444; 
    --highlight-1: #3f3dc2;
    --highlight-2: #2d69c2;
    --highlight-3: #58a6ff;
    --highlight-4: #98e2d6;
    --highlight-5: #c2a6e2;
    --shadow: rgba(0, 0, 0, 0.1);
}
body {
  background-color: var(--background-2);
  color: #2f2f2f;
}
.logo {
  background-color: var(--background-3);
}
.card-container {
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  display: flex;
  gap: 1rem;
  padding: 1rem;
}
.card {
  background-color: var(--background-3);
  border-radius: 10px;
  border-color: var(--background-1);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  padding: 1rem;
  transition: transform 0.2s, box-shadow 0.2s;
}
.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
}
.card h3 {
  color: var(--text-color-1);
  margin: 0;
  font-size: 1.5rem;
}
.card h3 {
  margin: 0.5rem 0 0;
  color: #555;
}
#one h3 {
  color: var(--highlight-1);
}
#two h3 {
  color: var(--highlight-2);
}
#three h3 {
  color: var(--highlight-3);
}
#four h3 {
  color: var(--highlight-4);
}
#five h3 {
  color: var(--highlight-5);
}
.text {
  background-color: var(--background-4);
  color: var(--text-color-2)
}
</style>
</head>
<body>
<div class="logo">
<a href="https://polarity-lang.github.io/">
    <p align="center">
        <img alt="The polarity logo" src="https://raw.githubusercontent.com/polarity-lang/artwork/88e3b8f9e4c87a0baf6a0a61f0a7e5e9f1d757a2/logo_transparent.svg" width=30%>
    </p>
</a>
<h1 align="center">Polarity</h1>
<p align="center"><strong>A programming language with dependent data and codata types.</strong></p>
<p align="center">
    <a href="https://polarity-lang.github.io/">
        <img src="https://img.shields.io/website-up-down-green-red/http/polarity-lang.github.io" alt="Website">
    </a>
    <a href="https://github.com/polarity-lang/polarity/actions/workflows/ci.yml">
        <img src="https://github.com/polarity-lang/polarity/actions/workflows/ci.yml/badge.svg" alt="Rust CI">
    </a>
    <a href="https://app.codecov.io/gh/polarity-lang/polarity">
        <img src="https://codecov.io/gh/polarity-lang/polarity/branch/main/graph/badge.svg" alt="Codecov Coverage">
    </a>
</p>
</div>
<div class="card-container">
        <div class="card" id="one">
          <h3>Card 1</h3>
        </div>
        <div class="card" id="two">
          <h3>Card 1</h3>
        </div>
        <div class="card" id="three">
          <h3>Card 1</h3>
        </div>
        <div class="card" id="four">
          <h3>Card 1</h3>
        </div>
        <div class="card" id="five">
          <h3>Card 1</h3>
        </div>
    </div>
</div>
<div class="text">
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
<p>Curabitur pretium tincidunt lacus. Nulla gravida orci a odio. Nullam varius, turpis et commodo pharetra, est eros bibendum elit, nec luctus magna felis sollicitudin mauris. Integer in mauris eu nibh eu
</div>
</body>
</html>