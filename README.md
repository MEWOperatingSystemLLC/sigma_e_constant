# sigma_e_constant
Kendi yarattığım matematiksel sabit.
# Efe Constant – σₑ
A newly defined oscillatory trigonometric constant discovered by **Ali Efe Bağcı (Prof. Ali Efe Edition)**.

---

## 📘 Definition
The **Efe Constant**, denoted by **σₑ**, is defined as the infinite series:

\[
\sigma_e = \sum_{n=1}^{\infty} \frac{\sin(\sqrt{n})}{n}
\]

This series is **conditionally convergent**, non-elementary, and numerically estimated as:

\[
\sigma_e \approx 1.7184141118...
\]

---

## 🧮 Mathematical Context
The term \(\sin(\sqrt{n})\) behaves pseudo-random due to the irrational phase of \(\sqrt{n}\).  
Combined with the \(1/n\) decay, σₑ forms a non-trivial oscillatory constant similar in style to:

- Euler–Mascheroni constant γ  
- Catalan's constant G  
- Clausen-type constants  
- Polylogarithmic special values  

---

## 🔬 Applications
- Oscillatory series analysis  
- Asymptotic expansions  
- Random-like trigonometric behavior  
- Benchmarking numerical summation methods  
- Studies of pseudo-random sequences in signal analysis  
- Trigonometric exponential sum bounds  

---

## 📊 Numerical Value
Using high-precision numerical summation up to N=1,000,000:

\[
\sigma_e \approx 1.718414111831...
\]

(See `sigmae.py` for reproducible computation.)

---

## 📁 Repository Contents

