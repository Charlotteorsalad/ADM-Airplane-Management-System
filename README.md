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

<h2>Entity-relaationship Diagram</h2>
<img src="https://github.com/user-attachments/assets/31ca1441-6d3d-4d0f-867c-5c9e7edf5b69" alt="image" width="500"/>

<h2>Project Outputs</h2>

<h3>1. Queries</h3>
<h4>Query1: Item and Customer Segmentation Analysis</h4>
<p><strong>Purpose:</strong> This query helps identify key customer demographics and their purchasing behavior by analyzing the items purchased over a specific period. It provides insights into how different customer segments (based on state, gender, and age group) interact with different product categories followed by market basket analysis.</p>
<p><strong>Insights:</strong> This data can be used to design targeted marketing campaigns. For example, the high quantity of laptop purchases among young males in Selangor suggests a tech-savvy demographic that might respond well to promotions for electronics. Tailoring product recommendations based on these insights can lead to higher conversion rates and increased revenue.</p>

<img src="https://github.com/user-attachments/assets/b29c6fbf-94db-4481-b009-5193afd713a0" alt="image" width="500"/>

<h4>Query2: Member Engagement and Value Over Time</h4>
<p><strong>Purpose:</strong> This query tracks member engagement and spending behavior over the last 24 months. It helps evaluate the relationship between membership level and the financial value generated by each member.</p>
<p><strong>Insights:</strong> The data shows that members with higher membership levels (like Platinum) tend to make more bookings and generate more revenue, making them prime candidates for loyalty rewards and exclusive offers. This insight supports the idea of investing in premium loyalty programs and personalized offers to further increase engagement and spending among high-tier members.</p>

<img src="https://github.com/user-attachments/assets/8153c26a-69b0-469f-a613-5b76443268dc" alt="image" width="500"/>

<h3>2. Stored Procedures (SP)</h3>
<h4>Procedure1: Get Insurance Claim Details</h4>
<p><strong>Purpose:</strong> This procedure retrieves detailed information about a passenger's insurance claim, including coverage type, claim reason, and related claims within the last 24 months. It helps in evaluating claim validity and historical claim trends for passengers.</p>
<p><strong>Insights:</strong> This data can assist in identifying passengers who frequently file claims, potentially indicating fraud risks or operational issues that should be addressed. Businesses can adjust their insurance policies to better manage risk and reduce claim payouts by analyzing claims over time.</p>

<img src="https://github.com/user-attachments/assets/0aeff28b-6c9a-45bf-9b0d-2be91eff9662" alt="image" width="500"/>

<h4>Procedure2: Validate Upgrade Request</h4>
<p><strong>Purpose:</strong> This procedure checks whether a passenger is eligible to upgrade their flight class based on available points, seat availability, and flight status. It automates the validation process for upgrade requests.</p>
<p><strong>Insights:</strong> Automating the upgrade validation process improves operational efficiency and enhances customer satisfaction by speeding up upgrade approvals. Insights from upgrade data can also help airlines refine their loyalty programs and better manage seat inventory, ensuring that premium seats are utilized effectively.</p>

<img src="https://github.com/user-attachments/assets/86410806-f1b9-4af8-8d90-27f39af00578" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/ef4356dd-5285-4a63-94dd-e42914f4ca2c" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/aa2caf27-6590-48ae-8386-4dbfa06ef28f" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/3b269f6c-9602-453a-bfdf-3648a71d8029" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/8d25e8b8-a3a4-4ecf-b234-d03dbd2de89c" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/c453924e-32cd-466f-a66f-b9fe6b8f9172" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/e5f8d16d-1881-4f39-812a-d744f5bc435a" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/fed78b05-cb1f-4df1-b540-bc91c0ec9224" alt="image" width="500"/>

<h3>3. Triggers</h3>
<h4>Trigger1: Auto Update Membership Level</h4>
<p><strong>Purpose:</strong> This trigger automatically updates a passenger's membership level based on the accumulation of points. It ensures that loyalty program members are rewarded with the correct level without manual intervention.</p>
<p><strong>Insights:</strong> Automating membership level updates allows the business to respond dynamically to customer engagement, incentivizing higher spending through tiered benefits. It also ensures the loyalty program remains competitive and rewards frequent flyers appropriately, fostering long-term customer loyalty.</p>

<img src="https://github.com/user-attachments/assets/e68895d7-77d1-4f62-a570-f04ae31750b0" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/db6acdc9-63c6-4761-8a25-503ce7dbaeea" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/407f70bb-9205-4809-a0ac-7aa98aee1a15" alt="image" width="500"/>

<h4>Trigger2: Update Flight Availability</h4>
<p><strong>Purpose:</strong> This trigger updates flight availability when a ticket is booked or canceled, keeping the flight's seat availability accurate in real-time.</p>
<p><strong>Insights:</strong> Keeping real-time data on seat availability enhances the booking experience by ensuring that customers can view up-to-date information on available flights. This can help avoid overbooking issues, improve customer satisfaction, and optimize flight inventory management.</p>

<img src="https://github.com/user-attachments/assets/fe8c318b-c33d-4f74-b60f-8b070e5dd453" alt="image" width="500"/>

<h3>4. Reports</h3>
<h4>Report1: Booking Cancellation and Refund Analysis</h4>
<p><strong>Purpose:</strong> This report provides an analysis of booking cancellations, refund rates, and trends over time. It helps identify the factors contributing to booking cancellations and the corresponding financial impact.</p>
<p><strong>Insights:</strong> This data can inform customer service improvements, such as offering better refund policies or addressing common cancellation reasons. Identifying trends in cancellations can help the business take proactive measures to reduce churn, such as improving flight reliability or providing more flexible booking options.</p>

<img src="https://github.com/user-attachments/assets/0f4b2a20-cd53-478d-b883-baea655bc932" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/e2f8ade3-0801-4e87-9aa8-38c1b81356fa" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/3c26cf79-1d67-4946-a25b-94d1e4df6cc4" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/f6fb7c35-0026-4902-9be1-0d3b016715d5" alt="image" width="500"/>

<h4>Report2: Aircraft Maintenance and Operational Cost Analysis</h4>
<p><strong>Purpose:</strong> This report analyzes the frequency and cost of aircraft maintenance, helping identify cost drivers and trends related to aircraft upkeep. It provides detailed insight into the operational costs of different aircraft models.</p>
<p><strong>Insights:</strong> Understanding maintenance patterns can help the business plan for future costs and potentially phase out high-maintenance models. By comparing maintenance frequency and costs across models, the company can make data-driven decisions about fleet management and optimize resource allocation.</p>

<img src="https://github.com/user-attachments/assets/7642b4f2-a286-472c-ae37-7890bc78ec91" alt="image" width="500"/>

<img src="https://github.com/user-attachments/assets/15ffc106-e062-43b6-ba08-5f66f8504b98" alt="image" width="500"/>

<h2>License</h2>
<p>This project is part of a university assignment and is not intended for commercial use.</p>
