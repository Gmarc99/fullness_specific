# fullness_specific
Complete vision for inbounding and outbounding of specific items
<p>Schemas, Tables, Columns and Values are changed from the original ones to avoid sensitive data being released outside the company</p>
<p>Tool used:</p>
<ul>
    <li>SQL, ETL Oracle</li>
    <li>Excel, Power Query</li>
</ul>
<p>This project has been created for particular instances of fullness on specific items.</p>
<p>To have a complete vision there are 2 ETL&nbsp;Queries with weekly automated refreshes:</p>
<ul>
    <li>The first one returns the Inventory quantity and the Shipment Pipeline at the Item level. We can so analyze the Outbound possibility compared with the Inventory at Annual metric(Inventory Turns).</li>
    <li>The second one returns the Inbound Arrival for those specifics at the Item level.</li>
</ul>
<p>The 2 Pipeline is extracted 2 times with Power Query, to have the vision with different granularity: Appointment level and Item Level.</p>
<p>We create the Pivot Tables where we will extract all the data in a report page with the function GETPIVOTDATA</p>
<p><br></p>
<p>ACHIEVEMENTS</p>
<p>We decreased the overall Fullness of these specific items by 14% in 2 weeks.</p>
<p>The Inbounding of&nbsp; Low Turning items was decreased for 2 weeks.</p>
<p>The report helps in reducing the Fullness without affecting the availability of High Sales product</p>
<p><br></p>
