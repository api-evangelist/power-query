---
title: "Power BI February 2026 Feature Summary"
url: "https://community.fabric.microsoft.com/t5/Power-BI-Updates-Blog/Power-BI-February-2026-Feature-Summary/ba-p/5173936"
date: "Tue, 24 Feb 2026 16:00:00 GMT"
author: "kamurray"
feed_url: "https://community.fabric.microsoft.com/oxcrx34285/rss/board?board.id=fbc_pbiupdatesblog"
---
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Welcome to the February Power BI update!</strong></p>
<span>Power BI’s February 2026 update is here, and it’s a good one. This release brings smarter Copilot and AI experiences, more flexible ways to interact with reports, polished visuals, and useful modeling enhancements—plus a few important updates to keep in mind. With FabCon right around the corner, it’s the perfect time to explore what’s new and get excited about what’s next</span>. To get the scoop from experts and meet other enthusiasts, <a href="https://aka.ms/fabcon" rel="noopener" target="_blank">join us in Atlanta in March</a>!
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Meet the four finalists of the Dataviz World Championships on March 4th </strong></p>
Ever wondered what separates great data visualization from world‑class? This is your chance to find out, straight from the best in the world. Join us for an exclusive session with the four finalists heading to finals at FabCon, where they will battle it out for the title of 2026 Power BI DataViz World Champion. Before they step onto the global stage, you’ll get an inside look at how these elite designers think, create, and win.

<p>Register for the session and get access to the recording on March 4<sup>th</sup> at 12pm PT.</p>

<p><a href="https://developer.microsoft.com/reactor/events/26851/" rel="noopener" target="_blank">Learn more</a>&nbsp;about how to enter and view the entries from the first week, happening now.
</p><p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Less than one month until FabCon – will we see you there?</strong></p>
Join us for the ultimate Power BI, Microsoft Fabric SQL, Real-Time Intelligence, AI, and Databases community-led event from March 16-20, 2026, in Atlanta, GA. The third annual FabCon Americas will feature sessions from your favorite Microsoft and community speakers, keynotes, more opportunities to Ask the Experts for 1:1 support, an engaging community lounge with opportunities to network and connect with your peers, a dedicated partner pre-day, a packed expo hall, attendee favorites Power Hour and the Data Viz World Championships live finals, and a can’t-miss attendee party at the Georgia Aquarium.<p></p>

<p><a href="https://aka.ms/fabcon" rel="noopener" target="_blank">Register</a>&nbsp;with code FABCOMM to save $200.
</p><p style="font-size: 22px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">Contents</p>

&nbsp;
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">February Monthly Update Video</p>
https://youtu.be/O21vXCpYdCc
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">February Power BI Desktop</p>
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><a href="https://www.microsoft.com/power-platform/products/power-bi/desktop?WT.mc_id=Blog_Desktop_Update"><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336368i631F5ECD2D5FAC5B/image-size/large?v=v2&amp;px=999" title="PBI-download-blog.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span></a></p>
<ul>
 	<li>
<p style="font-size: 16px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Version number: <span>v:2.151.1052.0 </span></strong></p>
</li>
 	<li>
<p style="font-size: 16px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Date published: 02/20/2026</strong></p>
</li>
</ul>
&nbsp;
<h2>General</h2>
<h3>Deprecation of Hierarchies in Power BI scorecards</h3>
Starting April 15, 2026, the Hierarchies feature in Power BI Scorecards will be removed. Hierarchies allow users to define a multi-level structure (e.g. by region, division, team) and automatically generate filtered scorecard views for each slice of data.<p></p>

<p>The Heatmap view, which was tied to hierarchies, will also be discontinued. <strong>Scorecards themselves will continue to work as usual;</strong> no other functionality is being removed. If you currently use hierarchies or heatmap view, these specific capabilities will no longer be available after the deprecation date.</p>

<p>We appreciate your understanding as we streamline the experience to focus on core Scorecard functionality. For more information on Scorecards refer to <a href="https://learn.microsoft.com/power-bi/create-reports/service-goals-create" rel="noopener" target="_blank">Create scorecards and manual goals</a>.
</p><h3>Deprecation of SSRS, PBIRS and SSAS Management Packs in SCOM</h3>
Microsoft has officially announced the deprecation of the System Center Operations Manager (SCOM) Management Packs for SQL Server Reporting Services (SSRS), Power BI Report Server (PBIRS), and SQL Server Analysis Services (SSAS). While these management packs will remain available, they will no longer be supported after<strong> January&nbsp;2027</strong>, and no future updates are planned, including compatibility with SQL Server&nbsp;2025 or SCOM&nbsp;2025. Customers should begin planning their transition to modern, Azure‑based monitoring solutions to ensure continued reliability and coverage. For full details and guidance on Azure‑based alternatives, refer to the <a href="https://techcommunity.microsoft.com/blog/sqlserver/deprecation-announcement-ssrspbirs-and-ssas-management-packs-for-scom/4486497" rel="noopener" target="_blank">Deprecation Announcement</a>.
<h3>Deprecation of legacy Import Excel &amp; CSV experience in Power BI Service</h3>
Excel and CSV files remain a valid data source for Power BI semantic models and reports. You can continue to use them to create reports in Power BI service from the <strong>Create</strong> page or in Power BI Desktop.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_the_Power_BI_Service_Create_page_with_the_legacy_old_Excel_and_CSV" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336519i0A8C7672E4FD6FD7/image-size/large?v=v2&amp;px=999" title="screenshot-of-the-power-bi-service-create-page-wit-1-1024x420.png" /><span class="lia-inline-image-caption">Screenshot_of_the_Power_BI_Service_Create_page_with_the_legacy_old_Excel_and_CSV</span></span></p>

