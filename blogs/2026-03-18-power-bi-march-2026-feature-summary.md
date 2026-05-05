---
title: "Power BI March 2026 Feature Summary"
url: "https://community.fabric.microsoft.com/t5/Power-BI-Updates-Blog/Power-BI-March-2026-Feature-Summary/ba-p/5173928"
date: "Wed, 18 Mar 2026 13:07:49 GMT"
author: "kamurray"
feed_url: "https://community.fabric.microsoft.com/oxcrx34285/rss/board?board.id=fbc_pbiupdatesblog"
---
<p>Welcome to the <strong>Power BI March 2026 Feature Summary</strong>—and welcome to <strong>FabCon!</strong></p>

<p>As FabCon gets underway, this month’s update reflects the momentum we’re seeing across Power BI and the conversations happening with customers right now. March brings a thoughtful set of improvements across Copilot, reporting, modeling, and data connectivity—focused on making everyday authoring smoother, visuals more expressive, and analytics experiences more flexible and open.</p>

<p>Whether you’re refining reports, enabling more interactive analytics, or modernizing semantic models, there’s plenty to explore in this release—and we’re excited to keep the conversation going throughout FabCon.</p>

<p><em>If you haven’t already, check out Arun Ulag’s hero blog “</em><a href="https://aka.ms/FabCon-SQLCon-2026-news" rel="noopener" target="_blank"><em>FabCon and SQLCon 2026: Unifying databases and Fabric on a single, complete platform</em></a><em>” for a complete look at all of our FabCon and SQLCon announcements across both Fabric and our database offerings.&nbsp;</em>
</p><p style="font-size: 22px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">Contents</p>

<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">March Monthly Update Video</p>
https://youtu.be/INwbDNhRMG0
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">March Power BI Desktop</p>
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><a href="https://www.microsoft.com/power-platform/products/power-bi/desktop?WT.mc_id=Blog_Desktop_Update" title=""><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336368i631F5ECD2D5FAC5B/image-size/large?v=v2&amp;px=999" title="PBI-download-blog.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span></a></p>
<ul>
 	<li>
<p style="font-size: 16px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Version number: v: 2.152.882.0&nbsp;</strong></p>
</li>
 	<li>
<p style="font-size: 16px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Date published: 03/15/2026</strong></p>
</li>
</ul>
<h2>Events and Announcements</h2>
<h3>Power BI DataViz World Championships live at FabCon and SQLCon Atlanta!</h3>
Four finalists <a id="post-32302-_Int_RvgDE3dN"></a>took the stage at FabCon to compete for the title of world champion, <a href="https://aka.ms/pbidvwc26/finalists" rel="noopener" target="_blank">view the preliminary round entries that sent them to the finals.</a><p></p>

<p><strong>We'd like to offer a huge congratulations to the winner, Gustavo Bavia the Power BI Dataviz World Champion!</strong>
</p><h3>Couldn't make it to Atlanta or just want more FabCon+SQLCon? Join us in Barcelona this September!</h3>
FabCon Europe is happening again in 2026. Mark your calendars for September 28 – October 1, 2026. <a href="https://www.sharepointeurope.com/european-microsoft-fabric-community-conference-tickets/" rel="noopener" target="_blank">Register now</a> to access Super Early Bird pricing!
<h2>General</h2>
<h3>Deprecation of Old File Picker Experience in Power BI Desktop</h3>
Beginning April 2026, as part of the SU04 release, users will no longer be able to access the old file picker experience in Power BI Desktop.<p></p>

<p>In January, <a href="https://powerbi.microsoft.com/blog/save-to-onedrive-and-sharepoint-updated-file-picker-public-preview/" rel="noopener" target="_blank">we announced an updated file picker experience</a> that provides users with a more intuitive, straightforward way of navigating between files and folders. As of next month, we are moving the updated experience out of preview and making it the default experience in Power BI Desktop. With this change, users will no longer be able to toggle between the old and updated experience.</p>

<p><em>Note</em>: No action is required from users as part of this deprecation; this is simply an informational announcement.
</p><h3>QuickBooks Online Connector Retirement</h3>
The QuickBooks Online connector is being retired and will no longer be supported as of March 2026.<p></p>

<p>As part of our ongoing platform evolution, this change streamlines our connector portfolio and ensures our continued commitment to only the highest level of secure data connectivity.</p>

<p>After retirement, customers will no longer be able to create new connections, and existing connections may no longer function.
</p><h2>Copilot and AI</h2>
<h3>Copilot pane user experience update</h3>
To match the standalone experience, we’ve updated the Copilot pane in Reports and Apps to have the same look and feel.
<table>
<tbody>
<tr>
<td>Before</td>
<td>After</td>
</tr>
<tr>
<td><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_the_current_Power_BI_Copilot_pane_displaying_a_user_query_about_to" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336449iDE9475599E9AD200/image-size/large?v=v2&amp;px=999" title="screenshot-of-the-current-power-bi-copilot-pane-di-2.png" /><span class="lia-inline-image-caption">Screenshot_of_the_current_Power_BI_Copilot_pane_displaying_a_user_query_about_to</span></span><em>Figure: Power BI Copilot pane showing current user experience</em></td>
<td><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_the_updated_Power_BI_Copilot_pane_displaying_a_query_about_total_b" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336450iA19094549F4D53D2/image-size/large?v=v2&amp;px=999" title="screenshot-of-the-updated-power-bi-copilot-pane-di-2.png" /><span class="lia-inline-image-caption">Screenshot_of_the_updated_Power_BI_Copilot_pane_displaying_a_query_about_total_b</span></span><em>Figure: Power BI Copilot pane showing updated user experience to match standalone</em></td>
</tr>
</tbody>
</table>
Functionally, the pane operates the same as before with the same capabilities. You may notice a few small changes in behavior:<br />
The starting button suggestions will disappear after you start your conversation. If you need to find them again, you can access them from the <strong>prompt guide</strong> (book icon):<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_a_text_input_box_labeled_Ask_a_question_about_this_report_with_a_s" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336453iC14CE629642FE447/image-size/large?v=v2&amp;px=999" title="screenshot-of-a-text-input-box-labeled-ask-a-ques-2.png" /><span class="lia-inline-image-caption">Screenshot_of_a_text_input_box_labeled_Ask_a_question_about_this_report_with_a_s</span></span></p>

