
Science Report
Lorem ipsum dolor sit amet, consectetuer adipiscing elit









Your Name
09/04/20XX


Some of the tabs having hide and show condition depends on those condition tabs can be hide and show back on document add edit page.

Document Product
Apart from normal crud operation from document product. We do also have calculation of pension fund and withholding tax calculation along with the document calculation.
Based on percentage of pension fund and withholding.
Basically there are two types of product exist in document one is there is type 0 and 1.
Basically we calculate document row without tax for each of the product and later after one type 1 we calculate pension fund over on that and also we do apply tax on pension fund.
Another operation followed by document product pension fund is withholding tax that is gets subtracted from document.





Document payment Row:

Top left selector is for selecting the payment installation previously done payment type.
Which use cases is to get the payment installment row for example it’s like 30, 45, 25 percentage each, so based on that payment is divided into multiple part rows and can be paid later on selected dates, which is further days from the document is being created.
Along with that there is also an option to select wallet in payment row itself. Last checkbox denotes , checked checkbox denotes to made payment immediately. Also the last delete option denotes to delete row of payment.
There is also an alert to notify that the payment total is the sum of total payment rows amount is greater or less than the normal document calculation, Also we can add our custom rows of payment in payment table.
 
Document address: 
Another tab  to enter or feed the information about the two address of delivery to customer, both address shows the billing and shipping of product.
Document file
Another tab is responsible for uploading the files correspond to document and to show the document from sdi received invoice.
Sdi Tab
The last tab is called sdi , which is used to fire and event sending documents to sdi server. This button is visible only in edit mode of document. Also there are some fields which are used to send on sdi server. The table below shows the list of xml files which are sent to the sdi and received from sdi.

Document buttons
Search Product button
This button used to fetch multiple products in multiple rows in document products. Here we use the same document rows , the rows we fetch is fetched directly from products row we would saved previously, the tax percentage it takes from the product details as well.
The document calculation is based on price, quantity, tax, discount of product row.
Generate Document button
Generate document shows the popup to generate the same invoice with another type of document option available currently. Once we select particular document type from the list, it will render another document number based on document date and document type written in earlier sections.
Clone Document
The clone document button renders another invoice with or from getting reference from this invoice details and payment but without the customer used in document.
Once the user saves the document it behaves like a normal document.

Print document
Print document button ask for template to print documents in format and immediate after selecting document template, the submit button prints document in pdf format.

Is canceled
Is canceled checkbox, this checkbox takes value is canceled or not value in database.





Document page
Document page consist of document list with pagination with filter of month and year in document page.
The top select box in document is responsible for selecting the document type , based on that the page renders that particular type of document.
The column details of list is easy to understand and which is not easily understandable is document total and document left to pay.
The last column it would consist would be the sdi icon which depends on the last sdi notification sent or received to or from sdi document.
Apart from document list it fetches the details of first invoice details and show the payment over on right side bar.
There are some few options available on generate, duplicate, stamp and another modify which is already explained earlier.

The list of document type on document page can be customised from company option page.