<p>Figure: Screenshot of the Power BI Service Create page with the legacy / old Excel and CSV import option outlined in red.</p>

<p>This announcement applies specifically to users who created reports using the old experience to import an Excel or CSV file from the <strong>Create</strong> page in the service. There's no impact for users who created semantic models in Power BI Desktop.</p>

<p>Entry points to the legacy experience will be removed on May 31, 2026, and semantic models created using the legacy experience will stop refreshing on July 31, 2026. Reports created from the legacy experience need to be recreated to continue updating. For guidance, refer to the documentation:
<ul>
 	<li><a href="https://learn.microsoft.com/power-bi/connect-data/service-excel-workbook-files" rel="noopener" target="_blank">Get data from Excel workbook files</a></li>
 	<li><a href="https://learn.microsoft.com/power-bi/connect-data/desktop-import-excel-workbooks" rel="noopener" target="_blank">Import Excel workbooks into Power BI Desktop</a></li>
 	<li><a href="https://learn.microsoft.com/power-bi/connect-data/service-get-data-from-files#where-to-save-your-file" rel="noopener" target="_blank">Get data from files for Power BI</a></li>
</ul>
</p><h3>Deprecation of the Simba Vertica ODBC driver</h3>
The deprecation of the Simba Vertica ODBC driver in Power BI connectors will be part of our ongoing efforts to modernize connectivity and improve performance.<p></p>

<p>Starting in February 2026, the Simba Vertica ODBC Driver will begin its deprecation process. Customers using the Vertica connector should transition to the Vertica ODBC driver, which is generally available and will continue to receive investment. For more details, visit <a href="https://learn.microsoft.com/power-query/connectors/vertica-database#use-vertica-odbc-driver" rel="noopener" target="_blank">Power Query Vertica database connector</a>.</p>

<p>This change impacts Power BI Desktop, On-Premises Data Gateway, Dataflows Gen1/Gen2, and Semantic Models. After the deprecation dates, new connections using the legacy drivers will fail, and existing queries may stop working.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336520i85F323A9108ED275/image-size/large?v=v2&amp;px=999" title="Picture5.jpg" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span></p>

<p>To avoid disruptions, please update your environment to install the supported ODBC drivers.
</p><h2>Copilot and AI</h2>
<h3>Expanded prompt input character limit</h3>
Based on customer feedback, we’ve now increased the character limit for the Copilot input from the previous 500 characters to 10K in all Copilot surfaces, including Standalone, Report pane, Apps, Mobile, and Embed. This will allow you to type or copy/paste longer and expressive prompts to Copilot to meet your needs.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336521i5DE1C7B797AD730B/image-size/large?v=v2&amp;px=999" title="word-image-32160-3.png" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span></p>

<p>Learn more at <a href="https://learn.microsoft.com/power-bi/create-reports/copilot-reports-overview" rel="noopener" target="_blank">Use Copilot with Power BI reports and semantic models</a>.
</p><h2>Reporting</h2>
<h3>Filter or enter data in reports with Input slicer (Generally Available)</h3>
The <strong>Text Slicer </strong>is now renamed to <strong>Input Slicer. </strong>This interactive visual lets you filter data using free-form text input when viewing Power BI reports. Unlike other slicers with predefined categories, the input slicer gives you the flexibility to define new filter options—such as exact match, contains, or starts with flexible data exploration. When editing the report, this flexibility is extended further with many formatting options for each part of the input slicer.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Input_slicer_visual_in_a_Power_BI_report_with_the_filter_options_control_availab" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336525i99C425919775ED9C/image-size/large?v=v2&amp;px=999" title="input-slicer-visual-in-a-power-bi-report-with-the-1.png" /><span class="lia-inline-image-caption">Input_slicer_visual_in_a_Power_BI_report_with_the_filter_options_control_availab</span></span></p>

<p>Figure: Input slicer in Power BI report showing the filter options menu (e.g., contains, starts with).</p>

<p>With general availability, you can now choose more filter options. Report consumers can choose from:
<ul>
 	<li>Contains any</li>
 	<li>Contains all</li>
 	<li>Does not contain any</li>
 	<li>Starts with any</li>
 	<li>Does not start with any</li>
 	<li>Is any</li>
 	<li>Is not any</li>
</ul>
A <strong>filter options icon</strong> now shows in all reports with the input slicer using a data column to slice. Report authors can choose to have only the filter options icon show or have the filter options text also show in the slicer. Whether you're searching for specific product names, customer identifiers, or any text-based data, the Input Slicer provides a powerful and intuitive way to dynamically filter your reports.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336526iCA76069B950A4284/image-size/large?v=v2&amp;px=999" title="the-image-is-a-data-table-in-a-software-interface-1-1024x900.png" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span>

</p><p>AI-generated content may be incorrect." width="525" height="461" /&gt;</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336528iD09C7C6FC6495FEA/image-size/large?v=v2&amp;px=999" title="the-image-displays-a-map-like-interface-with-a-blu-1-1024x894.png" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span>

