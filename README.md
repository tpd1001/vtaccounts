# Payroll Instructions

## Scratch

speak to hmrc
code from reference file

part renovation, part new
80% dwelling, 20 non dwelling
when submit plan, we put in "this is a new dwelling"
council will look and agree proportion
builder will invoice with vat for the renovation part

## Online

Available as a [README](https://github.com/tpd1001/vtaccounts/blob/main/README.md)

## Prerequisites

* Install RemotePC software
* Access 1Password, Viji Vault

## RemotePC

* Login to MRST-NEW-PC (Viji's main machine, if she's not using it)
* Failing that, use MRST-NEW-PC2
* START > Moneysoft > Payroll Manager
* File > Open
* T:\Moneysoft Payroll\2023-24

## T Drive

* `T:\clientdatabase_vandt_(Recovered).xlsx` > companies tab
  * submitted black, to do red
  * D in column A means a dormant company
    * confirmation statement once a year
      * further info in `companieshouse.docx`
  * ACS tab contains accounting periods for each client
    * accounts (acs) sent to client for approval
    * year end in black not ended
    * in red means accounts to be prepared
* `T:\joblist\2024joblist.xlsx` containing spreadsheet (2023/24) with task lists
* `T:\PAYE\payroll details controll2021.xlsx`

## OneDrive

Important locations:

* `ODT_Shared\PAYE\payroll details controll2021.xlsx`
* `ODT_Shared\Clients Ref*\Reference.xlsx` (see **Spreadsheet** in **Viji** vault in **1Password**)

## Calendar

Tom created a Google calendar, to be populated with key events going forward:
[VT Accounts Calendar](https://calendar.google.com/calendar/embed?src=1d886704ad858bd897308ae0220cca5bf10f6e39bbd01a945fc6ff277e4a2e9f%40group.calendar.google.com&ctz=Europe%2FLondon)

## Employers

See spreadsheet (client database presumably)

Do the full process for each employer in turn

### The Blue Cow

T drive folder: `T:\Clients\The Blue Cow\`
Weekly + monthly - RTI on month
P30/Tax summary wk 13 (~5th)
Payslips: adam(at)thebluecowbutchers(dot)com tbc

### Robert & Edwards Limited

T drive folder: `T:\Clients\R&E Ltd -R591\`
Payroll, stick to weekly routine
P30/Tax summary wk 13 (~5th)
Payslips: info(at)robertandedwards(dot)com tbc

* All weekly paid employees need to be on a round number for Net Pay
* N.B. Net + Pension = Round Number

It seems that we also need to ensure that some monthly employees are on a round number (2500) for Net Pay

* Julia Lawrence
* Claire Hewitt

### FOLIOS

T drive folder: `T:\Clients\Folios-F221\`
`ODT_Shared\Clients\Folios-F221\PAYE`
Payslips: sales(at)folios???.com
Send payslips by 20th, wait a few days, then do RTI
Monthly RTI on or before last Tuesday in month
Send P30 & Tax Summary immediately after you do the RTI
NEST whenever we send payslips

#### Abnormal Pension Payments

I've gone back to the historical abnormal pension payments and discovered that they were made done as follows:

- edit the May's employee pension to add the extra from the employer (£5000 in this case)
- first submit the normal RTI and save the PDF with an added suffix of "(with May's pension)"
- go back and unlock the record that the RTI locks
- remove the added 5000
- make the NEST pension contribution submission
- re-add the 5000
- finally relock the record

Then you have to go to NEST and do the following:

- make the normal pension schedule payment
- then create an exception schedule (see screenshot)
  - source: Direct Debit
  - reason: Payment not covered by a contribution
  - option: excess contributions for this tax year (member with opt-out rights)
- add May as a member to the schedule
- add the payment amount
- submit for payment

#### Pension

3% of basic pay
2022-23 payroll

### CH Meats

T drive folder: `T:\Clients\CH Meats & CA Hewitt\`
`ODT_Shared\Clients\CH Meats & CA Hewitt\PAYE`
Weekly RTI, send 4/5 payslips
Payslips: rhewitt339(at)btinternet(dot)com

P30/Tax summary wk 13 (~5th)

PAYE month ends 5th of month
`www.gov.uk` > HMRC services > sign in

If only weekly payroll have to pay liability weekly
monthly+weekly is pay liability monthly

employer NI 4k per year you don't have to pay (employer's allowance)

### USP

Gregory's company (Unique Surfaces Plus Limited)
no pension (husband & wife only)
Payslips: jola(at)usplus(.)co(.)uk

* Check P30 & Tax summary
* Should only be any liability in month 12 at end of FY
* Say 1000/month to avoid employer/employee NI
* Due by approx last day of the month

`ODT_Shared\Clients\UNIQUE SURFACES PLUS\PAYE`

### Tiny Computers

No pay currently.

* Monthly, currently nil-RTI, by 26/27th of the month
* Except around March/April
  * then what?

`ODT_Shared\Clients\TinyPltd-T710\PAYE`

### J.S.Kudail & Sons

No basic pay until end of year, then client tells how much in March - typically 15000, but confirm.

* Monthly nil-RTI, by last day of the month
* Annually something... payslips?
  * Tax PAYE run in March (and P30/tax summary?)
  * You **MUST** also check in April that things are back to Nil RTI
    * Payroll Manager, trying to be helpful, tries to start the new FY with the same pay as the end of the previous
  * Check in HMRC Online PAYE that figures match and that Tax has been paid
    * Check in April, search for "www.access.service.gov.uk" in password manager beginning 304

`ODT_Shared\Clients\JSK & Sons 356\PAYE`

### V&T

PAYE scheme kept open.

* Monthly nil-RTI, by last day of of the month
* Except July, typically 9000
* When you do a non-nil RTI, you need to force payslip before
  * This is to avoid the calculation thinking you are on a regular salary

`ODT_Shared\Clients\V&T LTD\PAYE`

### Lumbini

PAYE scheme to be closed?

* Monthly nil-RTI, by 5th of the month

`ODT_Shared\Clients\Athuraliyage Lumbini A009\PAYE`

### Viztec

Dormant
Year end 31/01/2024

File confirmation statement with Companies House
> is company trading status on stock market
> PSC changes
> any director changes
tick box & submit

payment: credit card or *by account*
presenter ID & presenter authentication code from from client database spreadsheet
no need for customer reference

Then file company accounts
> file dormant company accounts

## Employer NI

13.8% over 9000

## Reference

`T:\Clients....\Reference.xlsx` (password is "Spreadsheet" in 1Password)

Contains email addresses, phone numbers etc.

## Company year end

Companies House sends email

* from Inform Direct
* n

Then you can submit your accounts

Go to companies house and search for when Accounts and Confirmation Statement due

Companies house> File confirmation statement
email address tangam (at) vtaccounts.co.uk

Web Filing?

Your companies

## next

* MENU: Employees
* select, Payment tab
* Employer details e.g. PAYE ref, account ref etc.

Analysis: reports for pay details

Employees summary for current period (toolbar button)

* if weekly payroll, still have to send to HMRC monthly

### to run payroll

*Do this the week before* RTI is due

* click pound sign button or **Pay** > **Pay Details** (Ctrl-D)
  * pay Net, not gross
  * has to add up to a round number of pounds e.g. 452.08 + 17.92 = 470.00
* click on each employee in turn (you can click on the names tabs row)
  * ignore if monthly (`mmm-YYYY`)
  * check if weekly   (`Wk ##`)
* Click main menu bar yellow envelope button (with no tick) or **Pay** > **Employee's Payslip**
* Click **All** then **OK**
* Check ???
* Click the red Acrobat save as PDF button
* Save to a single PDF file
* save payslip to:
  * `T:\Clients\The Blue Cow\PAYE\2023-24`

#### RTI

1. Click red RTI button or **Pay** > **Employer's RTI schedule** (Ctrl-D)
1. Locate the line with status **due now**
1. Click **View / File**
1. For weekly payroll, double check that **Total Net Pay** + **Employee Pension Contributions** (or **Deductions**) add up to a whole number of pounds
1. Click the very thin **Click to file this return online to HMRC** (at top of sub-window)
1. Click **Start** and wait for all green ticks
1. Click **OK** then **Check for responses**
1. When you get a Succeeded, click **OK** then **Close**
1. Click the red Acrobat save as PDF button
1. Save response PDF to `T:\Clients\<>\PAYE\2023-24\RTI` (tbc)

Robert&Edwards - SAVE AS SINGLE PDF

Next steps:

* submit RTI to HMRC
* submit pension to nest site
* check for emails
  * Adam Lawrence (director of blue cow)
    * adam (at) thebluecowbutchers.co.uk
  * Robert Huey (operational) (Robert&Edwards?)
    * info (at) robertandedwards.co.uk
* when receive email - save statement etc. into T drive
  * `T:\Clients\<>\Accts\ye230824\bank\cc` (creditcard)
* also VAT return
  * ask for PDF + electronic and cross-reference (PDF more reliable)
  * or
  * `T:\Clients\<>\PAYE`

#### Monthly Payroll

* on 22nd of month onwards
* they setup a DD (payroll compliance) on 28th?
* payslip date must be before payment date
* Dec, payroll from 15th onwards as pay made ~ 1 week early

* click payroll, click **PDF** button, save on T: drive
* click **RTI** on main menu -> view/File
* submit to HMRC

#### Weekly Payroll

* from employer, via employer summary
  * click P30, monthly (RTI before 19th of month)
* RTI weekly to HMRC by end of Fri (reasonable excuse)
* check response is successful
* save response PDF to `T:\Clients\The Blue Cow\PAYE\2023-24\RTI` (tbc)

#### P30 and Tax Summary

before 5th month (EMP,P30) - send to client (to submit & pay to HMRC by 17th)

1. Open Payroll file
1. Click **Pay Details** (£) button or **Pay > Pay Details**
1. Select the most recent locked week/month
1. Click **P30** button or **Pay > P30**
1. Click **PDF** button, save on T: drive in **PAYE\P30** folder
1. Click **TAX** button or **Pay > Tax Summary** (not for current period)
1. Click **PDF** button, save on T: drive in **PAYE\Tax summary** folder

* CH Meats - monthly, often no liability
* Folios - monthly
* blue cow - monthly
* R&E - monthly
* V&T - monthly, should be nil except March
* tiny - nil under normal circumstances
* lumbini - nil
* USP - monthly, should be no liability except month 12
* JSK - **annual payroll only**, after 15th of March

### PENSION

Google search: nest pension login
<https://nestpensions.org.uk>

In Moneysoft Payroll Manager

1. Previous week locked submission
1. week 41 pension = week 42 RTI = week 43 payslips
1. From the main menu
1. **pension** > **generate upload files** > **NEST** > **contributions**
1. Double check that the **Employee Contributions** matches the Pay Details
1. Note down the **Total Contribution** figure
1. Click the very thin **Click to here file this return online to NEST** (at top)
1. Click **Start** and wait for all green ticks
1. Click **OK** then **Check for responses**
1. When you get a Succeeded, click **OK** then **Close**
1. no need to see/save reply
1. No need to save PDF
1. Leave payroll open & launch Microsoft Edge
1. Go to Nest pension site <https://nestpensions.org.uk>
1. Login (creds are saved in browser)
1. Scroll down to **Your employer accounts**
1. Click the arrow in the **View** column for the client in question
1. Click **Manage contributions**
1. N.B. Pension contributions are always 1 week behind (to avoid long delay in case of payroll change)
1. Click the arrow in the **Edit/Pay** column for the top row (nearest payment due date)
1. Double check that the **Member Contributions** matches the Pay Details figure from payroll
1. Click **Submit schedule**
1. pay now, confirm

Kannan 5-6pm (traveling) 6pm Canada (-5hrs UK) Mon&Fri

before 5th month (EMP,P30) - send to client (to submit & pay to HMRC by 17th)

### Send payslips to client

* tbc

---

tasks

1. Do payroll
1. main menu bar > payslip
1. pension + netpay = 470
1. net-to-gross pay > target net pay 470 > don't use figure because of pension deduction
1. WRONG put net pay into excel * 0.04 for pension
1. net pay * 0.96 for 4% pension
1. put in 452.08 an accept basic pay (yes)
1. tweak to get pension and net as desired
1. every 4 weeks or so, he basic pay changed because of personal allowance runs out
1. ultimately, make sure net+pension = 470.00
1. Submit RTI to HMRC
1. ?

## Spreadsheet

Use to record submissions, payroll, pension
`T:\PAYE\payroll details control2021.xlsx`

## Year End

1. Complete the final FPS
1. Complete the year end EPS
1. Export the P60s
    1. one per employee
    1. select "Exclude Leavers"
1. Run the script below for each client from their folder
    1. Launch "Git Bash"
    1. Change to the "Clients" folder: `cd ~/OneDrive*Accountants/ODT_Shared/Clients`
    1. Change to each client in turn e.g. `cd The*Blue*Cow`
    1. Patch the script `sed -i 's/25/26/g;s/24/25/g;s/23/24/g' ../make_new_fy_dirs.txt`
    1. Or edit the script `vim ../make_new_fy_dirs.txt` and increment all the FY numbers by one
    1. Run the script `bash ../make_new_fy_dirs.txt`
1. Create the new FY folder for Moneysoft Payroll
    1. e.g. `mkdir ~/OneDrive*Accountants/ODT_Shared/Moneysoft*Payroll/2025/26`
1. "Click here to create a file for next year" and click "OK"
1. Tick the box to change details and click "OK"
1. Change the folder to "Moneysoft Payroll/2025-26" and click "Save"

```bash
tbc
```

## Other Notes

Sage Cloud (reconciliation/bookkeeping)
3 Clients
bring report from sage:
cash in

electronic or bank statement import

month by month -> reconcile

these not going through the bank - how was it paid? get client to confirm?
they send credit card statements sometimes too

---

MRST-NEW-PC2

## PAYE Notices

Tools > Downloads PAYE Notices > Check for new notices

* Check monthly for all clients or every 2 months
* If there are changes:
  * Theck if the client already forwarded a copy of their "notice of coding change" letter
  * If not, contact the client and ask for a copy of the HMRC letter to under stand why
  * If deemed all ok, select employee and click apply

tax code adjustment before calculating net/goss pay

check pay copied over from week 53 to week 1

net-to-gross target button and enter 500

## Other

John Read - plus others

basic pay increase because tax code changes
need notice from HMRC for why code was changed
please confirm if you want us to apply the new code
