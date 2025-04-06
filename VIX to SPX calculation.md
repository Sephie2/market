**1. Estimating Daily SPX Move Using VIX:**

- **Formula**: Daily Expected Move= $\frac{\text{VIX}}{\sqrt{252}}$
    _Note_: There are approximately 252 trading days in a year.​

- **Example Calculation**: If the VIX is at 45:​ $\frac{45}{\sqrt{252}} \approx \frac{45}{15.87} \approx 2.84$

This suggests an expected daily move of about ±2.84% in the SPX.​


**2. Estimating Intraday SPX Move Using VIX1D:**

The VIX1D measures expected volatility specifically for the current trading day. To estimate the intraday move:​
- **Formula**: Intraday Expected Move=$\frac{\text{VIX1D}}{\sqrt{T}}$
    _Note_: T represents the fraction of the trading day remaining. For a full day, $T=1$; for half a day, $T=0.5$, etc.​

- **Example Calculation**: If the VIX1D is at 81 and the full trading day is ahead:​   $\frac{81}{\sqrt{1}} = 81$​

This indicates an expected intraday move of about ±81% in the SPX, which is exceptionally high and suggests extreme market volatility.​


