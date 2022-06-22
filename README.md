# STATEMENT-DISBURSMENT-RECONCILIATION
This Reconciliation has to do with an overview.

THE QUESTION:
Overview of PYS Disbursement Process.      
To facilitate disbursements, PYS works with different processors depending on the destination account and reliability of processors. These processors receive instruction from PYS server to complete a disbursement then they respond with the status of the transfer (success, failed, forfeited, null) and simultaneously debit the bank account linked to the integration for only successful transfers. Where a transfer was not successful, the processor is required to ensure the sum was reversed – if initially debited.

PROMT
Using the excel data provided in the file attached, kindly reconcile the disbursements for February 2021 transactions debited in the bank account provided. Also summarize the data to be shared with our processor for exceptions – exceptions consist of instances where a disbursement was not debited once. For example, a N200 transfer that failed, debited but not reversed will be an exception. However, note that if that transfer was reversed, it won’t be an exception.Please prepare a summary table detailing your findings to be shared with the processor.

ANALYSIS          
So, basically, This is to show the process (as an analyst) at which the data was cleaned and providing solutions to below:1) Reconciliation of transaction debited in the bank account provided (3..Transactions reconciled file),
2) Data with exceptions to be shared with the processor.(5.. Failed transactions with exceptions file),
3) A summary detailing my findings (6 ..Findings summarized)
4) The data for the Bank statement and disbursement as seen and attached were first joined using the ACCESS APP and power Query. then were exported to Microsoft excel , where the data was cleaned. After the cleaning, I used excel to sort and filter for successful transaction , Failed and debited transactions with their reversals and transactions that were failed and debited without reversal. The essence of the analysis is to find out the transactions that were failed and debited without a reversal so that it can be reconciled by the processor. The named files attached shows the file to be sent to the processor for them to reverse accordingly.

From the 109,680 data reviewed, it was discovered that 33,089 failed, 2705 were forfeited, 14 transactions are pending and 73,872 were successful and as such the failed transactions will be returned to the process for refund and escalation. Out of the 33k transactions that failed, about 2,260 were automatically reversed and will not be escalated.