</p><p>AI-generated content may be incorrect." width="525" height="458" /&gt;</p>

<p>Beyond filtering, the input slicer can also be configured for user input with Translytical Task Flows. Without a data column in the build pane, you disable its filtering capability and report consumers can simply enter in any value to pass to the Fabric user data function. This setup is essential for passing parameters that aren't tied to a specific data field—such as comments, annotations, or external triggers. Once all the user input is received, the button with a Fabric user data function passes the input to wherever it needs to go. This enables powerful workflows like write back, approval, or notifications, without relying on dataset-bound filtering.</p>

<p>Take your report to the next level with the input slicer today! Learn more at <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-text-slicer" rel="noopener" target="_blank">Create and use in input slicer</a> and <a href="https://learn.microsoft.com/power-bi/create-reports/translytical-task-flow-overview" rel="noopener" target="_blank">Understand translytical task flows</a>.
</p><h3>Paste selections into any report slicer</h3>
The <strong>paste</strong> context menu feature on the <strong>slicer</strong> visual lets you apply multiple selections by pasting a list of values—no need to manually select each option one by one. Already available on button and list slicer, this month brings the functionality to the slicer visual too. Pasting selections into slicers streamlines the filtering process, especially when you already have the selections you want to make in Excel, Notepad, or in an email.<p></p>

<p>Simply copy a list of values, with each selection on its own line, and paste them directly into your slicer. In the <strong>header icon</strong> select the <strong>…</strong> to open the context menu and choose <strong>Paste</strong>. Or select the visual and use the keyboard shortcut to paste, usually <strong>CTRL + v.</strong> The slicer then automatically recognizes and applies all matching selections at once. This approach not only saves time but also reduces the likelihood of overlooking values.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_report_slicer_context_menu_showing_the_Paste_option_used_to_apply_multi" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336529i01D2C14294CAF7E4/image-size/large?v=v2&amp;px=999" title="power-bi-report-slicer-context-menu-showing-the-pa-1-1024x722.png" /><span class="lia-inline-image-caption">Power_BI_report_slicer_context_menu_showing_the_Paste_option_used_to_apply_multi</span></span></p>

<p>Figure: Paste a list of values into a slicer using the slicer header menu (… &gt; Paste).</p>

<p>Learn more about pasting values into slicer at <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-slicers?tabs=powerbi-desktop#paste-values-in-slicers" rel="noopener" target="_blank">Slicers in Power BI</a>.
</p><h3>Card visual updates</h3>
The new Card visual brings a visually engaging way to call out key performance indicators in your reports, with extensive formatting options and many ways to incorporate images into your card visual. Create visually rich reports going far beyond simple data points.<p></p>

<p>We heard your feedback that the default of up to 5 callouts in a horizontal layout was too restrictive and changed the default to be up to <strong>10 callouts. </strong>This can be increased further or decreased using the <strong>Format pane</strong>. If you are using the defaults (and did not change the number of columns), the new default will apply to your report.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_report_page_with_a_Card_visual_displaying_multiple_KPI_callouts_for_exa" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336532iBADF64FF3056FEF1/image-size/large?v=v2&amp;px=999" title="power-bi-report-page-with-a-card-visual-displaying-1-1024x253.png" /><span class="lia-inline-image-caption">Power_BI_report_page_with_a_Card_visual_displaying_multiple_KPI_callouts_for_exa</span></span></p>

<p>Figure: New Card visual showing multiple callouts (default increased to 10) and layout options.</p>

<p>When using categories in your Card visual, the experience becomes even more interactive as <strong>selecting a category name will filter other visuals on the page.</strong> To remove the filter, simply select somewhere else on the card to deselect it.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_report_page_illustrating_that_selecting_a_Card_visual_category_applies" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336534iDA30D8926155277C/image-size/large?v=v2&amp;px=999" title="power-bi-report-page-illustrating-that-selecting-a-1-1024x1000.png" /><span class="lia-inline-image-caption">Power_BI_report_page_illustrating_that_selecting_a_Card_visual_category_applies</span></span></p>

<p>Figure: Selecting a category in the Card visual cross-filters other visuals on the page.</p>

<p>Try adding the new Card visual to your next report and experience the difference for yourself! For more details and step-by-step instructions, check out the official documentation at <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-card?tabs=powerbi-desktop" rel="noopener" target="_blank">Create a card visual in Power BI</a>.
</p><h3>Fonts compatible with non-Windows devices for Power BI reports</h3>
Defaults fonts such as Segoe UI in Power BI reports when viewed on a non-Windows device now show as expected. Previously, the font didn’t load and showed as a different font.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_report_screenshot_demonstrating_consistent_font_rendering_on_a_non-Wind" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336536iAF49F0B37D55CB68/image-size/large?v=v2&amp;px=999" title="power-bi-report-screenshot-demonstrating-consisten-1-1024x501.png" /><span class="lia-inline-image-caption">Power_BI_report_screenshot_demonstrating_consistent_font_rendering_on_a_non-Wind</span></span></p>

<p>Figure: Default report fonts (for example, Segoe UI) now render correctly when viewing Power BI reports on non-Windows devices.</p>

