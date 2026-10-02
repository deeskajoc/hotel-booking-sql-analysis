# Hotel Booking Analysis with SQL

Analysis of guest booking and cancellation behaviour using SQL and Python (pandas, SQLite).

**Data:** "Hotel Booking Demand" dataset from Kaggle (about 119,000 bookings from a city hotel and a resort hotel). Download the CSV from Kaggle to run the notebook.

**Tools:** Python, SQL (SQLite), pandas, Jupyter

## Questions and findings
1. **Cancellations by hotel type:** City Hotel [42]% vs Resort Hotel [28]%.
2. **Repeat guests:** returning guests cancelled less often ([14]% vs [37]%), but they are a small share of bookings.
3. **Special requests:** more special requests were associated with fewer cancellations ([48]% with none vs [22]% with one).
4. **Lead time:** cancellations increased as the time between booking and arrival grew.

## Ideas for guest engagement
Re-engaging past guests, treating special requests as an engagement signal, and contacting early bookers before arrival could help reduce cancellations. These are associations in the data, not proven causes.
