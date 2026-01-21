# Option Pricing

## Assumption:

- $S_0 = 50$ (Current Stock Price)
- $\sigma = 0.3$ (Volatility)
- $K = 52$ (Strike Price)
- $T = 2$ (Time to Maturity)
- $r = 0.05$ (risk-free rate)
- $q = 0$ (Non-Dividend Paying Stock)

## Formulas:

- $u = e^{\sigma \sqrt{\Delta{t}}}$ ( $S_0u$ will be the stock price after one time step with probability of p)
- $d = e^{-\sigma \sqrt{\Delta{t}}}$ ( $S_0d$ will be the stock price after one time step with probability of 1-p)
- $p = \frac{e^{r\Delta{t}}-d}{u-d}$
- $f = e^{-r\Delta{t}}\left[pf_u + (1-p)f_d\right]$ ( Option price )

## Calculation of u,d,p for different time steps

<img width="500" height="100" alt="image" src="https://github.com/user-attachments/assets/1b8ba4df-2669-45b5-9aee-3fe5b81295a4" />

## Pricing European Option

<img width="450" height="200" alt="image" src="https://github.com/user-attachments/assets/98dbe31b-7113-466a-828e-4b156489966b" />

## Comparison Between BS model and Binomial model

<img width="450" height="250" alt="image" src="https://github.com/user-attachments/assets/c6c72877-dc9f-4d8c-b01f-bf37550d8944" />

## Pricing American Option

<img width="400" height="75" alt="image" src="https://github.com/user-attachments/assets/ac87fb77-7df9-479e-8745-3a4a76dc230c" />

## Probability of different terminal stock price

<img width="500" height="280" alt="image" src="https://github.com/user-attachments/assets/6fdd989c-6ea5-4656-84d4-d68522bcbfbd" />

<img width="500" height="280" alt="image" src="https://github.com/user-attachments/assets/d29514de-4268-42b7-bf88-6605cbc1f7e2" />

<img width="500" height="280" alt="image" src="https://github.com/user-attachments/assets/119cd297-8afe-4431-89f8-0bc33c05f969" />