<p>Try it out today! Learn more about the default fonts in Power BI and Fabric and other considerations for non-Windows devices at <a href="https://learn.microsoft.com/power-bi/fundamentals/power-bi-browsers" rel="noopener" target="_blank">Supported Browsers for Power BI and Fabric.</a>
</p><h3>Preview visuals update</h3>
We received your feedback regarding the need for clearer communication about visuals that are still in preview. Preview visuals now display "(Preview)" after their name and will soon appear below the divider line with custom and other unpinned visuals.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_visualization_pane_showing_a_preview_visual_with_Preview_appended_to_it" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336538i21F7F54A41D7D0ED/image-size/large?v=v2&amp;px=999" title="power-bi-visualization-pane-showing-a-preview-visu-1.png" /><span class="lia-inline-image-caption">Power_BI_visualization_pane_showing_a_preview_visual_with_Preview_appended_to_it</span></span></p>

<p>Figure: Preview visuals are labeled “(Preview)” in the visualization pane.</p>

<p>You have the flexibility to arrange visuals in the visualization pane as you prefer. Each visual can be pinned or unpinned at any time.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_visualization_pane_showing_the_pin_unpin_control_used_to_change_a_visua" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336539iEB7AA71281557DFC/image-size/large?v=v2&amp;px=999" title="power-bi-visualization-pane-showing-the-pin-unpin-1.png" /><span class="lia-inline-image-caption">Power_BI_visualization_pane_showing_the_pin_unpin_control_used_to_change_a_visua</span></span></p>

<p>Figure: Pin or unpin visuals to control where they appear in the visualization pane.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_visualization_pane_illustrating_preview_visuals_grouped_below_a_divider" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336543iA5797FCEE60EF0C0/image-size/large?v=v2&amp;px=999" title="power-bi-visualization-pane-illustrating-preview-v-1.png" /><span class="lia-inline-image-caption">Power_BI_visualization_pane_illustrating_preview_visuals_grouped_below_a_divider</span></span></p>

<p>Figure: Preview visuals appear below the divider with custom and other unpinned visuals.</p>

<p>To reset the visuals to their default settings, use the <strong>restore default visuals</strong> option found in the three dots menu. This menu is also where you can access visuals that are hidden by default, including the legacy card and multi-card visuals.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_visualization_pane_overflow_menu_showing_Restore_default_visuals_used_t" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336544i69214D2EEEAE3132/image-size/large?v=v2&amp;px=999" title="power-bi-visualization-pane-overflow-menu-showing-1.png" /><span class="lia-inline-image-caption">Power_BI_visualization_pane_overflow_menu_showing_Restore_default_visuals_used_t</span></span></p>

<p>Figure: Use the three-dots menu to restore default visuals or access hidden visuals.</p>

<p>Learn more about <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-report-visualizations" rel="noopener" target="_blank">customizing your visualization pane,</a> try it out and let us know what you think.
</p><h3>Conditional formatting dialog updates</h3>
Additional enhancements are available in the conditional formatting dialog, allowing you to apply data-driven colors to your visuals. For instance, when you select the conditional formatting button beside the bar color, you'll find a wider dropdown menu with helpful tooltips that display field names for easier selection.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_conditional_formatting_dialog_showing_a_wider_field_dropdown_with_toolt" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336547iB23BB3168A58FD70/image-size/large?v=v2&amp;px=999" title="power-bi-conditional-formatting-dialog-showing-a-w-1-1024x619.png" /><span class="lia-inline-image-caption">Power_BI_conditional_formatting_dialog_showing_a_wider_field_dropdown_with_toolt</span></span></p>

<p>Figure: Conditional formatting dialog with an expanded field dropdown and tooltips that show field names.</p>

<p>Try it out today and let us know what you think. Learn more about conditional formatting at <a href="https://learn.microsoft.com/power-bi/create-reports/desktop-conditional-table-formatting" rel="noopener" target="_blank">Apply Conditional Table Formatting in Power BI</a>.
</p><h3>Improved error dialogs in Power BI Desktop</h3>
We have added additional details for errors in visuals on Power BI reports in Power BI Desktop this month. This enhanced error dialog has been available for reports in the browser.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_Desktop_visual_error_dialog_expanded_to_show_technical_details_for_the" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336548i3EF0272914E9D134/image-size/large?v=v2&amp;px=999" title="power-bi-desktop-visual-error-dialog-expanded-to-s-1-1024x384.png" /><span class="lia-inline-image-caption">Power_BI_Desktop_visual_error_dialog_expanded_to_show_technical_details_for_the</span></span></p>

<p>Figure: Power BI Desktop improved error dialog showing expanded technical details for a visual error.</p>

<p>Learn more about errors in visuals and how you can fix them at <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-troubleshoot" rel="noopener" target="_blank">Troubleshoot Visualizations in Power BI</a>.
</p><h3>Azure Maps visual updates</h3>
Based on your feedback, we’ve been working behind the scenes to enhance the performance of the <strong>Azure Maps visual with pie charts</strong>. Starting with the February release, customers will begin to see faster rendering when working with these visuals.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336550i0E739BA1F63C8B8E/image-size/large?v=v2&amp;px=999" title="word-image-32160-17.gif" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span></p>

<p>Figure: The GIF demonstrates loading an Azure maps visual with pie chart before the perf improvement.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336552i45BF45707441E1B4/image-size/large?v=v2&amp;px=999" title="word-image-32160-18.gif" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span></p>

<p>Figure: The GIF demonstrates loading an Azure maps visual with pie chart after the perf improvement.</p>