<p>Figure: Power BI Copilot pane with prompt guide icon</p>

<p>or <strong>clear your chat</strong> to start over:</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_a_chat_interface_showing_a_user_request_for_an_executive_summary_o" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336452i7A48AFA7263A8D10/image-size/large?v=v2&amp;px=999" title="screenshot-of-a-chat-interface-showing-a-user-requ-2.png" /><span class="lia-inline-image-caption">Screenshot_of_a_chat_interface_showing_a_user_request_for_an_executive_summary_o</span></span></p>

<p><em>Figure: Power BI Copilot pane with clear chat history sweep icon</em></p>

<p>Input box now appears enabled while processing an ongoing request and you can type your next prompt. However, you will still need to wait until the current prompt finishes before submitting your next.</p>

<p>The copy action has been moved to the bottom of the response output next to the feedback buttons.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_a_text_excerpt_highlighting_Copilot_summary_response_with_the_copy" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336457iFD744413724044FE/image-size/large?v=v2&amp;px=999" title="screenshot-of-a-text-excerpt-highlighting-copilot-2.png" /><span class="lia-inline-image-caption">Screenshot_of_a_text_excerpt_highlighting_Copilot_summary_response_with_the_copy</span></span></p>

<p><em>Figure: Power BI Copilot pane with text summary response and copy icon</em></p>

<p>Learn more about the <a href="https://learn.microsoft.com/power-bi/create-reports/copilot-reports-overview" rel="noopener" target="_blank">Copilot report pane</a> in our documentation.
</p><h3>Copilot feedback update</h3>
Across all Power BI Copilot experiences, you’ll see an updated feedback dialog that now allows you add diagnostics with your submission to the product team. Sharing diagnostics with your thumbs up or down feedback provides more conversational context to your rating and is especially helpful during support case investigations. You can also preview the diagnostics file before submission to ensure you are not sending any sensitive information.
<table>
<tbody>
<tr>
<td>Before</td>
<td>After</td>
</tr>
<tr>
<td><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_a_feedback_submission_form_for_Microsoft_requesting_users_to_descr" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336458iC44885E5E2034A39/image-size/large?v=v2&amp;px=999" title="screenshot-of-a-feedback-submission-form-for-micro-4.png" /><span class="lia-inline-image-caption">Screenshot_of_a_feedback_submission_form_for_Microsoft_requesting_users_to_descr</span></span>Figure: Previous Power BI Copilot feedback dialog experience</td>
<td><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_a_feedback_submission_form_for_Microsoft_prompting_users_to_descri" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336459i514BBAEE2E644C33/image-size/large?v=v2&amp;px=999" title="screenshot-of-a-feedback-submission-form-for-micro-5.png" /><span class="lia-inline-image-caption">Screenshot_of_a_feedback_submission_form_for_Microsoft_prompting_users_to_descri</span></span>Figure: Updated Power BI Copilot feedback dialog experience with diagnostics attached</td>
</tr>
</tbody>
</table>
Learn more about our <a href="https://learn.microsoft.com/power-bi/create-reports/copilot-introduction" rel="noopener" target="_blank">Power BI Copilot experiences</a> in our documentation.
<h2>Reporting</h2>
<h3>AI Narrative auto refresh</h3>
Instead of clicking <strong>Refresh</strong> every time you select a slicer in a report with the AI Narrative visual, use the <strong>Auto refresh</strong> toggle in the visualizations pane. This enables the summary to update automatically whenever a slicer selection changes, creating a smoother and more efficient reporting experience.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="AI_narrative_message_displayed_when_a_slicer_is_selected_in_the_report" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336460i103C876FFA60EB1E/image-size/large?v=v2&amp;px=999" title="ai-narrative-message-displayed-when-a-slicer-is-se-2.png" /><span class="lia-inline-image-caption">AI_narrative_message_displayed_when_a_slicer_is_selected_in_the_report</span></span></p>

<p><em>Figure: AI narrative message displayed when a slicer is selected in the report</em></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Toggle_the_option_to_enable_automatic_refresh_of_the_AI_Narrative_in_the_format" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336465i9FB8683C08244B71/image-size/large?v=v2&amp;px=999" title="toggle-the-option-to-enable-automatic-refresh-of-t-2.png" /><span class="lia-inline-image-caption">Toggle_the_option_to_enable_automatic_refresh_of_the_AI_Narrative_in_the_format</span></span></p>

<p><em>Figure: Toggle the option to enable automatic refresh of the AI Narrative in the format pane</em>
</p><h3>Translytical task flows (Generally Available)</h3>
Translytical task flows enable end users to perform actions directly within Power BI reports, such as updating records, adding data, or initiating workflows in other systems, all without navigating away from the report.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_the_Translytical_task_flow_authoring_experience_in_Power_BI_showin" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336467iBF64787B290BFAA8/image-size/large?v=v2&amp;px=999" title="screenshot-of-the-translytical-task-flow-authoring-2.png" /><span class="lia-inline-image-caption">Screenshot_of_the_Translytical_task_flow_authoring_experience_in_Power_BI_showin</span></span></p>

<p><em>Figure: Translytical task flow in Power BI</em></p>

<p>Translytical task flows use Fabric user data functions to connect reports to underlying data sources. Common scenarios include editing data records in place, adding annotations, deleting outdated entries, and calling external APIs like Azure OpenAI. For example, a sales team can update discount values directly in a report, or request approvals that post automatically to Teams.</p>

