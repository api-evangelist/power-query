---
title: "Translytical Task Flows (Generally Available)"
url: "https://community.fabric.microsoft.com/t5/Power-BI-Updates-Blog/Translytical-Task-Flows-Generally-Available/ba-p/5173907"
date: "Mon, 20 Apr 2026 16:00:00 GMT"
author: "DataZoe"
feed_url: "https://community.fabric.microsoft.com/oxcrx34285/rss/board?board.id=fbc_pbiupdatesblog"
---
<p>Translytical task flows take interactive Power BI reports to the next level where users can update records, add annotations, and trigger actions in external systems—all without leaving the report.</p>

<p>With translytical task flows, report consumers become active participants. Instead of viewing data and then switching to another application to take action, users can complete their entire workflow within the Power BI interface.</p>

<p>Translytical task flows connect Power BI reports to Fabric User Data Functions. When a user interacts with a report—selecting a record, entering a value, and clicking a button—the report passes the context of what they have selected to a function to execute the requested action.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Translytical_Task_Flows_Generally_Available" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336405iF9B1EB78010C0E4A/image-size/large?v=v2&amp;px=999" title="word-image-32425-1.png" /><span class="lia-inline-image-caption">Translytical_Task_Flows_Generally_Available</span></span></p>

<p><em>Figure 1: Example of a translytical report experience, where users can review project status and add notes directly in Power BI.</em>
</p><h2>Capabilities</h2>
<ul>
 	<li><strong>Adding data</strong>: Insert new records into your database directly from the report. For example, a customer service representative can add a new customer record while reviewing existing accounts and see it immediately in the report.</li>
 	<li><strong>Updating data</strong>: Update existing records without leaving the report. A logistics coordinator can change an order status or add notes to a shipment record as they work through their queue.</li>
 	<li><strong>Deleting data</strong>: Remove records that are no longer needed. An inventory manager can delete discontinued products from active lists while reviewing stock levels.</li>
 	<li><strong>Calling external APIs</strong>: Trigger actions in other systems through API requests. A sales representative can request a discount approval that posts directly to Microsoft Teams, where a manager can review and respond. Not only can they trigger these but capture and pass on a message too.<span class="lia-inline-image-display-wrapper"><img alt="An_adaptive_card_requestion_an_update_in_a_Teams_channel" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336408i084040D6F91AAC45/image-size/large?v=v2&amp;px=999" title="an-adaptive-card-requestion-an-update-in-a-teams-c.png" /><span class="lia-inline-image-caption">An_adaptive_card_requestion_an_update_in_a_Teams_channel</span></span><br />
<em>Figure 2: An adaptive card in a Teams channel requesting an update to a status with link to the Power BI report to update it using translytical task flows.</em></li>
</ul>
These capabilities can work together too. For instance, a sales opportunity report can include a discount request form. When a user selects opportunities from a filtered table, enters a discount percentage, and adds a justification, clicking the submit button sends all that context to a function. The function then processes the discount and posts the request to Teams with the relevant details, creating a complete audit trail from insight to action. The updated data is also immediately visible in the same report!<p></p>

<p>Other scenarios for translytical task flows include:</p>

<p><strong>Data annotation and quality management</strong>: Field teams often discover data issues while working in reports. With translytical task flows, they can correct a misspelled customer name, update an outdated address, or add contextual notes to records immediately. This approach improves data quality at the point of discovery rather than routing corrections through separate processes.</p>

<p><strong>Workflow automation</strong>: Business processes frequently require approvals, notifications, or ticket creation. Translytical task flows can trigger these actions based on report context. A procurement analyst reviewing vendor performance can flag a supplier for review, automatically creating a task in the appropriate system with all the supporting data attached.</p>

<p><strong>AI-assisted decision making</strong>: Use AI functions in your extract load and transform process with Fabric Notebooks to categorize or summarize your data. These can then be reviewed and updated in your Power BI report.</p>

<p>For data write-back scenarios, User Data Functions currently have native connection management for the following Fabric data sources:
<ul>
 	<li>Fabric SQL databases</li>
 	<li>Fabric warehouses</li>
 	<li>Fabric lakehouses (for files)</li>
</ul>
Once you have your scenario in mind, building your first translytical task flow involves these main tasks:
<ul>
 	<li>Storing your data in a Fabric data source.</li>
 	<li>Developing a User Data Function to handle the action.</li>
 	<li>Creating a Power BI semantic model to use this data.</li>
 	<li>Building a Power BI report with interactive elements to capture the user's input and call the function.</li>
</ul>
<a href="https://learn.microsoft.com/fabric/fundamentals/copilot-fabric-overview" rel="noopener" target="_blank">Copilot in Microsoft Fabric</a> is built into many Fabric workflows and <a href="https://github.com/features/copilot" rel="noopener" target="_blank">GitHub Copilot</a> in <a href="https://code.visualstudio.com/" rel="noopener" target="_blank">Visual Studio Code</a> with <a href="https://github.com/mcp" rel="noopener" target="_blank">MCPs</a> to <a href="https://learn.microsoft.com/training/support/mcp" rel="noopener" target="_blank">access learn documentation</a> and <a href="https://github.com/microsoft/powerbi-modeling-mcp" rel="noopener" target="_blank">connect to Power BI semantic models</a> can help you accelerate this process too.</p>

<p>Translytical task flows represent a shift in how organizations can use Power BI. Reports are no longer only for analysis—they enable you to take action. By connecting insight directly to execution, teams can reduce the time between identifying an opportunity and acting on it.
</p><h2>Next steps</h2>
<ul>
 	<li><strong>Learn more</strong>: Refer to the <a href="https://learn.microsoft.com/power-bi/create-reports/translytical-task-flow-overview" rel="noopener" target="_blank">Translytical task flows documentation</a> for detailed guidance on building your first task flow.</li>
 	<li><strong>Explore User Data Functions</strong>: Visit the <a href="https://learn.microsoft.com/fabric/data-engineering/user-data-functions/user-data-functions-overview" rel="noopener" target="_blank">User Data Functions in Fabric documentation</a> to understand all the capabilities it supports.</li>
 	<li><strong>Submit ideas</strong>: Share your feedback and feature requests through the <a href="https://community.fabric.microsoft.com/t5/Fabric-Ideas/idb-p/fbc_ideas" rel="noopener" target="_blank">Power BI ideas forum</a>.</li>
</ul><p></p>
