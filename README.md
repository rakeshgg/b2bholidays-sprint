# README

## How to Run `main.py` and Insert XML Data

Please follow the steps below to run the `main.py` file and insert XML data:

### Steps:

1. **Navigate to the `src` directory:**  
   ```sh
   cd src
   ```

2. **Open `main.py` and insert your XML in the `xml_input` variable.**  
   Example:
   ```python
   xml_input = """<AvailRQ>
       <timeoutMilliseconds>25000</timeoutMilliseconds>
       <source>
           <languageCode>en</languageCode>
       </source>
       <optionsQuota>25</optionsQuota>
       <Configuration>
           <Parameters>
               <Parameter password="pass123" username="user123" CompanyID="123"/>
               <Parameter password="pass123" username="user123" CompanyID="123"/>
           </Parameters>
       </Configuration>
       <SearchType>Multiple</SearchType>
       <AvailDestinations>
           <Destination>New York</Destination>
           <Destination>London</Destination>
       </AvailDestinations>
       <StartDate>15/10/2025</StartDate>
       <EndDate>18/10/2025</EndDate>
       <Currency>USD</Currency>
       <Nationality>US</Nationality>
       <Market>ES</Market>
       <Paxes>
           <Pax type="Adult"/>
           <Pax type="Child" age="5"/>
       </Paxes>
       <Paxes>
           <Pax type="Adult"/>
       </Paxes>
   </AvailRQ>"""


3. **Run the `main.py`
   ```sh
   python main.py
   ```

