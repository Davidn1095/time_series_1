# time_series_1

### Lognormal Process
- **Origin:** Associated with the deterministic Malthusian model.
- **Characteristics:**
  - Based on the exponential growth curve.
  - Used in fields such as Ecology, Economics, and Marketing.
  - Stochastic model that incorporates random fluctuations.
- **Stochastic Differential Equation:**
  - \[
    dX(t) = mX(t)dt + \sigma X(t)dW(t)
    \]
  - with \(\sigma > 0\) and \(W(t)\) representing the standard Wiener process.
- **Distribution:**
  - Univariate lognormal.
  - Transition density function based on the Fokker-Planck equation.

### Gompertz Process
- **Origin:** Associated with the deterministic Gompertz model.
- **Characteristics:**
  - Applied in the study of human mortality law and population growth.
  - Stochastic model with bounded growth.
- **Stochastic Differential Equation:**
  - \[
    dX(t) = (\alpha - \beta \ln X(t))X(t) dt + \sigma X(t)dW(t)
    \]
  - with \(\alpha, \beta > 0\) and \(\sigma > 0\).
- **Distribution:**
  - Lognormal with time-dependent parameters.
  - Transition density function reflects bounded growth.

### Gompertz-Type Process
- **Origin:** Derived from the Gompertz model and adapted to other phenomena.
- **Characteristics:**
  - Double exponential, suitable for bounded growth.
  - Variability in the limit depending on the initial value.
- **Stochastic Differential Equation:**
  - \[
    dX(t) = h(t)X(t)dt + \sigma X(t)dW(t)
    \]
  - Function \(h(t)\) represents the growth rate, dependent on time.
- **Distribution:**
  - Non-homogeneous lognormal.
  - Characteristics adjustable according to the function \(h(t)\).
