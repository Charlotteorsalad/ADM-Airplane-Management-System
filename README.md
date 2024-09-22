# ADM-Airplane-Management-System
Advanced Database Management Assignment

<h2>Project Description</h2>
<p>This project was developed as part of our university assignment for <strong>Advanced Database Management</strong>. The aim is to develop a series of SQL procedures, queries, triggers, and reports for managing and analyzing data related to airplane management systems using SQL and PL/SQL.</p>

<h2>Team Members</h2>
<ul>
  <li><strong>Me: Kam Bee Foong</strong>
  <li><strong>Teammate 1: Ooi Yi Xuen</strong>
  <li><strong>Teammate 2: Ho Jun Min</strong>
  <li><strong>Teammate 3: Hee JingXi</strong>
  <li><strong>Teammate 4: Tan Kok Wang</strong>
</ul>

<h2>Project Structure - Individual Code Files</h2>
<ul>
  <li><strong>src/</strong>: Contains Stored procedures and triggers.
    <ul>
      <li><code>Procedure1-Get_Insurance_Claim_Details.txt</code>: Stored procedure to fetch insurance claim details.</li>
      <li><code>Procedure2-Validate_Upgrade_Request.txt</code>: Stored procedure to validate flight class upgrade requests.</li>
      <li><code>Trigger1-Auto_Update_Membership_Level.txt</code>: Trigger to automatically update membership levels.</li>
      <li><code>Trigger2-Update_Flight_Availability.txt</code>: Trigger to update flight availability after booking status is updated.</li>
    </ul>
  </li>
  <li><strong>reports/</strong>: Contains PL/SQL-based reports.
    <ul>
      <li><code>Report1-Booking_Cancellation_and_Refund_Analysis_Report.txt</code>: Analysis report on booking cancellations and refunds.</li>
      <li><code>Report2-Aircraft_Maintenance_and_Operational_Cost_Analysis_Report.txt</code>: Analysis report on aircraft maintenance and operational costs.</li>
    </ul>
  </li>
  <li><strong>queries/</strong>: Contains SQL queries and views.
    <ul>
      <li><code>Query1-Item_and_Customer_Segmentation_Analysis.txt</code>: SQL query for item and customer segmentation analysis.</li>
      <li><code>Query2-Member_Engagement_and_Value_Over_Time.txt</code>: SQL query for member engagement and value analysis over time.</li>
    </ul>
  </li>
</ul>

<h2>How to Run</h2>
<ol>
  <li>Ensure you have access to an Oracle or compatible SQL database environment.</li>
  <li>First, run the table schema and data insertion files to set up the database:
    <ul>
      <li>Run <code>schema/TableSchema.sql</code> to create the tables.</li>
      <li>Run <code>schema/DataInsertion.sql</code> to insert the sample data into the tables.</li>
    </ul>
  </li>
  <li>Next, upload or copy the SQL files from the <code>src</code>, <code>queries</code>, and <code>reports</code> folders into your SQL workspace.</li>
  <li>Execute the SQL files in the following order:
    <ul>
      <li><strong>Procedures</strong>: 
        <ul>
          <li><code>Procedure1-Get_Insurance_Claim_Details.txt</code></li>
          <li><code>Procedure2-Validate_Upgrade_Request.txt</code></li>
        </ul>
      </li>
      <li><strong>Triggers</strong>: 
        <ul>
          <li><code>Trigger1-Auto_Update_Membership_Level.txt</code></li>
          <li><code>Trigger2-Update_Flight_Availability.txt</code></li>
        </ul>
      </li>
      <li><strong>Queries</strong>:
        <ul>
          <li><code>Query1-Item_and_Customer_Segmentation_Analysis.txt</code></li>
          <li><code>Query2-Member_Engagement_and_Value_Over_Time.txt</code></li>
        </ul>
      </li>
      <li><strong>Reports</strong>:
        <ul>
          <li><code>Report1-Booking_Cancellation_and_Refund_Analysis_Report.txt</code></li>
          <li><code>Report2-Aircraft_Maintenance_and_Operational_Cost_Analysis_Report.txt</code></li>
        </ul>
      </li>
    </ul>
  </li>
</ol>

<img src="https://github.com/user-attachments/assets/31ca1441-6d3d-4d0f-867c-5c9e7edf5b69" alt="image" width="500"/>



<h2>Output</h2>










<h3>Example 1: Procedure1-Get_Insurance_Claim_Details</h3>
<p>This procedure will fetch details about an insurance claim and related claims within the last 24 months.</p>

<pre>
Claim ID:    12345
Date:        12-JUN-2023
Amount:      RM1000
Status:      Completed
Reason:      Flight Delay
Coverage:    Full
Premium:     RM100
Passenger:   John Doe
Flight:      F12345
Route:       Kuala Lumpur to Singapore
Departure:   12-JUN-2023 14:30

Related Claims:
Claim ID    Date       Amount     Status     Reason
----------------------------------------------------
12346       12-JAN-2022 500       Completed  Luggage Delay
----------------------------------------------------
</pre>

<h3>Example 2: Trigger1-Auto_Update_Membership_Level</h3>
<p>The trigger will update a member's level based on their points after a points change.</p>

<pre>
Trigger fired: Membership level updated to Silver for Member ID: MEM12345.
</pre>

<h3>Example 3: Report1-Booking Cancellation and Refund Analysis</h3>
<p>This report shows booking cancellations and refunds over a selected date range.</p>

<pre>
| Month     | Total Bookings | Cancellations | Rate(%)  | Refund Amount | Trend  |
| --------- | -------------- | ------------- | -------- | ------------- | ------ |
| JAN-2024  | 500            | 20            | 4.00%    | RM 5000.00    | +2%    |
</pre>

<h3>Example 4: Query1-Item and Customer Segmentation Analysis</h3>
<p>This query analyzes customer demographics and item purchases over the past 24 months.</p>

<pre>
| State   | Gender | AgeGroup | ItemName    | TotalQuantitySold | TotalRevenue |
| ------- | ------ | -------- | ----------- | ----------------- | ------------ |
| Selangor| Male   | 25-34    | Laptop      | 50                | RM 100,000   |
</pre>

<h2>License</h2>
<p>This project is part of a university assignment and is not intended for commercial use.</p>
