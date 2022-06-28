# BitbillTester
Tests how many Bitcoin Bitbill still are untouched

The addresses of the Bitbills are known and will never change so they're hardcoded.
The program then checks through an API what the balance is of those addresses.
If the API no longer works or somehow limits the number of searches, you can easily update it to a new one.

Output in 6/2022 shows:

Bitbill tester:
Total bitbills=928
1BTC=589, 5BTC=144, 10BTC=107, 20BTC=88
Checking 589 Bitbill 1 BTC...00%..10%..20%..30%..40%..50%..60%..70%..80%..90%..100%..done
Checking 144 Bitbill 5 BTC...00%..10%..20%..30%..40%..50%..60%..70%..80%..90%..100%..done
Checking 107 Bitbill 10 BTC...00%..10%..20%..30%..40%..50%..60%..70%..80%..90%..100%..done
Checking 88 Bitbill 20 BTC...00%..10%..20%..30%..40%..50%..60%..70%..80%..90%..100%..done
Bitbill 1 BTC: total=589, untouched=320
Bitbill 5 BTC: total=144, untouched=51
Bitbill 10 BTC: total=107, untouched=31
Bitbill 20 BTC: total=88, untouched=37
