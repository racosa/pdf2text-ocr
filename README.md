# pdf2text-ocr

[pdf2text-ocr](https://racosa.github.io/pdf2text-ocr/) is a simple tool for converting PDF to text using OCR. Files are converted locally in the browser and are never uploaded to external servers.

It can be useful if you are getting gibberish when copying and pasting text from PDF ([example](https://superuser.com/questions/137824/pdf-has-garbled-text-when-copy-pasting)), specially if you don't want to or cannot use a cloud-based solution.

## Demo

Input: [file1.pdf](https://github.com/racosa/pdf2text-ocr/blob/main/file1.pdf)

Output:

```
reporting on a non-cash basis. As the last FBT year started before the GST was introduced an amount paid for
a benefit received over this particular FBT year 1™ April 2000 to 31" March 2001 should be amortised over
the period the benefit was provided to see if there is a pre GST portion on which no GST will be payable.

Unfortunately the ruling only looks at the limited circumstances of employees who are not owners of the
company. Many of our clients own companies or trusts of which they are employees. They don’t pay fringe
benefits tax because they make employee contributions to cancel out the benefit. Many clients may not even
be fully aware of this because until now the entry has been made by journal entry by the accountant when the
tax return is done. This is permitted to be done retrospectively under ruling MT2050. GSTR2001/3 accepts
that the employee can make a contribution after the end of the FBT year and have it apply to that year. So in
order to be technically correct the journal, when made should not be back dated as it has been in the past but
dated the date it is made. This way it can be correctly recorded in the BAS for the period when the accountant
is doing the work. Just make sure you get this information for your BAS. We have had the above approach
confirmed by the NTAA and ATO.

The above probably applies to you if your vehicle is owned by a trust or company and you are not in the
‘maximum tax bracket, or if an employee makes contributions to you.

In Short What to do Now:

If you have employees who make actual contributions during the year and you prepare your BAS on a cash
basis you will have to enter these amounts on the BAS for each period they are received. If you prepare your
BAS on a non-cash accruals basis you have to include all the future payments when the first one is received or
you issue a bill or the goods are supplied unless the total amount is uncertain. This should not be a problem if
the contribution is for goods as they have been supplied so the amount should have been set. The problem
arises when a car is provided on an ongoing basis. There seems to be a good argument here that the total
amount is not certain so the contribution only needs to be included when it is received or the journal entry
made. In the latter case where you are at risk of missing this one off entry as it does not go through the
cashbook. So if you are preparing your own BAS don’t forget to ask you accountant for this amount when the
business income tax return is done.

Some employees will be making an annual contribution in the June quarter as in most cases this is the
quarter when the liability is calculated for the FBT return. The fringe benefit calculation for motor vehicles
based on the formula method is reasonably simple. So once shown by your accountant you should be able to
do it yourself in future years. But note when the car has been held for more than 4 years, at the beginning of
the FBT year, the cost base in the formula is reduced to 2/3rds of the original cost. If you are accounting for
the car on a log book basis the fringe benefit calculation is much more complex.

Methods of Finance and GST

If you are reporting for GST on a cash basis and purchase an item under hire purchase you can only claim
the GST input credit on the principle portion of each repayment when it is made. A better scenario is to
borrow the money under a normal loan agreement or chattel mortgage so you can claim the full input credit
for the acquisition at the time you take out the loan.

Offsetting Non Commercial Losses Against Other Income

These provisions are explained in Newsflash 11. Note the concessions for primary producers have been
extended to Artists and Professional Sports People. If you fail the test in Newsflash 11 the losses are
quarantined but can be offset against future profits from the business. In order to be able to claim these losses
in future years they must be recorded in the income tax return for the year in which they are actually incurred
even though they cannot be claimed as a deduction. Accordingly, it is still necessary for you to bring in the
information regarding these businesses.

Motor Vehicle Purchases & GST
Please make sure when purchasing a motor vehicle that you obtain a Tax Invoice if you wish to claim back the
GST for business purposes. The Purchase Contract does not constitute a Tax Invoice.
Created by Julia Hartman B.Bus CPA - Tax Accountant -7
```

## How it works

Each page of the PDF is converted to an image using [PDF.js](https://mozilla.github.io/pdf.js/) and each image is converted to text using [Tesseract.js](https://github.com/naptha/tesseract.js). The results are displayed in the browser allowing users to copy the text, search, etc.
