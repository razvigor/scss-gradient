# SCSS Gradient Exercises

## Table of Contents

- Introduction
- Linear Gradient
- Repeating Linear Gradient
- Radial Gradient
- Repeating Radial Gradient
- Conic Gradient
- Repeating Conic Gradient
- Animated Repeating Conic Gradient

## Introduction

Welcome to the SCSS Gradient Exercises. These exercises will help you understand and practice various types of gradients in SCSS, including linear, radial, conic, and their repeating and animated versions.

## Linear Gradient

### Exercise 1: Basic Linear Gradient

**Objective:** Create a linear gradient background.

**Example:**
```scss
body {
  background: linear-gradient(to right, #ff7e5f, #feb47b);
}
```
## Repeating Linear Gradient
### Exercise 2: Repeating Linear Gradient
### Objective: Create a repeating linear gradient background.

**Example:**

```scss
body {
  background: repeating-linear-gradient(
    45deg,
    #ff7e5f,
    #ff7e5f 10px,
    #feb47b 10px,
    #feb47b 20px
  );
}
```
## Radial Gradient
### Exercise 3: Basic Radial Gradient
### Objective: Create a radial gradient background.

**Example:**

```scss
body {
  background: radial-gradient(circle, #ff7e5f, #feb47b);
}
```

## Repeating Radial Gradient
### Exercise 4: Repeating Radial Gradient
### Objective: Create a repeating radial gradient background.

**Example:**
```scss
body {
  background: repeating-radial-gradient(
    circle,
    #ff7e5f,
    #ff7e5f 10px,
    #feb47b 10px,
    #feb47b 20px
  );
}
```

## Conic Gradient
### Exercise 5: Basic Conic Gradient
### Objective: Create a conic gradient background.

**Example:**
```scss
body {
  background: conic-gradient(from 0deg, #ff7e5f, #feb47b);
}
```

## Repeating Conic Gradient
### Exercise 6: Repeating Conic Gradient
### Objective: Create a repeating conic gradient background.

**Example:**
```scss
body {
  background: repeating-conic-gradient(
    from 0deg,
    #ff7e5f 0deg,
    #feb47b 30deg
  );
}
```

## Animated Repeating Conic Gradient
### Exercise 7: Animated Repeating Conic Gradient
### Objective: Create an animated repeating conic gradient background.

**Example:**
```scss
@keyframes rotate {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

body {
  background: repeating-conic-gradient(
    from 0deg,
    #ff7e5f 0deg,
    #feb47b 30deg
  );
  animation: rotate 5s linear infinite;
}
```