<p>Learn more about Azure Maps Power BI visual at <a href="https://learn.microsoft.com/azure/azure-maps/power-bi-visual-get-started" rel="noopener" target="_blank">Get started with Azure Maps Power BI visual</a>.</p>

<p><strong>Azure Maps endpoints availability in Korea and Brazil</strong></p>

<p>Azure Maps continues to expand its global footprint with the addition of <strong>two new endpoint regions: Korea and Brazil</strong>. These new regions are now available on the list of supported Azure Maps endpoints, giving customers more flexibility in choosing where their data is processed.</p>

<p>By adding regional endpoints in Korea and Brazil, customers can benefit from lower latency, improved performance, and greater alignment with regional data residency and compliance requirements.</p>

<p>Learn more about Azure Maps Power BI visual Data residency at <a href="https://learn.microsoft.com/azure/azure-maps/power-bi-visual-data-residency" rel="noopener" target="_blank">Azure Maps Power BI visual Data Residency</a>.
</p><h3>Fewer steps to insight in Power BI apps – a more conversational Copilot and app summaries</h3>
We’ve made updates that bring a more conversational Copilot experience to Power BI apps. <strong>Now you can simply ask your question, and Copilot does the work by finding the right reports or data in your app, clarifying only when needed, and getting you to insights faster.</strong> No more pre‑selecting items from a list. Just a smarter, more intuitive Copilot that understands your intent and sources from curated content on your behalf.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_previous_experience_where_item_picking_was_necessary_and_second_sc" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336553i9E3D863681D95C6F/image-size/large?v=v2&amp;px=999" title="screenshot-of-previous-experience-where-item-picki-1-1024x384.png" /><span class="lia-inline-image-caption">Screenshot_of_previous_experience_where_item_picking_was_necessary_and_second_sc</span></span></p>

<p>Figure: Item selection is no longer required. Copilot automatically chooses the most relevant item.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_Copilot_asking_questions_to_clarify_what_the_users_interest_is_in" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336555i7766A2FD0E905068/image-size/large?v=v2&amp;px=999" title="screenshot-of-copilot-asking-questions-to-clarify-1-1024x790.png" /><span class="lia-inline-image-caption">Screenshot_of_Copilot_asking_questions_to_clarify_what_the_users_interest_is_in</span></span></p>

<p>Figure: When more than one relevant item is found, app Copilot will ask a brief clarifying question before choosing the best item to answer from.</p>

<p>In addition, <strong>Copilot can now summarize an app, helping you understand what reporting is available. </strong>Ask things like “Summarize the reporting in this app” or “What does this app cover?” Copilot reviews the report descriptions and returns a clear topical overview of the app’s content. This helps you quickly spot areas of interest, discover what the app includes, and ask more focused follow‑up questions. Copilot keeps answers grounded in the reporting available inside the app.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_an_app_summary_response_from_Copilot" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336559i42721EC7088BBC63/image-size/large?v=v2&amp;px=999" title="screenshot-of-an-app-summary-response-from-copilot-1-1024x502.png" /><span class="lia-inline-image-caption">Screenshot_of_an_app_summary_response_from_Copilot</span></span></p>

<p>Figure: Not sure what the app includes? Now you can ask app Copilot for a summary.</p>

<p>With these updates, <a href="https://learn.microsoft.com/power-bi/create-reports/copilot-apps-overview" rel="noopener" target="_blank">app Copilot</a><strong> helps you navigate the curated context of the app</strong>, guiding you to the right reporting and helping you move naturally from broad understanding to specific, trusted insights.</p>

<p><strong>Future-looking note:</strong> App authors can manage Copilot visibility in your workspace apps today in <em>Update app &gt; Setup &gt; Advanced Settings &gt; Show Copilot in app navigation</em>. Many tenant admins told us you’d like tenant‑wide control as well. We’re actively looking at this and will share updates in the future. Thank you for your continued feedback.
</p><h3>Org Apps now feature Persistent Report Filters and Reset Functionality (Preview)</h3>
Org apps (Preview) have been updated to retain Power BI report filters, slicers, and other data view changes you make. The persistent filters setting is enabled by default for all reports. When persistent filters are enabled, your data view changes persist as you move from report page to report page and between visits to the org app.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_a_report_in_an_app_with_the_filter_pane_open_and_some_filter_value" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336560i2DE8F4E3ACE49E5C/image-size/large?v=v2&amp;px=999" title="screenshot-of-a-report-in-an-app-with-the-filter-p-1-1024x327.png" /><span class="lia-inline-image-caption">Screenshot_of_a_report_in_an_app_with_the_filter_pane_open_and_some_filter_value</span></span></p>

<p>Figure: Filters applied to a report will now persist in org apps.</p>

<p>Additionally, selecting <strong>Reset to default </strong>will undo your data view changes and return to the defaults set by the report's author.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_the_reset_to_default_button_on_a_report_in_an_app" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336561i2594D27DBC01D314/image-size/large?v=v2&amp;px=999" title="screenshot-of-the-reset-to-default-button-on-a-rep-1-1024x257.png" /><span class="lia-inline-image-caption">Screenshot_of_the_reset_to_default_button_on_a_report_in_an_app</span></span></p>

<p>Figure: Reset to default is now available in org apps.</p>

