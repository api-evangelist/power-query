---
title: "Input slicer: Filter reports and collect user input (Generally Available)"
url: "https://community.fabric.microsoft.com/t5/Power-BI-Updates-Blog/Input-slicer-Filter-reports-and-collect-user-input-Generally/ba-p/5173933"
date: "Tue, 24 Feb 2026 19:00:00 GMT"
author: "DataZoe"
feed_url: "https://community.fabric.microsoft.com/oxcrx34285/rss/board?board.id=fbc_pbiupdatesblog"
---
<p>Previously known as the "text slicer" while in preview, this visual lets you type or paste values directly into a slicer to filter your report—no scrolling or searching through long lists required.</p>

<h2>What you can do with the input slicer</h2>

<p>Report consumers can quickly filter the report to what they are looking for using the input slicer. If you've ever needed to filter a report by a specific order ID, customer name, or product code, the input slicer is designed for exactly that. Instead of selecting items one by one from a dropdown, you can type values directly or use partial text to find matching records.</p>

<p>Traditional slicers work well when you have a manageable number of categories to choose from. But what happens when you have hundreds of customers, thousands of order IDs, or you simply don't know the exact value you're looking for?</p>

<p>This post introduces the input slicer through a few representative scenarios to illustrate how it works and when it’s useful. The examples are meant to show common patterns and possibilities rather than exhaustively cover every configuration option.</p>

<p>The input slicer addresses these scenarios:</p>

<ul>
<li><strong>Type multiple filter values</strong>: Enter order IDs, customer names, or product codes one at a time, pressing Enter after each to build your filter list.</li>

<li><strong>Search with partial matches</strong>: Type a few characters and use the "Contains" or "Starts with" operators to find records when you only remember part of a name.</li>

<li><strong>Collect free-form input</strong>: Use the visual without a data column to capture user input for translytical task flows, such as comments, approval notes, or values for data writebacks.</li>
</ul>

<p>This walkthrough focuses on getting you familiar with the experience; for complete and up‑to‑date configuration details as the feature evolves, see the <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-input-slicer" rel="noreferrer noopener" target="_blank">input slicer documentation on Microsoft Learn</a>.</p>

<h2>Getting started</h2>

<p>To try the input slicer, you can create sample data in a blank report. Open Power BI Desktop, go to&nbsp;<strong>Modeling &gt; New table</strong>, and enter the following DAX expression:</p>

<pre>Sample Products =<br /><br />DATATABLE(<br /><br />"Product", STRING,<br /><br />"Sales", INTEGER,<br /><br />{<br /><br />{"Apple", 150},<br /><br />{"Banana", 200},<br /><br />{"Cherry", 75},<br /><br />{"Date", 50},<br /><br />{"Elderberry", 125},<br /><br />{"Fig", 90},<br /><br />{"Grape", 180}<br /><br />}<br /><br />)</pre>

<p>Sample Products =</p>

<p>Next, create a bar chart using the Product and Sales columns so you can see the filtering in action.</p>

<h3>Step 1: Add the input slicer</h3>

<p>Select the&nbsp;<strong>input slicer</strong>&nbsp;from the Visualizations pane. Then drag the&nbsp;<strong>Product</strong>&nbsp;column to the slicer's Field well. The slicer displays an input box where you can type filter values.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_report_canvas_showing_an_input_slicer_bound_to_the_Product_field_and_a" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336508iD1203FEBBA5D5CAA/image-size/large?v=v2&amp;px=999" title="power-bi-report-canvas-showing-an-input-slicer-bou.png" /><span class="lia-inline-image-caption">Power_BI_report_canvas_showing_an_input_slicer_bound_to_the_Product_field_and_a</span></span></p>

<p><em>Figure: Input slicer added to the report to filter the Product field.</em></p>

<h3>Step 2: Type or paste values</h3>

<p>Type a value like "a" in the input box and press <strong>Enter</strong>. The value appears as a pill, and your bar chart filters to show only products containing the letter "a" (Apple, Banana, Date, Grape).</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Input_slicer_with_an_entered_value_shown_as_a_pill_and_a_bar_chart_filtered_to_p" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336511iE0340BA1293FF337/image-size/large?v=v2&amp;px=999" title="input-slicer-with-an-entered-value-shown-as-a-pil.png" /><span class="lia-inline-image-caption">Input_slicer_with_an_entered_value_shown_as_a_pill_and_a_bar_chart_filtered_to_p</span></span></p>

