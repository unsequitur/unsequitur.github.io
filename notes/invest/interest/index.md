---
layout: page
title: Interest Rates
weight: 3
---
When economists talk about interest rates in the economy, they refer to the 
interest rates on a broad class of government-issued securities ranging from 
the one month T-bill to the ten year Treasury note. Since these interest
rates often move together, it is convenient to talk about the trends associated
with interest rates in general.

When we talk about interest rates, we must make a distinction between two types
of interest rates: real and nominal rates. The nominal interest rate $$R$$ 
refers to the interest that is promised on the face of the bond/bill. For 
example, if you purchase a bond that promises to pay 5% of its face value as 
interest each year, the the nominal interest rate in this case is 5%.

On the other hand, the real interest rate accounts for the loss in purchasing 
power of the currency due to inflation. If the same bond as before is issued 
in a country with 2% annual inflation (say, $$i$$), then the nominal interest 
rate $$r$$ can be approximately computed as $$r \approx R-i =$$3%. The exact
relationship between the real and nominal interest rates is given as

\begin{equation}
\label{eq:rnom}
r = \frac{1+R}{1+i}
\end{equation}

Equation ($$\ref{eq:rnom}$$) becomes exact when all the rates are continuously
compounded. We can re-arrange the approximate equation to the slightly more
useful form

\begin{equation}
\label{eq:rnom_mod}
R = r+i
\end{equation}

Since the interest rates are forward looking (they refer to future cash
flows), the inflation in equation ($$\ref{eq:rnom_mod}$$) must be replaced
by _expected_ inflation, which results in Fischer's equation

\begin{equation}
\label{eq:fischer}
R = r + E[i]
\end{equation}

Before we can discuss how the nominal interest rates are computed, we must
understand the factors that influence the real interest rate and the 
expected inflation rate.

The real interest rate is decided based on supply
and demand. The supply in this case refers to wealth from household savings,
while the demand arises from industries with capital requirements. Apart from
these forces, the government (and the federal reserve) can intervene and
skew the real interest rates. As the rate of interest offered increases, 
investors are willing to invest larger amounts. This manifests in an upward
sloping supply curve. Higher interest rates might discourage industries from
borrowing, which results in a downward sloping demand curve. The intersection
of these curves determines the real interest rates.

The government has the ability to shift the supply and demand curves via
suitable government actions. It can increase demand by starting 
capital-intensive projects like highway constructions, which can increase
the budget deficit. The federal reserve
can manipulate the supply by adopting an "expansionary monetary policy"
(one popularly known supply manipulation technique
is quantitative easing, which we shall discuss at the end). Thus, the 
government can manipulate the interest rates to any degree that it may desire.
Indeed, the federal reserve has been committed to a policy of stable inflation
rates since the 1980's[1]. 

The expection inflation $$E[i]$$ serves as a discount factor for all future 
cash flows from the Treasury bill, and cannot be predicted easily. Varying 
expectations of inflation cause the prices of different Treasury bills to
fluctuate, providing speculative opportunities to global macro traders. 

Since Treasury bills and notes are considered to be risk-free (at least in the
US), one may be tempted to ask: why should I expect to get anything more than
a zero real rate from a riskless investment. The reason here is that the

<h5>References:</h5>

1. BKM
2. [American Enterprise Institute](http://www.aei.org/article/economics/fiscal-policy/what-determines-interest-rates/)
3. [PF & Investing](http://pfinvesting.com/2007/10/19/interest-rate/)