<p>Data writeback supports Fabric SQL databases, Fabric warehouses, and Fabric lakehouses (for files). For heavy read/write reporting scenarios, SQL database is the recommended data source. To get started, refer to the&nbsp;<a href="https://learn.microsoft.com/power-bi/create-reports/translytical-task-flow-overview" rel="noopener" target="_blank">Translytical task flows overview</a>&nbsp;documentation or follow the&nbsp;<a href="https://learn.microsoft.com/power-bi/create-reports/translytical-task-flow-tutorial" rel="noopener" target="_blank">step-by-step tutorial</a>&nbsp;to build your first task flow.
</p><h3>Modern visual defaults and customizing theme improvements (Preview)</h3>
Power BI Desktop visuals now start with a modern look. This preview introduces an updated base theme aligned with Fluent 2, featuring subtitles, uniform padding, style presets, and a grey canvas background at 1080x1920px by default. Charts display with smooth lines, slicers default to dropdown mode, and buttons have a refreshed appearance without manual formatting.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_report_page_using_the_new_modern_visual_defaults_Fluent_2_styling_showi" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336466i68A2E9E7B5C09F7F/image-size/large?v=v2&amp;px=999" title="power-bi-report-page-using-the-new-modern-visual-d-2.png" /><span class="lia-inline-image-caption">Power_BI_report_page_using_the_new_modern_visual_defaults_Fluent_2_styling_showi</span></span></p>

<p><em>Figure: Example report page with modern visual defaults applied—uniform padding, updated typography, and refreshed visual styling on a gray 1080×1920 canvas</em></p>

<p>Enable the preview in&nbsp;<strong>Options and settings</strong>&nbsp;&gt;&nbsp;<strong>Options</strong>&nbsp;&gt;&nbsp;<strong>Preview features</strong>&nbsp;by turning on&nbsp;<strong>modern visual defaults and customizing theme improvements</strong>. This preview is available in Power BI Desktop, and published reports retain the new base theme for editing in the browser. The base theme on existing reports remains unchanged until you go to&nbsp;<strong>View</strong>&nbsp;&gt;&nbsp;<strong>Themes</strong>&nbsp;&gt;&nbsp;<strong>Customize current theme</strong>&nbsp;and select&nbsp;<strong>Update theme</strong>. The theme schema also supports setting page size and defining reusable named colors.</p>

<p>Please share your feedback through the&nbsp;<a href="https://forms.office.com/pages/responsepage.aspx?id=v4j5cvGGr0GRqy180BHbR7qIRgX7n7VNtum7LaUVzhxUOEpQSVpHMFo3MVg2VVRWUlo4QUpNNVg0UC4u&amp;route=shorturl" rel="noopener" target="_blank">Modern Visuals Preview Feedback form</a>, and learn more in the&nbsp;<a href="https://learn.microsoft.com/power-bi/create-reports/desktop-report-themes" rel="noopener" target="_blank">Use report themes in Power BI Desktop</a>&nbsp;documentation.
</p><h3>Custom totals (Preview)</h3>
Table and matrix visuals display a DAX measure by category, with a total. The total (which you can toggle on or off) evaluates the measure in the entire filter context of the report page, rather than simply summing the category values, as in the waterfall visual. This ensures the correct result is shown for many non-additive calculations, such as averages, counts, margins, and maximum (or latest) values, among others. This is an intended design; the behavior of totals in these visuals is like tables and pivot tables in Excel. Understanding this behavior helps explain why a total may differ from a simple sum of the rows in a table or matrix.<p></p>

<p>To illustrate, the following example demonstrates this behavior. The calculations for DAX measures average sales and number of customers are non-additive, so the totals in the table do not show the sum of all categories, as they do for an additive measure such as total sales:<br />
<span class="lia-inline-image-display-wrapper"><img alt="Table_titled_Sales_by_Category_listing_Accessories_Bikes_Clothing_and_Components" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336468i8D82F73D33B1D5A2/image-size/large?v=v2&amp;px=999" title="table-titled-sales-by-category-listing-accessor-2.png" /><span class="lia-inline-image-caption">Table_titled_Sales_by_Category_listing_Accessories_Bikes_Clothing_and_Components</span></span></p>

<p>Figure: Sales by Category summary showing Bikes as the primary revenue driver ($46.98M total sales), contributing most of the $62.17M total across 18,485 customers</p>

<p>Some report authors wish for more control over totals in tables and matrices. Custom totals are a new feature to address scenarios where a summed row total is the desired behavior for these visuals. Keeping the measure definition unchanged, a custom total instead adjusts the visual’s aggregation logic to override the measure’s default total behavior. Using this feature does not alter the underlying DAX measure; it changes how the total row is calculated for the configured visual only by using a visual calculation.</p>

<p>Setting a <strong>Custom total</strong> is easy. First, make sure the visual calculations preview is turned on. Then, to set a custom total, right-click a column or use the <strong>Build</strong> pane to choose or define the desired calculation, without writing DAX. Options such as <strong>Sum</strong>, <strong>Min</strong>, <strong>Max</strong> <strong>Count</strong> <strong>(Distinct)</strong> and <strong>Count</strong> allow you to tailor the total to the context of the visual. “Reset to default” will return the total to the default DAX-driven total behavior whenever needed.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_a_reporting_app_context_menu_with_options_such_as_Copy_Share_Summa" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336471iB0A9A69E51F30467/image-size/large?v=v2&amp;px=999" title="screenshot-of-a-reporting-app-context-menu-with-op-2.png" /><span class="lia-inline-image-caption">Screenshot_of_a_reporting_app_context_menu_with_options_such_as_Copy_Share_Summa</span></span></p>

<p><em>Figure: Right-click menu showing how to customize a visual’s total calculation (preview) by selecting an aggregation method such as Sum, Min, Max, Count (Distinct), or Count</em></p>

<p>Once you set a custom total, an Excel-like indicator appears. For instance, after setting <strong>Number of Customers</strong> to <strong>Sum</strong>, the column title updates:</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_the_Power_BI_Copilot_report_input_area_showing_a_text_box_labeled" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336473i2BFD6E4F708727A1/image-size/large?v=v2&amp;px=999" title="screenshot-of-the-power-bi-copilot-report-input-ar-2.png" /><span class="lia-inline-image-caption">Screenshot_of_the_Power_BI_Copilot_report_input_area_showing_a_text_box_labeled</span></span></p>

<p><em>Figure: Power BI Copilot pane showing the prompt guide (book) icon next to the “Ask a question about this report” input box</em></p>

<p>Custom totals use visual calculations and share their limitations. For example, formatting is not automatically applied to custom totals; <a href="https://learn.microsoft.com/power-bi/transform-model/desktop-visual-calculations-overview#formatting-visual-calculations" rel="noopener" target="_blank">use Data Format settings to format them, just as with visual calculations.</a></p>