<p>Figure: <em>Typing a value and hitting Enter creates a pill and filters the visual to matching products.</em></p>

<h3>Step 3: Choose a filter operator</h3>

<p>Select the <strong>dropdown arrow</strong> on the slicer to choose how your entered values match the data. The following filter operators are available:</p>

<ul>
<li><strong>Contains all</strong>: Records must contain all entered values</li>

<li><strong>Contains any</strong>: Records contain at least one entered value (default)</li>

<li><strong>Does not contain any</strong>: Excludes records with any entered value</li>

<li><strong>Starts with any</strong>: Records start with any entered value</li>

<li><strong>Does not start with any</strong>: Excludes records starting with any entered value</li>

<li><strong>Is any</strong>: Records exactly match any entered value</li>

<li><strong>Is not any</strong>: Excludes exact matches</li>
</ul>

<p>For example, change the filter operator to&nbsp;<strong>Starts with any</strong>&nbsp;to only see values that start with the text you entered. Report creators set the initial operator, but consumers can change it at any time when viewing the report.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Input_slicer_operator_dropdown_showing_text-match_options_such_as_Contains_Start" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336513iBA5DBAE7458BCAEB/image-size/large?v=v2&amp;px=999" title="input-slicer-operator-dropdown-showing-text-match.png" /><span class="lia-inline-image-caption">Input_slicer_operator_dropdown_showing_text-match_options_such_as_Contains_Start</span></span></p>

<p><em>Figure: Choose how typed values are matched using the slicer’s operator menu (for example, Starts with any).</em></p>

<h3>Step 4: Configure multiple values</h3>

<p>By default, the slicer accepts multiple filter values. To allow only a single value, go to&nbsp;<strong>Format &gt; Slicer settings &gt; Options</strong>&nbsp;and turn off&nbsp;<strong>Accept multiple values</strong>.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_Format_pane_open_to_Slicer_settings_showing_the_option_to_enable_or_dis" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336515i138EBBDB38EAA26E/image-size/large?v=v2&amp;px=999" title="power-bi-format-pane-open-to-slicer-settings-show.png" /><span class="lia-inline-image-caption">Power_BI_Format_pane_open_to_Slicer_settings_showing_the_option_to_enable_or_dis</span></span></p>

<p>Figure: <em>Control whether the input slicer accepts one value or multiple values in Slicer settings.</em></p>

<p>To filter by multiple values, type another value and press <strong>Enter</strong>. Each value becomes its own pill, and the report filters to records matching any of the entered values.</p>

<h2>Other example scenarios</h2>

<p>The following are some other scenarios that would work with the input slicer.</p>

<h3>Scenario 1: Sales team reviewing specific accounts</h3>

<p>A sales manager needs to review 10 specific accounts flagged for follow-up. They type each account ID into the input slicer, pressing Enter after each one, and change the filter operator <strong>is any</strong>&nbsp;for exact matches. The report instantly filters to show only those accounts, letting them focus on the data that matters.</p>

<h3>Scenario 2: Support team finding customer tickets</h3>

<p>A support agent needs to find tickets for a customer but only remembers the last name starts with "John." Using the&nbsp;<strong>Starts with any</strong>&nbsp;operator, they type "John" and see all matching customers—Johnson, Johnston, Johnstone—without scrolling through thousands of entries.</p>

<h3>Scenario 3: Data writebacks with translytical task flows</h3>

<p>A report includes an input slicer without a data column connected. Users type comments or approval notes into the slicer, and a button configured with&nbsp;<a href="https://learn.microsoft.com/power-bi/create-reports/translytical-task-flow-overview" rel="noreferrer noopener" target="_blank">translytical task flows</a>&nbsp;submits that input to update the underlying database—all without leaving the report.</p>

<h2>Wrapping up</h2>

<p>The input slicer gives report creators a simple, flexible way to filter data when traditional slicers fall short—especially when you’re working with large lists, partial values, or free‑form input. By typing values directly into the report, you can quickly focus on what matters without extra navigation or setup. Whether you’re narrowing results to a known set of IDs or enabling new interaction patterns in your reports, the input slicer opens up new ways to work with data.</p>

<h2>Next steps</h2>

<p>Try out the input slicer now available when creating reports in Power BI Desktop and the Power BI service and read the full documentation at <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-input-slicer" rel="noreferrer noopener" target="_blank">Create and use an input slicer</a>. For the most current guidance, settings, and limitations as the feature evolves, refer to the input slicer documentation on Microsoft Learn.</p>
