
<h1>Stock and Company identification API - Finnworlds</h1>

<p><a href="https://finnworlds.com/finance-data/stock-and-company-identification-numbers-api/">Stock and company identification API</a> 
is a useful tool that lets you pull stock ticker and company information from our database through JSON REST API and our databases are also downloadable as an excel or csv file.
You can use the Stock and Company Identifiers API to access an active and up-to-date database without having to collect and maintain a huge amount of data from multiple sources yourself. 
The API is expanded regularly as we add new stocks and exchange traded funds in the database. 
You can access to the Stock and Company Identifiers API without having to continuously worry about the quality and the quantity of the data you are using to develop your project. 
Better focus results in better quality projects.</p>

<p><a href="https://finnworlds.com/">Finnworlds</a> has clients of all sizes. Mostly we work directly with developers who develop platforms for their clients but we also partner with inhouse development teams. Either way we have a package for every size of business</p>




<p><a href="https://finnworlds.com/pricing">Sign up for an API key</a> to get started with the data right away. We don't have free packages on the website but for students we can do something. Just email us and lets talk about it.</p>



<h2>API Features</h2>



<ul><li><strong>Company name</strong></li>
<li><strong>Stock ticker symbol</strong></li>
<li><strong>ISIN Identifier</strong></li>
<li><strong>CUSIP Number</strong></li>
<li><strong>CIK Code</strong></li>
<li><strong>Employer ID / EIN</strong></li></ul>

Aside with this data comes other related information such as industry and sector, IPO date, financial reporting dates and more.

<h2>How to access the data</h2>



<ul><li><strong>JSON rest API</strong></li><li><strong>Excel CSV download</strong></li><li><strong>PDF reports</strong></li><li><strong>Email link</strong></li></ul>



<h2>Documentation</h2>



Our <a href="https://finnworlds.com/documentation">documentation</a> includes input parameters, output objects with explanation of their meaning, we also provide clear examples on the documentation page of various endpoints and their output. On top of this we have SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala</p>


<h2>Examples</h2>




<p>https://finnworlds.com/api/v1/identifiers?key=YOUR-KEY&stock_ticker_symbol=aapl</p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "cik_code": "0000320193"
            "cusip_number": "037833100"
            "employer_id": "942404110"
            "exchange": "nasdaq"
            "ipo_date": "1980:11:12"
            "founded_date": "1976:04:01"
            "industry": "technology"
            "sector": "consumer electronics"
        }
    [


The API can filter on each identifier, to obtain all other identifiers of the company you are interested in.



<h2>Customer Support</h2>

<p>Need help, have questions? <a href="mailto:support@finnworlds.com">Get in touch with Support</a>.</p>

<h2>Legal</h2>

<p>Use of the Finnworlds website, services like API and database are subject to the&nbsp;<a href="https://finnworlds.com/legal/terms-and-conditions-on-finnworlds-data/">Finnworlds terms &amp; Conditions</a></p>