<p>Although <strong>Custom totals</strong> add flexibility and convenience, they don’t replace Power BI’s default total behavior, which remains the most accurate representation of the measure as defined in DAX.</p>

<p>Learn more about <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-tables?tabs=powerbi-desktop" rel="noopener" target="_blank">Custom totals and how they work in our table and matrix</a>.
</p><h3>Series label leader lines for line charts</h3>
Leader lines for series labels are now available on line charts and related visuals, making it easier to understand which line belongs to which label—especially in dense or overlapping scenarios.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Line_chart_of_profit_over_time_year_quarter_for_multiple_states_with_series_labe" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336475iD97BC448EBA94BD9/image-size/large?v=v2&amp;px=999" title="line-chart-of-profit-over-time-year-quarter-for-2.png" /><span class="lia-inline-image-caption">Line_chart_of_profit_over_time_year_quarter_for_multiple_states_with_series_labe</span></span></p>

<p><em>Figure: Series label leader lines on a line chart, connecting each label to its corresponding series for easier identification in dense visuals</em></p>

<p>When enabled, leader lines visually connect each series label to its corresponding data point, improving readability without changing which labels appear. The feature includes smart layout logic to avoid label collisions, along with formatting options for line style, width, and transparency so you can match your visual design. Leader lines turn on automatically when series labels are enabled for new reports, while existing reports remain unchanged. Series labels are also selectable, which highlight a line and turn on the markers. To select multiple items, use multi-select (Ctrl on Windows or Command on macOS).</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Line_chart_of_profit_over_time_for_multiple_states_with_series_labels_and_leader" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336476i8B765EA474084130/image-size/large?v=v2&amp;px=999" title="line-chart-of-profit-over-time-for-multiple-states-2.png" /><span class="lia-inline-image-caption">Line_chart_of_profit_over_time_for_multiple_states_with_series_labels_and_leader</span></span></p>

<p><em>Figure: Selecting series labels highlights the corresponding lines and shows markers, making it easier to compare multiple series</em></p>

<p>For more information about visualizations in Power BI, refer to the&nbsp;<a href="https://learn.microsoft.com/power-bi/visuals/power-bi-line-chart" rel="noopener" target="_blank">Line charts in Power BI</a>&nbsp;documentation.
</p><h3>Report theme updates</h3>
This month introduces two new enhancements to custom report themes, providing you with greater control over your report's formatting.<p></p>

<p>You can now <strong>define a default page size directly in your theme file</strong>. When you add a&nbsp;page&nbsp;section to your theme JSON, any new pages added to your report automatically use those dimensions. This feature helps teams maintain consistent report layouts without manually configuring each page. For example, you can set a custom 1920x1080 resolution for presentation-ready reports:</p>

<p>{</p>

<p>"name": "Page Size Theme Example",</p>

<p>"$schema": "reportThemeSchema-2.149.json",</p>

<p>&nbsp;</p>

<p>"visualStyles": {</p>

<p>"page": {</p>

<p>"*": {</p>

<p>"pageSize": [</p>

<p>{</p>

<p>"pageSizeTypes": "Custom",</p>

<p>"pageSizeWidth": 1920,</p>

<p>"pageSizeHeight": 1080</p>

<p>}</p>

<p>]</p>

<p>}</p>

<p>}</p>

<p>}</p>

<p>}</p>

<p>You can also now reference <strong>structural theme colors </strong>such as <em>background</em> and <em>foreground</em>. This example shows how to set different colors in a table visual preset.</p>

<p>{</p>

<p>"name": "Structural Colors Theme Example",</p>

<p>"$schema": "reportThemeSchema-2.149.json",</p>

<p>&nbsp;</p>

<p>"foreground": "#242424",</p>

<p>"background": "#FFFFFF",</p>

<p>"secondaryBackground": "#F5F5F5",</p>

<p>&nbsp;</p>

<p>"visualStyles": {</p>

<p>"tableEx": {</p>

<p>"*": {</p>

<p>"columnHeaders": [</p>

<p>{</p>

<p>"fontColor": {</p>

<p>"solid": {</p>

<p>"color": "foreground"</p>

<p>}</p>

<p>},</p>

<p>"backColor": {</p>

<p>"solid": {</p>

<p>"color": "secondaryBackground"</p>

<p>}</p>

<p>}</p>

<p>}</p>

<p>],</p>

<p>"values": [</p>

<p>{</p>

<p>"fontColor": {</p>

<p>"solid": {</p>

<p>"color": "foreground"</p>

<p>}</p>

<p>},</p>

<p>"backColor": {</p>

<p>"solid": {</p>

<p>"color": "background"</p>

<p>}</p>

<p>}</p>

<p>}</p>

<p>]</p>

<p>}</p>

<p>}</p>

<p>}</p>

<p>}</p>

<p>To learn more about creating custom themes, refer to the&nbsp;<a href="https://learn.microsoft.com/power-bi/create-reports/report-themes-create-custom" rel="noopener" target="_blank">Create custom report themes in Power BI Desktop</a>&nbsp;documentation.
</p><h3>Input slicer now supports conditional formatting</h3>
The input slicer now supports conditional formatting (Fx) across multiple visual elements in the formatting pane. You can apply dynamic formatting rules to text colors, icon colors, borders, and accent bars based on measures or field values in your data.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_Power_BI_Desktop_with_the_input_slicer_selected_the_formatting_pan" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336480i6F9A3D82F93F52E5/image-size/large?v=v2&amp;px=999" title="screenshot-of-power-bi-desktop-with-the-input-slic-2.png" /><span class="lia-inline-image-caption">Screenshot_of_Power_BI_Desktop_with_the_input_slicer_selected_the_formatting_pan</span></span></p>

<p><em>Figure: Input slicer conditional formatting (Fx) options in the formatting pane</em></p>

<p>Elements that support conditional formatting include:
<ul>
 	<li>Filters: Text color, Dismiss button color</li>
 	<li>Filter operator: Text and icon color</li>
 	<li>Apply button: Icon color</li>
 	<li>Input box: Placeholder text color and accent bar color</li>
 	<li>Background and border colors for each element.</li>