<p>These updates address customer feedback and close some of the gaps between the current version of apps (workspace apps) and <a href="https://learn.microsoft.com/power-bi/consumer/org-app-items/org-app-items" rel="noopener" target="_blank">org apps (preview)</a>.
</p><h3>Reminder: update on column sizing in tables and matrices</h3>
Last month, we reverted the default column sizing for tables and matrices so columns once again size themselves based on their content. This was driven largely by your feedback.<p></p>

<p>In recent releases, table and matrix visuals automatically expanded their columns to fill available space—a feature added for tables in October and for matrices in November. Many of you noted that this caused small fields to stretch unnecessarily, creating layouts that felt inconsistent or wasted screen space.</p>

<p>Starting with the January release, new reports now default to content-based column sizing. This makes tables and matrices more compact, easier to read, and better aligned to the actual data.</p>

<p>You can still manually adjust column widths, or use <em>Grow to Fit</em> to expand columns when needed. But by default, visuals now prioritize content-driven sizing, giving you cleaner, more predictable layouts right out of the box.</p>

<p>Learn more about <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-tables?tabs=powerbi-desktop#adjust-column-width" rel="noopener" target="_blank">adjusting column width in the table and matrix.</a>
</p><h2>Modeling</h2>
<h3>TABLEOF and NAMEOF DAX functions</h3>
We’re introducing a new DAX function called <strong>TABLEOF</strong>, a close companion to <strong>NAMEOF</strong>.<p></p>

<p><strong>NAMEOF</strong> and <strong>TABLEOF</strong> help you write DAX that’s safer and easier to maintain. They let you reference model objects that auto-adapt to renames and works cleanly inside <a href="https://learn.microsoft.com/dax/best-practices/dax-user-defined-functions" rel="noopener" target="_blank">UDFs</a>, reducing the fragile text‑based patterns.</p>

<p><a href="https://learn.microsoft.com/dax/nameof-function-dax" rel="noopener" target="_blank">NAMEOF</a> was originally added to support Field Parameters, though it remained undocumented until now. It returns the <em>name</em> of a table, column, measure, or calendar as a text string. Because NAMEOF produces names dynamically, it helps you write more resilient DAX—formulas that automatically adapt when objects are renamed, rather than relying on Power BI Desktop to update references for you. It’s especially useful in <a href="https://learn.microsoft.com/power-bi/create-reports/power-bi-field-parameters" rel="noopener" target="_blank">field parameters</a>, <a href="https://learn.microsoft.com/power-bi/transform-model/calculation-groups" rel="noopener" target="_blank">calculation groups</a> and UDFs.</p>

<p><a href="https://learn.microsoft.com/dax/tableof-function-dax" rel="noopener" target="_blank">TABLEOF</a> works similarly, but instead of returning a text string, it returns a reference to the table associated with a given column, measure, or calendar. For example, this expression returns the number of rows in the <em>Customer</em> table:<br />
<pre>EVALUATE ROW ( "RowCount", COUNTROWS ( TABLEOF ( 'Customer'[Customer ID] ) ) )</pre><br />
TABLEOF becomes even more powerful when used inside UDFs. The following UDF returns the average of a provided column by another:<br />
<pre>DEFINE</pre></p>

<p>FUNCTION</p>

<p>FlexibleAverage = (</p>

<p>averageColumn: ANYREF,</p>

<p>averageByColumn: ANYREF</p>

<p>)</p>

<p>=&gt;</p>

<p>SUMMARIZE (</p>

<p>TABLEOF ( averageColumn ),</p>

<p>averageByColumn,</p>

<p>"avg",</p>

<p>AVERAGE ( averageColumn )</p>

<p>)</p>

<p>EVALUATE</p>

<p>FlexibleAverage ( 'Sales'[Extended Amount], 'Product'[Category] )<br />
As a more advanced example, you can use TABLEOF to build a flexible iterator function that identifies the most frequently occurring value or values of an expression evaluated over a column. The UDF below, MODEX, uses TABLEOF to operate over the correct table automatically:<br />
<pre>DEFINE</pre></p>

<p>FUNCTION MODEX = (</p>

<p>e : ANYREF</p>

<p>) =&gt;</p>

<p>VAR newTable =</p>

<p>ADDCOLUMNS ( TABLEOF ( e ), "expr", e )</p>

<p>VAR freqTable =</p>

<p>GROUPBY ( newTable, [expr], "count", SUMX ( CURRENTGROUP (), 1 ) )</p>

<p>VAR maxCount =</p>

<p>MAXX ( freqTable, [count] )</p>

<p>VAR topResults =</p>

<p>FILTER ( freqTable, [count] = maxCount )</p>

<p>RETURN</p>

<p>SELECTCOLUMNS ( topResults, "expr", [expr] )</p>

<p>EVALUATE</p>

<p>MODEX ( [Total Sales] )<br />
You can find more details about <a href="https://learn.microsoft.com/dax/best-practices/dax-user-defined-functions" rel="noopener" target="_blank">DAX UDFs</a>, <a href="https://learn.microsoft.com/dax/nameof-function-dax" rel="noopener" target="_blank">NAMEOF</a> and <a href="https://learn.microsoft.com/dax/tableof-function-dax" rel="noopener" target="_blank">TABLEOF</a> in our documentation.
</p><h2>Visualizations</h2>
<h3>Drill Down Pie PRO (Filter) by ZoomCharts</h3>
Pie PRO (Filter) enhances pie and donut charts in Power BI with advanced labeling and flexible category level reference markers, enabling users to understand performance context and interact with data directly on the chart.<p></p>

