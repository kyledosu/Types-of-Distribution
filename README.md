# Types-of-Distribution

Performance Task
Modeling and Simulation
Normal Distribution
Formula:
  z = (x - μ) / σ

Problem:
  The average height of adult men is 175 cm with a standard deviation of 10 cm. What is the probability that a randomly selected man is taller than 185 cm?

Solution:
  z = (185 - 175) / 10 = 1
  From a Z-table, P(Z > 1) = 0.1587
  So, there's a 15.87% chance a man is taller than 185 cm.
Poisson Distribution
Formula:
  P(X = k) = (λ^k × e^(-λ)) / k!

Problem:
  At 5 PM, an average of 3 cars pass per minute. What is the probability that exactly 5 cars pass in one minute?

Solution:
  P(5) = (3^5 × e^(-3)) / 5! = 243 × e^-3 / 120 ≈ 0.1008
Exponential Distribution
Formula:
  P(T ≤ t) = 1 - e^(-λt)

Problem:
  On average, a bus comes every 10 minutes (λ = 1/10). What’s the probability it arrives within 5 minutes?

Solution:
  P(T ≤ 5) = 1 - e^(-0.1 × 5) = 1 - e^-0.5 ≈ 0.3935
  So, there's a 39.35% chance.

  So, there's a 10.08% chance.

Binomial Distribution
Formula:
  P(X = k) = C(n, k) × p^k × (1 - p)^(n - k)

Problem:
  What is the probability of getting exactly 3 heads in 5 coin flips (p = 0.5)?

Solution:
  P(3 heads) = C(5, 3) × 0.5^3 × 0.5^2 = 10 × 0.125 × 0.25 = 0.3125
  So, there's a 31.25% chance.

Beta Distribution
Formula:
  Beta(α, β) where α = heads + 1, β = tails + 1

Problem:
  You flip a coin 10 times and get 7 heads and 3 tails. What is your estimate of the probability of heads?

Solution:
  Beta(8, 4) → mean = α / (α + β) = 8 / (8 + 4) = 0.6667
  Estimated probability of heads ≈ 67%.

Logarithmic Distribution
Formula:
  P(X = k) = -1/ln(1 - p) × (p^k / k), for 0 < p < 1

Problem:
  You model rare sightings of a rare owl with p = 0.3. What’s the probability of spotting exactly 2 in a year?

Solution:
  P(2) = -1 / ln(1 - 0.3) × (0.3² / 2) = 1.357 × 0.045 = 0.061
  About 6.1% chance.




Trigonometric Distribution 
Use: von Mises distribution (circular normal)

Problem:
  If crime happens most at 2 AM and follows a circular pattern, what’s the chance it happens close to 2 AM?

Solution:
  Use von Mises centered at θ = 2 AM with a concentration κ. The mode is at 2 AM, and probability falls symmetrically.
  Highest probability is near 2 AM, lowest near 2 PM.
  Formula: f(θ) = (1 / 2πI₀(κ)) × e^(κ cos(θ - μ))

Weibull Distribution
Formula:
  P(t) = (k/λ) × (t/λ)^(k - 1) × e^-(t/λ)^k

Problem:
  A phone model has λ = 2 years and k = 1.5. What is the probability it fails before 1 year?

Solution:
  P(T < 1) ≈ 1 - e^-(1/2)^1.5 ≈ 1 - e^-0.353 ≈ 1 - 0.702 = 0.298
  About 29.8% chance of failing in the first year.

Gamma Distribution
Formula:
  f(x; α, β) = (β^α x^(α−1) e^−βx) / Γ(α)

Problem:
  You wait for 3 buses. Each bus arrives randomly at an average of 10 minutes (β = 0.1). What’s the probability they all come within 20 minutes?

Solution:
  Use Γ(3) = 2! = 2
  P(x < 20) ≈ use gamma calculator → About 0.857
  85.7% chance all buses arrive within 20 minutes.


Uniform Distribution
Formula:
  P(x) = 1 / (b - a + 1)

Problem:
  What is the probability of rolling a 4 on a fair six-sided die?

Solution:
  P(4) = 1 / 6 = 0.1667 → 16.67% chance.



Video Link: https://drive.google.com/drive/folders/1xGUvYr4Pid1b807K4LQV3FjhqVfhKqkT?usp=sharing 