</ul>
This update gives you greater control over the input slicer's appearance, allowing you to create visual cues that respond to your data. For example, you can change the accent bar color based on a status field or highlight the apply button when certain conditions are met.</p>

<p>Learn more about the input slicer and its formatting options in the <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-input-slicer" rel="noopener" target="_blank">Create and use an input slicer</a>&nbsp;documentation.
</p><h2>Modeling</h2>
<h3>Direct Lake in OneLake (Generally Available)</h3>
Power BI is standardizing open-data formats by adopting Delta Lake and Parquet to help you avoid vendor lock-in and reduce data duplication. This minimizes data silos and fragmentation, offering a single source of truth across the enterprise. <strong>Direct Lake storage mode</strong> accelerates data-driven decisions by unlocking incredible performance directly against OneLake, without the need to manage costly, time-consuming data refreshes for large volumes of data in OneLake.<p></p>

<p>In May 2023, we <a href="https://powerbi.microsoft.com/blog/power-bi-may-2023-feature-summary/" rel="noopener" target="_blank">announced</a> the revolutionary Direct Lake storage mode for Power BI semantic models and used Direct Lake on SQL, which reached general availability with Microsoft Fabric in November 2023. In March 2025, we introduced <strong>Direct Lake on OneLake</strong> semantic model creation from Power BI Desktop. For more information and a more in-depth look, check out the <a href="https://powerbi.microsoft.com/blog/deep-dive-into-direct-lake-on-onelake-and-creating-direct-lake-semantic-models-in-power-bi-desktop/" rel="noopener" target="_blank">Deep dive into Direct Lake on OneLake</a> blog post.
<ul>
 	<li>Use <strong>Direct Lake on OneLake</strong> for compatibility with <a href="https://learn.microsoft.com/fabric/onelake/security/get-started-security" rel="noopener" target="_blank">OneLake security</a>, more modeling features, and faster query performance.</li>
 	<li>Use <strong>Direct Lake on SQL</strong> when you depend on security rules defined in the SQL analytics endpoint with <a href="https://learn.microsoft.com/en-us/fabric/onelake/security/sql-analytics-endpoint-onelake-security" rel="noopener" target="_blank">delegated identity mode</a>, or you need fallback to DirectQuery.</li>
</ul>
<span class="lia-inline-image-display-wrapper"><img alt="The_image_displays_a_dashboard_with_a_new_semantic_model_added_to_Direct_Lake_on" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336484i4DAAAE3DD82A4B80/image-size/large?v=v2&amp;px=999" title="the-image-displays-a-dashboard-with-a-new-semantic-2.jpeg" /><span class="lia-inline-image-caption">The_image_displays_a_dashboard_with_a_new_semantic_model_added_to_Direct_Lake_on</span></span></p>

<p><em>Figure: The default selection is determined by whether the SQL endpoint is running in User ID mode or delegated mode</em></p>

<p>Check out the <a href="https://learn.microsoft.com/fabric/fundamentals/direct-lake-overview" rel="noopener" target="_blank">Direct Lake overview</a> for a full comparison.</p>

<p>When you create a new Direct Lake semantic model from the SQL analytics endpoint page, you can choose <strong>Direct Lake on OneLake</strong> or <strong>Direct Lake on SQL</strong>.
</p><h3>TMDL View in web modeling (Preview)</h3>
In the coming weeks, TMDL View on the Web will become available in preview, introducing a new code‑first semantic modeling experience directly in the browser.<p></p>

<p>With this preview, developers can script, modify, and apply changes to model objects directly in a code editor using <a href="https://learn.microsoft.com/analysis-services/tmdl/tmdl-overview" rel="noopener" target="_blank">Tabular Model Definition Language (TMDL),</a> without switching to Desktop or downloading model files.</p>

<p>This experience provides immediate, code‑level visibility into all semantic model metadata (tables, measures, relationships, and more), enabling bulk edits, automation of repetitive tasks, and the reuse of definitions to improve consistency and productivity.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="TMDL_View_on_the_web_showing_a_side-by-side_TMDL_code_diff_that_previews_the_sem" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336483i85180CF788B0947E/image-size/large?v=v2&amp;px=999" title="tmdl-view-on-the-web-showing-a-side-by-side-tmdl-c-2.png" /><span class="lia-inline-image-caption">TMDL_View_on_the_web_showing_a_side-by-side_TMDL_code_diff_that_previews_the_sem</span></span></p>

<p><em>Figure: Previewing semantic model changes from a TMDL script in TMDL View on the web</em></p>

<p>For more details about TMDL view and the full list of capabilities in this release, refer to the documentation: <a href="https://learn.microsoft.com/power-bi/transform-model/desktop-tmdl-view" rel="noopener" target="_blank">Use Tabular Model Definition Language (TMDL) view in Power BI Desktop - Power BI | Microsoft Learn</a>
</p><h3>DAX user-defined functions (Preview)</h3>
This month, our ongoing preview of <a href="https://aka.ms/powerbi-dax-UDFs-blog" rel="noopener" target="_blank">DAX user defined functions</a> gets a few exciting updates:
<ul>
 	<li>A new <a href="https://learn.microsoft.com/dax/info-userdefinedfunctions-function-dax" rel="noopener" target="_blank">INFO.USERDEFINEDFUNCTIONS()</a> function is now available that will return information about the user-defined functions in your model.</li>
 	<li>Power BI normally keeps your DAX code in sync when you rename tables, columns, or measures, and it tracks dependencies automatically. We are bringing that same behavior to user‑defined functions. One limitation: unqualified names are interpreted as measure references, so they won’t be reliably fixed or included in dependency tracking when you intended them to refer to columns. An unqualified name is an object reference without a table prefix.</li>
 	<li><a href="https://learn.microsoft.com/dax/best-practices/dax-user-defined-functions" rel="noopener" target="_blank">New types to give you more expressive power and flexibility</a>. In addition to the previously available AnyVal, Scalar, Table and AnyRef, we are adding CalendarRef, ColumnRef, MeasureRef and TableRef. Note that implicit type casting is not supported by these type hints.</li>
 	<li>“Quick queries” for Functions in DAX Query View now supports “Define with references and evaluate.” This enhancement automatically finds all UDF and measure references within the UDF or measure expression being evaluated.</li>