<p><strong>Key Features</strong></p>

<p><strong>Advanced label customization -</strong> configure names, values, and percentages. Arrange them across multiple lines. Apply custom fonts, colors, and backgrounds. Hide secondary details to keep attention to the most important information.</p>

<p><strong>Category level performance markers - </strong>reference markers appear at the slice level, making it easy to see which categories are below, meeting, or exceeding a target without switching visuals or adding complex calculations. Add reference markers per category using any UTF 8 character or icon including symbols or emojis.</p>

<p><strong>One click drill down - </strong>click on one or multiple slices to instantly filter other visuals in the report, combining performance insight with intuitive data exploration.</p>

<p><strong>Images on slices </strong>- add images on slices to visually differentiate categories.</p>

<p><strong>Key use cases</strong>
<ul>
 	<li>Category performance comparison with custom visual indicators</li>
 	<li>Reports that require expressive yet compact labeling</li>
 	<li>Executive dashboards where fast interpretation is critical</li>
</ul>
<a href="https://zoomcharts.com/en/goto/?url=https%3A%2F%2Fmarketplace.microsoft.com%2Fen-gb%2Fproduct%2FWA200001678%3Ftab%3DOverview&amp;utm_source=microsoftcom&amp;utm_medium=blog&amp;utm_campaign=feature_summary_february_2026&amp;utm_term=link" rel="noopener" target="_blank">Get Pie PRO (Filter) on AppSource</a></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336564i3FAE3321B04CE658/image-size/large?v=v2&amp;px=999" title="word-image-32160-24-713x1024.png" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span> <span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336565iE1639160ECC5FF27/image-size/large?v=v2&amp;px=999" title="word-image-32160-25-713x1024.png" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span>
</p><h3>Rich titles in Zebra BI Charts</h3>
That moment when someone says, “<em>Quick one, what exactly is this chart showing?</em>” is where review meetings start to slow down. Across a reporting cycle, those micro-pauses can add <strong>minutes lost on orientation</strong> instead of analysis.<p></p>

<p>In Power BI, chart titles often need to carry the full context, but with limited in-title formatting it’s <strong>hard to make key parts stand out</strong>. A title like “Q4 2024 Europe Division Net Revenue in mEUR vs Plan and Prior Year” may be accurate, but it isn’t scan friendly.</p>

<p><a href="https://bit.ly/3LEKmLc" rel="noopener" target="_blank">Rich titles in Zebra BI Charts</a> (also available in Tables) let you structure context across multiple lines:</p>

<p>Europe Division<br />
<strong>Net revenue</strong> in mEUR<br />
Q4 2024 AC and PY</p>

<p>This multi-line hierarchy matches <strong>how readers scan reports</strong>: who, what, when. It also aligns with <strong>IBCS recommendations</strong> for clear business communication.</p>

<p>How it helps
<ul>
 	<li><strong>Board and monthly reviews</strong>: reduce PowerPoint reformatting</li>
 	<li><strong>Cross-team standardization</strong>: consistent titles, less QA before decks</li>
 	<li><strong>Executive dashboards</strong>: clearer multi-KPI monitoring without re-reading titles</li>
</ul>
<a href="https://bit.ly/3LEKmLc" rel="noopener" target="_blank">Rich titles</a> work with dynamic titles and Zebra BI’s responsive visuals, so clarity holds up on smaller screens and in exports.</p>

<p>The impact is faster comprehension, smoother discussions, and more time acting on insights.</p>

<p><a href="https://bit.ly/49w2Up2" rel="noopener" target="_blank">Explore more in Zebra BI Charts</a>.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336568iBBA09F4C168426CD/image-size/large?v=v2&amp;px=999" title="word-image-32160-26-819x1024.png" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span>
</p><h3>Rose Donut Pie Chart by Powerviz</h3>
The <a href="https://appsource.microsoft.com/product/power-bi-visuals/truvizinc1674781244292.rose-donut-pie-chart-by-powerviz?tab=Overview" rel="noopener" target="_blank">Rose/Donut/Pie Chart</a> is a powerful visual that lets you build four types of charts - a rose, a rose donut, a donut, and a pie chart. These chart types are commonly used to display part-to-whole relationships, proportions of categorical data, and ratios. Each arc represents the ratio from the total for easy comparison.<p></p>

<p><strong>Key Features</strong>
<ul>
 	<li><strong>Chart Options: </strong>Rose, donut, pie charts with style customization.</li>
 	<li><strong>Data Colors: </strong>Choose from 30+ palettes, including color-blind mode.</li>
 	<li><strong>Fill Patterns: </strong>Apply patterns or use custom images.</li>
 	<li><strong>Smart Labels: </strong>Improve readability with data and leaf labels.</li>
 	<li><strong>Arc Customization: </strong>Easily adjust arc radius, padding, and stroke.</li>
 	<li><strong>Ranking: </strong>Filter Top/Bottom N, show others intelligently.</li>
 	<li><strong>Center Circle: </strong>Multiple layers, text, icons, and images in the center.</li>
 	<li><strong>Mouseover Text: </strong>Display dynamic details when hovering over arcs.</li>
 	<li><strong>Image Labels: </strong>Integrate dynamic image URLs for enhanced visuals.</li>
 	<li><strong>Conditional Formatting: </strong>Detect outliers and set smart rules for measures/categories.</li>
