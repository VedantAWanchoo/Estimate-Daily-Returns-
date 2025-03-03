Our fund admin reports the official NAV / returns on a monthly basis.

However, we also want official daily data for internal calculations etc.

Our PMS platform would give us a daily return / NAV estimate.

However, there is always a difference between the daily estimate from PMS and the offical NAV from admin at month end.

Hence, I built a small code that solves this differnece.

We compare the daily estimate from the PMS platform with the official monthly numbers from the fund admin.

Then we adjust the daily PMS number so that the daily numbers match the official fund admin numbers.

I made this pre ChatGPT, so you might see loops instead of vectorization.

I have not attached input files for confidentiality.