</ul>
<span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_a_semantic_model_pane_with_expandable_sections_Calculation_groups" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336482i0E6C34039C13BFDC/image-size/large?v=v2&amp;px=999" title="screenshot-of-a-semantic-model-pane-with-expandabl-2.png" /><span class="lia-inline-image-caption">Screenshot_of_a_semantic_model_pane_with_expandable_sections_Calculation_groups</span></span><p></p>

<p><em>Figure: Context menus in the semantic model pane showing options to define/evaluate functions and manage model elements (rename, delete, hide/unhide, collapse/expand)</em>
<ul>
 	<li>Formula bar is available for creating or modifying a UDF expression in Model Explorer.</li>
 	<li>Syntax highlighting support for UDFs in TMDL View.</li>
 	<li>Support for <a href="https://jsdoc.app/" rel="noopener" target="_blank">JSDoc block tags</a> to author UDF description and parameters using the triple slash prefix (i.e. `///`) while in DAX Query View.</li>
 	<li>Support for up to 256 UDF parameters (from the previous 12 parameters).</li>
</ul>
As always, if you encounter issues with DAX user-defined functions, let us know and read more about <a href="https://aka.ms/powerbi-dax-UDFs-docs" rel="noopener" target="_blank">DAX user-defined functions in our documentation</a>.
</p><h2>Data connectivity</h2>
<h3>IBM Netezza ODBC Driver (Generally Available)</h3>
With this update, customers gain a more reliable, supported path forward using their own Netezza driver as we transition away from the embedded Simba driver.<p></p>

<p>This update ensures continued connectivity, long-term support, and a more future-ready experience for organizations using the Netezza connector.</p>

<p>Customers do not need to install the new connector; you may reuse your existing connector but will need to install the new IBM Netezza ODBC driver.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Image_depicting_the_IBM_Netezza_connector_selection_pane_from_Fabric" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336487i6D634445471ED08C/image-size/large?v=v2&amp;px=999" title="image-depicting-the-ibm-netezza-connector-selectio-2.png" /><span class="lia-inline-image-caption">Image_depicting_the_IBM_Netezza_connector_selection_pane_from_Fabric</span></span></p>

<p><em>Figure: Netezza Connector Selection UI in Fabric</em></p>

<p>Refer to the <a href="https://learn.microsoft.com/en-us/power-query/connectors/ibm-netezza-database" rel="noopener" target="_blank">IBM Netezza ODBC documentation</a> for more information.
</p><h2>Visualizations</h2>
<h3>Sankey Chart by Powerviz</h3>
The Powerviz <a href="https://appsource.microsoft.com/product/power-bi-visuals/truvizinc1674781244292.sankey-chart-by-powerviz?tab=Overview" rel="noopener" target="_blank">Sankey Chart</a> is a dynamic flow diagram that visualizes the proportional movement of data, resources, or processes across categories or stages. With weighted connections and flexible layouts, it helps users uncover insights within complex systems.<p></p>

<p><strong>New Features</strong>
<ul>
 	<li><strong>Link Labels:</strong> Display values directly on Sankey links to understand flows instantly.</li>
 	<li><strong>Real and Absolute Values:</strong> Toggle between real and absolute node values to better understand true data figures.</li>
 	<li><strong>Level-wise sorting</strong>: Sort each level by ascending or descending order to keep flows organized, and easy to follow.</li>
</ul>
<strong>Key Features</strong>
<ul>
 	<li><strong>Chart Orientation</strong>: Switch seamlessly between vertical and horizontal orientation.</li>
 	<li><strong>Node Customizations</strong>: Control node appearance, spacing, visibility, and interactions for optimal clarity.</li>
 	<li><strong>Multi-Level Support</strong>: Add multiple levels to visualize layered, hierarchical flows.</li>
 	<li><strong>Data Colors</strong>: Access to 30+ color palettes, including color-blind-safe options.</li>
 	<li><strong>Conditional Formatting</strong>: Highlight outlier flows using measure-based or category-based rules.</li>
 	<li><strong>Smart Labels</strong>: Display data and header labels for enhanced readability.</li>
 	<li><strong>Templates</strong>: Use built-in templates or design your own.</li>
</ul>
Other features included are Import/Export Themes, Fill Patterns, Ranking, Show Condition, Grid View and more.</p>

<p><strong>Business Use Cases</strong></p>

<p>Customer Journey Mapping, Expense Breakdown, Supply Chain Flow.
<ul>
 	<li>Try Sankey Chart visual for FREE from&nbsp;<a href="https://appsource.microsoft.com/product/power-bi-visuals/truvizinc1674781244292.sankey-chart-by-powerviz?tab=Overview" rel="noopener" target="_blank">AppSource</a></li>
 	<li><a href="https://app.powerbi.com/view?r=eyJrIjoiZTgyMGYwYzItZGExMi00MGUyLWIzODYtY2VlNmM3MmUwYWE0IiwidCI6ImNhODc1ZjVhLTcwNmMtNDFmNS04YTczLWNlMTQ0ZjMxMDhlMyIsImMiOjF9" rel="noopener" target="_blank">Check out all features of the visual</a></li>
 	<li><a href="https://docs.powerviz.ai/powerviz/sankey-chart/introduction" rel="noopener" target="_blank">Step-by-step instructions</a></li>
 	<li><a href="https://youtu.be/4Dl9Nwt0LMI?si=gnrNXGJXbZc--bdK" rel="noopener" target="_blank">YouTube Video</a></li>
 	<li><a href="https://powerviz.ai/" rel="noopener" target="_blank">Learn more about visuals</a></li>
 	<li><a href="https://lnkd.in/gN_9Sa6U" rel="noopener" target="_blank">Follow Powerviz on LinkedIn</a>&nbsp;<span class="lia-inline-image-display-wrapper"><img alt="The_image_is_a_Sankey_chart_from_PowerBI_illustrating_data_flow_among_various_ca" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336492i5F9BBCA3170D99DD/image-size/large?v=v2&amp;px=999" title="the-image-is-a-sankey-chart-from-powerbi-illustra-2.png" /><span class="lia-inline-image-caption">The_image_is_a_Sankey_chart_from_PowerBI_illustrating_data_flow_among_various_ca</span></span></li>
