
html_content = """\
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invoice Bill</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; padding: 20px; }
        table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        th, td { border: 1px solid #000; padding: 10px; text-align: left; }
        th { background-color: #f2f2f2; }
        .center { text-align: center; font-weight: bold; }
    </style>
</head>
<body>
    <h2 class="center">Invoice Bill</h2>
    <table>
        <tr><th>Invoice No.</th><td>VE/24-25/02</td></tr>
        <tr><th>Invoice Date</th><td>01.06.2024</td></tr>
        <tr><th>State</th><td>Dadra & Nagar Haveli</td></tr>
        <tr><th>State Code</th><td>26</td></tr>
        <tr><th>Place of Supply</th><td>Pipariya, Silvassa</td></tr>
    </table>

    <h3>Billing Details</h3>
    <table>
        <tr>
            <th>SR. NO.</th><th>PARTICULARS</th><th>HSN/SAC</th>
            <th>AMOUNT</th><th>CGST @9%</th><th>UTGST @9%</th><th>TOTAL</th>
        </tr>
        <tr>
            <td>1</td><td>Machine Loading & Shifting (Crane)</td><td>997319</td>
            <td>27000</td><td>2430</td><td>2430</td><td>31860</td>
        </tr>
    </table>

    <h3>Summary</h3>
    <table>
        <tr><th>Total Amount Before Tax</th><td>27000</td></tr>
        <tr><th>CGST @ 9%</th><td>2430</td></tr>
        <tr><th>UTGST @ 9%</th><td>2430</td></tr>
        <tr><th>Total Tax Amount</th><td>4860</td></tr>
        <tr><th>Total Billing Amount</th><td>31860</td></tr>
        <tr><th>Total Amount in Words</th><td>Thirty-One Thousand Eight Hundred and Sixty Only</td></tr>
    </table>

    <h3>Bank Details</h3>
    <table>
        <tr><th>Bank Name</th><td>Bank of Baroda</td></tr>
        <tr><th>Account Number</th><td>50840200000868</td></tr>
        <tr><th>IFSC</th><td>BARB0SILSIL</td></tr>
    </table>
</body>
</html>