</ul>
Other features included are annotation, grid view, show condition, and accessibility support.</p>

<p><strong>Business Use Cases</strong></p>

<p><strong>Finance, Healthcare, E-commerce, Education, Customer Demographics</strong>
<ul>
 	<li><strong>Try Rose/Donut/Pie Chart for FREE from</strong> <a href="https://appsource.microsoft.com/product/power-bi-visuals/truvizinc1674781244292.rose-donut-pie-chart-by-powerviz?tab=Overview" rel="noopener" target="_blank">AppSource</a></li>
 	<li><strong>Check out all features of the visual: </strong><a href="https://app.powerbi.com/view?r=eyJrIjoiMGFlNzJhMjItNWUxOC00OTUyLTgwY2YtNzA2ZTYyNzYzYTVmIiwidCI6ImNhODc1ZjVhLTcwNmMtNDFmNS04YTczLWNlMTQ0ZjMxMDhlMyIsImMiOjF9" rel="noopener" target="_blank">Demo file</a></li>
 	<li><strong>Step-by-step instructions: </strong><a href="https://docs.powerviz.ai/rose-donut-pie-chart/introduction" rel="noopener" target="_blank">Documentation</a></li>
 	<li><strong>YouTube Video:</strong> <a href="https://youtu.be/I6XUUXWKyrI?si=Ivb8ud7BUSXqdbqi" rel="noopener" target="_blank">Video Link</a></li>
 	<li><strong>Learn more about visuals:</strong> <a href="https://powerviz.ai/" rel="noopener" target="_blank">https://powerviz.ai/</a></li>
 	<li><strong>Follow Powerviz</strong>: <a href="https://lnkd.in/gN_9Sa6U" rel="noopener" target="_blank">https://lnkd.in/gN_9Sa6U<br />
</a></li>
</ul>
<span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336569iB908DF2F76458556/image-size/large?v=v2&amp;px=999" title="word-image-32160-27-713x1024.png" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span> <span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336571i14691882998712E4/image-size/large?v=v2&amp;px=999" title="word-image-32160-28-713x1024.png" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span></p>

<p>&nbsp;</p>

<p>&nbsp;
</p><h2>Other</h2>
<h3>Fabric Copilot capacity tenant setting default update</h3>
Fabric Copilot capacity enables organizations to consolidate Copilot usage across Power BI Desktop, Pro and Premium per-user workspaces into a single designated capacity<p></p>

<p><strong>Beginning on or after February 8, 2026</strong>, the tenant setting <a href="https://learn.microsoft.com/fabric/admin/service-admin-portal-copilot" rel="noopener" target="_blank">Capacities can be designated as Fabric Copilot capacities</a> will be <strong>enabled by default</strong> for all tenants.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_February_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336574iC2EFCF9AEE20D1D1/image-size/large?v=v2&amp;px=999" title="word-image-32160-29-1024x519.png" /><span class="lia-inline-image-caption">Power_BI_February_2026_Feature_Summary</span></span></p>

<p><em>Tenant settings in the Fabric Admin portal showing the option ‘Capacities can be designated as Fabric Copilot capacities toggled to Enabled.</em></p>

<p>This update affects only the tenant setting itself. It will <strong>not </strong>modify any existing capacity configurations. If your organization has not enabled any capacities for Fabric Copilot, this default change will have no impact on your current setup.</p>

<p><strong>What you can do to prepare</strong></p>

<p>No action is required unless your organization prefers<strong> not</strong> to adopt the new default-on behavior.</p>

<p>If your organization wants <strong>to opt out</strong> of the automatic default-on update:
<ol>
 	<li>Turn the Copilot capacity designation setting <strong>on</strong> in the<em> Fabric admin portal</em>.</li>
 	<li>Then turn the setting <strong>off </strong>immediately.</li>
</ol>
This action signals that your organization plans to enable Copilot capacities later, and we will skip applying the automatic change to your tenant.</p>

<p><strong>Learn more: </strong>
<ul>
 	<li><a href="https://learn.microsoft.com/fabric/admin/service-admin-portal-copilot#capacities-can-be-designated-as-fabric-copilot-capacities" rel="noopener" target="_blank">Capacities can be designated as Fabric Copilot capacities</a></li>
 	<li><a href="https://learn.microsoft.com/fabric/enterprise/fabric-copilot-capacity" rel="noopener" target="_blank">Fabric Copilot capacity | Microsoft Fabric</a></li>
</ul>
&nbsp;
</p><p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">Closing</p>
That’s a wrap for February’s updates! We hope these improvements make your day‑to‑day work in Power BI even smoother and more fun to explore. And with <a href="https://aka.ms/fabcon" rel="noopener" target="_blank">FabCon</a> just around the corner, there’s no better time to dive in, swap ideas with the community, and see what’s coming next. We’d love to see you there!<p></p>

<p>&nbsp;
</p><p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">Power BI Desktop</p>
<a href="https://www.microsoft.com/power-platform/products/power-bi/desktop?WT.mc_id=Blog_Desktop_Update"><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336368i631F5ECD2D5FAC5B/image-size/large?v=v2&amp;px=999" title="PBI-download-blog.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span></a><p></p>