</ul>
<em>Figure: Sankey Chart by Powerviz showing category-to-category flows with real/absolute value and level-sorting options</em></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="The_image_is_a_Sankey_chart_from_Powerviz_featuring_multiple_levels_customizable" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336491i126F63E5E2FD45C6/image-size/large?v=v2&amp;px=999" title="the-image-is-a-sankey-chart-from-powerviz-featuri-2.png" /><span class="lia-inline-image-caption">The_image_is_a_Sankey_chart_from_Powerviz_featuring_multiple_levels_customizable</span></span></p>

<p><em>Figure: Powerviz Sankey chart with multi-level flows and customizable formatting</em>
</p><h3>Drill Down Pie PRO (Filter) by ZoomCharts</h3>
Pie PRO (Filter) enhances pie and donut charts in Power BI with advanced labeling and flexible category level reference markers, enabling users to understand performance context and interact with data directly on the chart.<p></p>

<p><strong>Key Features</strong></p>

<p><strong>Advanced label customization</strong>: Configure names, values, and percentages. Arrange them across multiple lines. Apply custom fonts, colors, and backgrounds. Hide secondary details to keep attention to the most important information.</p>

<p><strong>Category level performance markers</strong>: Reference markers appear at the slice level, making it easy to see which categories are below, meeting, or exceeding a target without switching visuals or adding complex calculations. Add reference markers per category using any UTF 8 character or icon, including symbols or emojis.</p>

<p><strong>One-click drill down</strong>: Click on one or multiple slices to instantly filter other visuals in the report, combining performance insight with intuitive data exploration.</p>

<p><strong>Images on slices</strong>: Add images on slices to visually differentiate categories.</p>

<p><strong>Key use cases</strong>
<ul>
 	<li>Category performance comparison with custom visual indicators</li>
 	<li>Reports that require expressive yet compact labeling</li>
 	<li>Executive dashboards where fast interpretation is critical</li>
</ul>
<a href="https://zoomcharts.com/goto/?url=https%3A%2F%2Fmarketplace.microsoft.com%2Fen-gb%2Fproduct%2FWA200001678%3Ftab%3DOverview&amp;utm_source=microsoftcom&amp;utm_medium=blog&amp;utm_campaign=feature_summary_february_2026&amp;utm_term=link" rel="noopener" target="_blank">Get Pie PRO (Filter) on AppSource</a>.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="The_image_is_a_pie_chart_illustrating_the_distribution_of_sales_across_different" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336493iE8E9200E42FE886B/image-size/large?v=v2&amp;px=999" title="the-image-is-a-pie-chart-illustrating-the-distribu-2.png" /><span class="lia-inline-image-caption">The_image_is_a_pie_chart_illustrating_the_distribution_of_sales_across_different</span></span></p>

<p><em>Figure: Drill Down Pie PRO showing regional sales distribution with multiple label and indicator styles</em> <span class="lia-inline-image-display-wrapper"><img alt="The_image_illustrates_a_pie_chart_interface_in_Drill_Down_Pie_PRO_showing_custom" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336495iBCC3ABCBD005A58A/image-size/large?v=v2&amp;px=999" title="the-image-illustrates-a-pie-chart-interface-in-dri-2.png" /><span class="lia-inline-image-caption">The_image_illustrates_a_pie_chart_interface_in_Drill_Down_Pie_PRO_showing_custom</span></span></p>

<p><em>Figure: Drill Down Pie PRO interface highlighting label customization and calculation-basis settings</em>
</p><h3>Let location drive your analysis with Icon Map Slicer for Power BI</h3>
<a href="https://icon-map.com/products/slicer/" rel="noopener" target="_blank">Icon Map Slicer</a> is a powerful map visual, purpose-built as a slicer for Power BI with intuitive selections tools, dynamic field-of-view filtering and cross page synchronization.<p></p>

<p>Enhanced 3D capabilities let your visualize terrain and data in three dimensions with support for 3D terrain, extruded polygons, 3D lines and 3D columns.</p>

<p><strong>Data Catalog</strong></p>

<p>New this month, the built-in geospatial catalog contains hundreds of layers ready to instantly enhance your map with additional context, or rich detailed boundaries, formatted and filtered by your Power BI data.</p>

<p>Available map layers include:
<ul>
 	<li>Administrative and Statistical Boundaries</li>
 	<li>Infrastructure layers for Road, Rail and Water</li>
 	<li>Census data including Population Density and Deprivation Indicators</li>
 	<li>Environmental and Risk Factors</li>
</ul>
<span class="lia-inline-image-display-wrapper"><img alt="Screenshots_of_th_eIcon_Map_Catalog_user_interface_showing_4_different_example_d" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336496i95EAD2C9F5E4D33A/image-size/large?v=v2&amp;px=999" title="screenshots-of-th-eicon-map-catalog-user-interface-1.png" /><span class="lia-inline-image-caption">Screenshots_of_th_eIcon_Map_Catalog_user_interface_showing_4_different_example_d</span></span></p>

<p>Reference layers provide extensive formatting options and may be dynamically filtered using Power BI’s “fx” buttons. Many layers can be directly bound to the Power BI dataset enabling conditional formatting options, tooltips and selection.</p>

<p><strong>Filtering Capabilities</strong></p>

<p>Icon Map Slicer provides multiple options for selecting data:
<ul>
 	<li>Automatically filter all visuals on the report based on longitude and latitude fields as you zoom and move the map</li>
 	<li>Select all overlapping elements</li>
 	<li>Lasso select</li>
 	<li>Circle radius select</li>
 	<li>Select all items within a polygon</li>
 	<li>Sync selections between different pages of a Power BI report</li>
</ul>
Extensive Range of Data Visualizations</p>

<p>Power BI data can be presented on the map and conditionally formatted as:
<ul>
 	<li>Circles</li>
 	<li>3D Columns</li>
 	<li>Images, Icons or Emojis</li>
 	<li>Geospatial Cells such as H3 (hexagons), S2 (rectangles), A5 (pentagons)</li>
 	<li>Lines – straight, shortest path, 3D, or flow</li>
 	<li>Shapes / Points / Line Strings from Power BI Data as Well-Known Text (WKT) or GeoJSON features</li>
 	<li>Shapes from GeoJSON / KML / TopJSON or Shape files</li>
 	<li>Vector tiles in with support for PMTiles</li>
