# PT-Family-distribution

1. Exponential Distribution (Earthquakes)
Problem:
200 earthquakes occurred in 40 years (480 months). Find P(wait ≥3 months for next earthquake).

Solution:

Calculate rate: λ = 200/480 = 0.4167 earthquakes/month

P(X > 3) = e^(-λx) = e^(-0.4167×3) = e^(-1.2501) ≈ 0.2865

Answer: 28.65% chance

2. Normal Distribution (Metal Rods)
Problem:
Rods: μ=100cm, σ=2cm. Find P(X < 96cm).

Solution:

Z-score = (96-100)/2 = -2

P(Z < -2) = 0.0228

Answer: 2.28% probability

3. Poisson Distribution (Bakery Sales)
Problem:
Average=3 cakes/hour. Find P(exactly 5 cakes in next hour).

Solution:
P(X=5) = (e^(-3) × 3^5)/5! = (0.0498×243)/120 ≈ 0.1009

Answer: 10.09% chance

4. Binomial Distribution (Quiz Guessing)
Problem:
10 questions, 4 choices each. Find P(3 correct guesses).

Solution:
P(X=3) = C(10,3) × (0.25)^3 × (0.75)^7 = 120 × 0.015625 × 0.1335 ≈ 0.25

Answer: 25% probability

5. Triangular Distribution (Delivery Time)
Problem:
Delivery times: min=30, mode=45, max=90 mins. Find P(X ≤60).

Solution:
P(X≤60) = 1 - [(90-60)²/((90-30)(90-45))] = 1 - (900/2700) ≈ 0.6667

Answer: 66.67% chance

6. Lognormal Distribution (Reading Time)
Problem:
Reading time: μ=3.2, σ=0.5 (log-scale). Find P(X <30 mins).

Solution:

ln(30) ≈ 3.401

Z = (3.401-3.2)/0.5 ≈ 0.402

P(Z < 0.402) ≈ 0.656

Answer: 65.6% probability

7. Gamma Distribution (Customer Arrivals)
Problem:
Customers: shape k=1, rate λ=0.2. Find P(X >10 mins).

Solution:
P(X>10) = e^(-λx) = e^(-0.2×10) = e^(-2) ≈ 0.1353

Answer: 13.53% chance

8. Beta Distribution (Basketball Free Throws)
Problem:
Success rate follows Beta(2,2). Find P(p <0.5).

Solution:
∫(0 to 0.5) 6p(1-p) dp = 0.5

Answer: 50% probability

9. Weibull Distribution (Battery Life)
Problem:
Battery life: shape β=2, scale η=100 hours. Find P(T >80).

Solution:
P(T>80) = e^(-(80/100)^2) = e^(-0.64) ≈ 0.5273

Answer: 52.73% chance

10. Uniform Distribution (Bus Waiting Time)
Problem:
Buses every 15 mins. Find P(wait <5 mins).

Solution:
P(X<5) = 5/15 ≈ 0.3333

Answer: 33.33% probability