</ul>
<span class="lia-inline-image-display-wrapper"><img alt="Icon_Map_Slicer_screenshots_showing_available_background_layers_and_samples_of_d" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336499iC5DA3E541C07A7D9/image-size/large?v=v2&amp;px=999" title="icon-map-slicer-screenshots-showing-available-back-1.png" /><span class="lia-inline-image-caption">Icon_Map_Slicer_screenshots_showing_available_background_layers_and_samples_of_d</span></span>
</p><h3>RADIAL TREE</h3>
The Radial Tree visual allows users to explore hierarchical relationships in an intuitive and engaging way. Designed for clarity and aesthetics, it arranges nodes in concentric circles, displaying parent-child connections through smooth radial links. The layout provides a balanced, symmetrical view that helps uncover patterns, dependencies, and clusters within complex datasets.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_March_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336502i8841BA2F5BDED115/image-size/large?v=v2&amp;px=999" title="word-image-32302-28.png" /><span class="lia-inline-image-caption">Power_BI_March_2026_Feature_Summary</span></span></p>

<p>The values can be encoded as bubble size or as distance from the center or previous level.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_March_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336504i5D712CBD3CFBBEC2/image-size/large?v=v2&amp;px=999" title="word-image-32302-29.png" /><span class="lia-inline-image-caption">Power_BI_March_2026_Feature_Summary</span></span> The last level of nodes can be depicted as bars.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_March_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336503iA3D72E487B851724/image-size/large?v=v2&amp;px=999" title="word-image-32302-30.png" /><span class="lia-inline-image-caption">Power_BI_March_2026_Feature_Summary</span></span></p>

<p>Download this visual from <a href="https://appsource.microsoft.com/en-us/product/power-bi-visuals/excelnaccesscom1597493022219.radial_tree?tab=Overview" rel="noopener" target="_blank">APPSOURCE</a></p>

<p>Download Demo File from <a href="https://customvisualspackages.powerbi.com/publishedpackages/radial50DB3783432B40A69C0B91926CE74CD9.17.0.0.0.pbix" rel="noopener" target="_blank">APPSOURCE</a></p>

<p>For more information visit <a href="https://www.excelnaccess.com/radial-tree/" rel="noopener" target="_blank">excelnaccess</a> or <a href="mailto:zubair@excelnaccess.com" rel="noopener" target="_blank">contact us.</a>
</p><h3>accoCOMMENT – Context-Driven Collaboration in Microsoft Power BI</h3>
accoCOMMENT extends Microsoft Power BI with structured, enterprise-ready commenting — fully integrated with your semantic model and written directly to <strong>your own database</strong>.<p></p>

<p>All comment data is stored together with the <strong>full report context</strong> (filters, dimensions, measures, row selections), ensuring tight integration with your semantic model. This guarantees that every comment is precisely linked to the exact data state it relates to — creating traceability, auditability, and analytical consistency.</p>

<p><strong>Key Features</strong>
<ul>
 	<li><strong>Database Writeback:</strong> All comments are stored in the customer’s own database — not in external services.</li>
 	<li><strong>Context Storage:</strong> Comments are saved together with report filter context for deep semantic integration.</li>
 	<li><strong>Rich Text:</strong> Structured formatting for clear communication.</li>
 	<li><strong>Document Upload:</strong> Attach supporting files directly to comments.</li>
 	<li><strong>Tags &amp; Ratings:</strong> Classify and prioritize insights.</li>
 	<li><strong>Dropdown Lists:</strong> Controlled and validated inputs.</li>
 	<li><strong>Workflow &amp; Dates:</strong> Assign responsibilities and deadlines.</li>
 	<li><strong>Dynamic Measure References:</strong> Insert live measures that automatically update.</li>
 	<li><strong>Highly configurable and adaptable to any existing data model and report.</strong></li>
</ul>
&nbsp;</p>

<p>With accoCOMMENT, Power BI evolves from reporting to a fully governed, context-aware decision platform — without compromising data ownership or model integrity.</p>

<p><strong>Business Use Cases</strong></p>

<p>Sales Funnel Analysis, Financial Follow-Ups (Invoicing/Payments), User Onboarding, and Project Follow-Up</p>

<p>&nbsp;</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_March_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336507i8F702D2E758E4DD1/image-size/large?v=v2&amp;px=999" title="word-image-32302-31.jpeg" /><span class="lia-inline-image-caption">Power_BI_March_2026_Feature_Summary</span></span>
<ul>
 	<li><strong>Try accoCOMMENT for FREE</strong> from&nbsp;<a href="https://marketplace.microsoft.com/en-us/product/accobat.accocomment_enterprise?tab=Overview" rel="noopener" target="_blank">AppSource</a></li>
 	<li><strong>Check out all features of the visual: </strong><a href="https://customvisualspackages.powerbi.com/publishedpackages/accoCOMMENT_4DAA52ABFBF441E2A7898A79384CAFC0.1.0.0.0.pbix" rel="noopener" target="_blank">Demo_file</a></li>
 	<li><strong>Step-by-step instructions: </strong><a href="https://kb.accobat.com/kb/en/accocomment-174716" rel="noopener" target="_blank">Documentation</a></li>
 	<li><strong>Follow accoTOOL</strong>: <a href="https://www.linkedin.com/company/93281786/" rel="noopener" target="_blank">on LinkedIn</a></li>
</ul>
</p><h2>That’s a wrap!</h2>
As always, we appreciate the thoughtful feedback and engagement from the Power BI community—it continues to shape how these features evolve. Many of the updates in this release reflect direct input from customers who are building, scaling, and operationalizing analytics every day.<p></p>

<p>As FabCon gets underway, we encourage you to explore the new capabilities, especially those currently in preview, and share your feedback through the usual channels. Your insights help us refine the experience and inform us what comes next.</p>

<p>Thank you for being part of the Power BI journey. We’re excited to hear what you build with the March updates and to keep the conversation going throughout FabCon and beyond.</p>
