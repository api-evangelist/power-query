---
title: "Power BI April 2026 Feature Summary"
url: "https://community.fabric.microsoft.com/t5/Power-BI-Updates-Blog/Power-BI-April-2026-Feature-Summary/ba-p/5173904"
date: "Wed, 22 Apr 2026 15:00:00 GMT"
author: "kamurray"
feed_url: "https://community.fabric.microsoft.com/oxcrx34285/rss/board?board.id=fbc_pbiupdatesblog"
---
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Welcome to the April Power BI update!</strong></p>
Power BI’s April 2026 update is here, bringing continued improvements across Copilot and AI, reporting, visuals, and modeling. This release includes more flexibility when working with layouts and visuals, expanded Copilot experiences—especially on mobile—and several preview features that continue to enhance performance and authoring workflows. You’ll also find important announcements and deprecation notices to keep in mind as you plan ahead. With FabCon fresh on our minds, now is a great time to dive into what’s new and see what’s coming next.
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">Contents</p>


<hr />

<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">April Power BI Video</p>
https://youtu.be/Nn19PQF59MM
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">April Power BI Desktop</p>
<p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><a href="https://www.microsoft.com/power-platform/products/power-bi/desktop?WT.mc_id=Blog_Desktop_Update" title=""><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336368i631F5ECD2D5FAC5B/image-size/large?v=v2&amp;px=999" title="PBI-download-blog.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span></a></p>
<ul>
 	<li>
<p style="font-size: 16px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Version number: v: <span><b>2.153.910.0</b></span></strong></p>
</li>
 	<li>
<p style="font-size: 16px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><strong>Date published: 21/4/2026</strong></p>
</li>
</ul>

<hr />

<h2>Events and Announcements</h2>
<h3>The FabCon SQLCon live recap series starts April 14<sup>th</sup></h3>
Whether you were there or not, this is your fast track to staying in the loop. In this series, we break down keynotes and corenotes into clear insights and standout demos you can use right away. If it mattered at FabCon, you’ll find it here.

<p>Join us, get inspired, and stay connected to what’s happening across the Fabric community. <a href="https://aka.ms/fabcon_sqlcon/recap" rel="noopener" target="_blank">Register now</a>.
</p><h3>Could you be the next Power BI Dataviz World Champion?</h3>
During the recent world championships, one of the finalists confessed that they almost didn’t enter the contest. When we say, “You’ll never know unless you enter!” we really mean it!<p></p>

<p>Don’t miss your chance to enter the next one. <a href="https://aka.ms/nextworldchamps" rel="noopener" target="_blank">Let us know you are interested</a> and we’ll let you know when it starts!
</p><h2>General</h2>
<h3>Deprecation of Old File Picker Experience in Power BI Desktop</h3>
Starting in April, as part of the SU04 release, users will no longer be able to access the old file picker experience in Power BI Desktop. Last January, we announced an updated file picker experience that provides users with a more intuitive, straightforward way of navigating between files and folders. As of SU04, we are moving the updated experience out of preview and making it the default experience in Power BI Desktop. With this change, users will no longer be able to toggle between the old and updated experience.<p></p>

<p>Note: No action is required from users as part of this deprecation; this is simply an informational announcement.
</p><h3>Deprecating the Built-In Netezza ODBC Driver</h3>
The IBM Netezza ODBC driver has been Generally Available for several weeks, and we are beginning the deprecation from the previously built-in ODBC driver to the newer version.<p></p>

<p>Customers do not need to install the new connector; you may reuse your existing connector but will need to install the new ODBC driver. We encourage customers to do this as soon as possible to ensure a smooth transition.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="IBM_ODBC_Netezza_driver_that_will_be_deprecated_from_Fabric" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336371i4AB6FB2FBBD32769/image-size/large?v=v2&amp;px=999" title="ibm-odbc-netezza-driver-that-will-be-deprecated-fr.jpeg" /><span class="lia-inline-image-caption">IBM_ODBC_Netezza_driver_that_will_be_deprecated_from_Fabric</span></span></p>

<p><em>Image: IBM ODBC Netezza driver that will be deprecated from Fabric.</em></p>

<p>Refer to the <a href="https://learn.microsoft.com/power-query/connectors/ibm-netezza-database" rel="noopener" target="_blank">IBM Netezza ODBC</a> documentation for more information.
</p><h2>Copilot and AI</h2>
<h3>Copilot in Power BI mobile now offers expanded features</h3>
In-report Copilot in Power BI Mobile apps just got a major upgrade: you can now have a full, back-and-forth chat with your report, right from your phone or tablet. Instead of stopping at summaries and prebuilt prompts, in-report Copilot in the mobile app now supports open-ended questions and follow-up conversations, all grounded in the specific report you’re viewing.<p></p>

<p>Ask about a metric or KPI, dig into what’s driving the numbers, and even get AI-generated visualizations to take your analysis further.</p>

<p>Every answer includes citations back to the exact visuals Copilot used, so it’s easy to validate insights and keep exploring with confidence on the go.</p>

<p>On iPhone and iPad, voice dictation makes it even faster to get hands-free answers while you’re prepping for a conversation or reviewing results away from your desk.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Two_mobile_phone_screenshots_display_a_sales_report_for_Contoso_showing_revenue" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336370i3430084C0C40BE52/image-size/large?v=v2&amp;px=999" title="two-mobile-phone-screenshots-display-a-sales-repor.png" /><span class="lia-inline-image-caption">Two_mobile_phone_screenshots_display_a_sales_report_for_Contoso_showing_revenue</span></span></p>

<p><em>Figure: Using in-report Copilot on the Power BI Mobile app to ask natural‑language questions and explore insights directly within a report.</em></p>

<p>To learn more, refer to the documentation <a href="https://learn.microsoft.com/power-bi/explore-reports/mobile/mobile-apps-copilot" rel="noopener" target="_blank">In-Report Copilot in Power BI Mobile Apps</a>
</p><h2>Reporting</h2>
<h3>Modern visual defaults and customize theme improvements (Preview)</h3>
This month's update adds a base theme switcher to the&nbsp;<strong>Customize current theme</strong>&nbsp;dialog (View ribbon &gt; Themes). If your custom theme doesn't yet work with the new modern defaults, you can use the base theme switcher to revert to the previous base theme until you've had a chance to update your custom theme. You can also use the base theme switcher to update an existing report created with an older base theme to the latest base theme.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_the_Customize_current_theme_dialog_showing_the_base_theme_switcher" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336369iD3E20CAFE02517B5/image-size/large?v=v2&amp;px=999" title="screenshot-of-the-customize-current-theme-dialog-s.png" /><span class="lia-inline-image-caption">Screenshot_of_the_Customize_current_theme_dialog_showing_the_base_theme_switcher</span></span></p>

<p><em>Figure: Base theme switcher in </em><strong><em>Customize current theme</em></strong><em> lets you revert to the previous base theme or update an older report to the latest modern defaults.</em></p>

<p>This update also includes common page sizes for each aspect ratio type in the <strong>Canvas settings &gt; Size</strong> drop-down. Custom sizing remains available for any dimensions you need.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Canvas_settings_panel_in_Power_BI_showing_Type_dropdown_set_to_16_9_and_Size_dro" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336376i3D4A51E6E026CF03/image-size/large?v=v2&amp;px=999" title="canvas-settings-panel-in-power-bi-showing-type-dro.png" /><span class="lia-inline-image-caption">Canvas_settings_panel_in_Power_BI_showing_Type_dropdown_set_to_16_9_and_Size_dro</span></span></p>

<p><em>Figure: Canvas settings with preset size options for 16:9 aspect ratio reports in Power BI Desktop.</em></p>

<p>Table and matrix built-in styles have been fixed, with banded rows now enabled by default, as well as default +/- buttons for matrix visuals. Axis colors now also use the correct structural color, fixing issues with the Innovate and Orchid custom themes.</p>

<p>Additionally, the built-in theme tiles have an updated look and the <strong>Reset to default</strong> tile is distinguished from the other built-in theme tiles. The behavior of the tile is not new; it simply clears any custom theme applied, leaving any formatting changes to individual visuals untouched until the visual itself is reset to default in the formatting pane.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_theme_gallery_showing_eight_built-in_theme_options_as_thumbnail_preview" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336377iFD4CB67E478F8F85/image-size/large?v=v2&amp;px=999" title="power-bi-theme-gallery-showing-eight-built-in-them.png" /><span class="lia-inline-image-caption">Power_BI_theme_gallery_showing_eight_built-in_theme_options_as_thumbnail_preview</span></span></p>

<p><em>Figure: Built-in theme gallery in Power BI Desktop with the "Reset to default" option to remove any custom theme and update report to latest base theme.</em></p>

<p>To get the latest version in an existing report, go to the&nbsp;<strong>Customize current theme</strong>&nbsp;dialog and select&nbsp;<strong>Update theme</strong>. Or choose the <strong>Reset to default</strong> tile in the <strong>Theme</strong> drop-down.</p>

<p>Thank you for your feedback during the preview. You can continue to <a href="https://forms.office.com/r/w8djJXSR1A" rel="noopener" target="_blank">provide feedback</a> and learn more about <a href="https://learn.microsoft.com/power-bi/create-reports/power-bi-reports-visual-defaults" rel="noopener" target="_blank">Visual defaults in Power BI reports</a>.
</p><h3>Fixed size layout for card, button slicer, and list slicer visuals</h3>
Card, button slicer, and list slicer visuals now support a <strong>Fixed size</strong> option in the <strong>Layout</strong> section of the format pane. Instead of specifying how many items to display, you can define the exact pixel dimensions for each card, button, or list item. When the visual container isn't large enough to display all items at the specified size, scroll bars appear automatically.<p></p>

<p>This update also renames <strong>Autogrid</strong> to <strong>Fit to space</strong> for clarity. When <strong>Fit to space</strong> is on, items grow or shrink to fill the visual container based on the items present. When <strong>Fit to space</strong> is off, the visual reserves space for the specified number of items, even when fewer items exist. For list slicer, the <strong>Fixed number of buttons option</strong>, equivalent to Autogrid off, is also renamed to <strong>Fit to space</strong> for consistency, especially when changing between visual types.</p>

<p><strong>Fixed size </strong>gives you precise control over each item's dimensions. As you resize the visual container, items maintain their specified height and width rather than scaling proportionally. This behavior is useful for creating consistent layouts across the report page or ensuring uniform button, list, or card sizes across multiple visuals. For list slicers specifically, fixed size provides a more natural experience when working with hierarchies. Expanding and collapsing hierarchy levels causes the number of visible items to change dramatically, and fixed-size items ensure consistent spacing as you navigate through the data.</p>

<p>To use <strong>fixed size:</strong>
<ol>
 	<li>Select your visual.</li>
 	<li>Expand the <strong>Layout</strong> section in the <strong>Format</strong> pane (found under <strong>Multi-card layout</strong> or <strong>Multi-button layout </strong>and toggle <strong>Fixed size</strong> to <em>On</em>.</li>
 	<li>For <em>Vertical</em> arrangement, set the <strong>Height</strong> value in pixels.</li>
 	<li>For <em>Horizontal</em> <strong>arrangement</strong>, set the <strong>Width</strong> value in pixels.</li>
 	<li>For <em>Grid</em> <strong>arrangement</strong>, set both <strong>Height</strong> and <strong>Width</strong> value in pixels.</li>
</ol>
When <strong>Fixed size</strong> is enabled, <strong>Fit to space</strong> is disabled since dimensions are now controlled explicitly.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_Power_BI_Desktop_showing_a_list_slicer_visual_with_the_Format_pane" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336379i06357479AEABDEF4/image-size/large?v=v2&amp;px=999" title="screenshot-of-power-bi-desktop-showing-a-list-slic.png" /><span class="lia-inline-image-caption">Screenshot_of_Power_BI_Desktop_showing_a_list_slicer_visual_with_the_Format_pane</span></span></p>

<p><em>Figure: List slicer with Fixed size enabled and Height set to 30 pixels.</em></p>

<p>To learn more, refer to the documentation for <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-card" rel="noopener" target="_blank">card visuals</a>, <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-button-slicer" rel="noopener" target="_blank">button slicers</a>, and <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-list-slicer" rel="noopener" target="_blank">list slicers</a>.
</p><h3>Card visual: Category interactivity and formatting updates</h3>
The card visual now provides clear visual feedback when you select a category header—the selected card appears highlighted while others dim, making it easy to see your current selection. When you add multiple data columns to the category field, the values concatenate in the category header for a cleaner display. You can also use Edit interactions to control which visuals the card filters, giving you more flexibility in how your report responds to selections. Additionally, top-level images display correctly when the image data is base64 encoded, so you can use images from your data without extra conversion steps.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_card_visual_with_a_category_header_selected_the_selected_card_is_highli" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336378i02FB7DD3855009C2/image-size/large?v=v2&amp;px=999" title="power-bi-card-visual-with-a-category-header-select.png" /><span class="lia-inline-image-caption">Power_BI_card_visual_with_a_category_header_selected_the_selected_card_is_highli</span></span><br />
<em>Figure: Card visual showing category header selection highlighting and dimming.</em></p>

<p>For more information about the card visual, refer to <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-card" rel="noopener" target="_blank">Create a card visual in Power BI</a>.</p>

<p>&nbsp;
</p><h3>Azure Maps visual: Map style picker sync</h3>
When you change the map style using the in-visual style picker, the selected style now persists with the Format pane. Your styling choices stay consistent across both the style picker and the Format pane, giving you predictable behavior as you design your reports.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Azure_Map_visual_in_Power_BI_showing_North_America_with_blue_bubble_markers._An" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336384i7CA6AC8BA479CE9F/image-size/large?v=v2&amp;px=999" title="azure-map-visual-in-power-bi-showing-north-america.png" /><span class="lia-inline-image-caption">Azure_Map_visual_in_Power_BI_showing_North_America_with_blue_bubble_markers._An</span></span></p>

<p><em>Figure: Azure map updating the format pane style when the report creator adjusts the style on the visual itself.</em></p>

<p>For more information about map styling options, refer to&nbsp;<a href="https://learn.microsoft.com/azure/azure-maps/power-bi-visual-get-started" rel="noopener" target="_blank">Get started with Azure Maps Power BI visual</a>.
</p><h3>Easily identify preview visuals in the Visualizations pane</h3>
We appreciate your continued feedback on visuals and have finished addressing the concern that preview visuals weren’t always clearly notifying their preview status. Preview visuals now display&nbsp;<strong>(preview)</strong>&nbsp;after their names in the Visualizations pane, making it easier to identify which visuals are still in preview. Additionally, preview visuals now appear below the divider in the pane (alongside custom and unpinned visuals), clearly separating them from generally available visuals. These changes help you quickly understand when you’re working with a preview feature.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_Visualizations_pane_showing_the_Build_visual_tab_with_visual_type_icons" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336385i0084EB825A02D152/image-size/large?v=v2&amp;px=999" title="power-bi-visualizations-pane-showing-the-build-vis.png" /><span class="lia-inline-image-caption">Power_BI_Visualizations_pane_showing_the_Build_visual_tab_with_visual_type_icons</span></span></p>

<p><em>Figure: Visualization pane when editing a report in Power BI Desktop showing preview visuals below the divider line and with (Preview) after their name.</em></p>

<p>For more information about visuals, refer to <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualizations-overview" rel="noopener" target="_blank">Visualizations overview in Power BI</a>.
</p><h3>Narrative Visual Default Type Update</h3>
The <strong>Narrative visual</strong> currently offers two modes: <strong>Copilot</strong> and <strong>Custom</strong>, giving report authors flexibility in how they generate and customize summaries. Previously, authors needed to explicitly choose which mode to use when creating the visual.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336386iE09E877B58B55752/image-size/large?v=v2&amp;px=999" title="word-image-32376-12.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span></p>

<p>We’ve recently improved this experience by introducing a smarter default. If a user has a <strong>Copilot license</strong>, the Narrative visual now opens in <strong>Copilot mode by default</strong>, making it quicker to get AI‑powered insights right away. We also increased the character limit to 10,000, enabling richer prompts and more detailed narratives. Authors can still easily toggle between Copilot and Custom modes at any time, ensuring full control over their storytelling workflow.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336387i6571BA76F1E01301/image-size/large?v=v2&amp;px=999" title="word-image-32376-13.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span></p>

<p>This improved default is available now, and learn more with the <a href="https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-smart-narrative" rel="noopener" target="_blank">Create Smart Narrative Summaries</a>&nbsp;documentation.
</p><h2>Modeling</h2>
<h3>Direct Lake calculated columns and tables (Preview)</h3>
<strong>Direct Lake storage mode</strong> accelerates time to insights by unlocking incredible performance directly against OneLake, without the need to manage costly, time-consuming refreshes for large volumes of data.
<ul>
 	<li><strong>Calculated columns</strong> (unmaterialized) on <strong>Direct Lake on OneLake</strong> tables is in the process of deployment and will be available in the service in the next few weeks.</li>
 	<li><strong>Calculated tables</strong> referring to <strong>Direct Lake on OneLake</strong> columns.</li>
</ul>
These features are particularly helpful when adding columns and creating tables upstream isn’t feasible, such as when data preparation in OneLake is owned by another team. Refer to the <a href="https://learn.microsoft.com/power-bi/transform-model/desktop-calculated-columns" rel="noopener" target="_blank">Create calculated columns in Power BI Desktop</a> documentation for more information on calculated columns.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_DAX_expression_to_define_a_calculated_column_to_define_customer_ag" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336391i8C668D6C9AB3DE45/image-size/large?v=v2&amp;px=999" title="screenshot-of-dax-expression-to-define-a-calculate.png" /><span class="lia-inline-image-caption">Screenshot_of_DAX_expression_to_define_a_calculated_column_to_define_customer_ag</span></span></p>

<p><em>Figure: To use the feature in Power BI Desktop, you must enable the Direct Lake calculated columns (unmaterialized) preview feature switch.</em>
</p><h3>User context aware calculated columns (Preview)</h3>
We are introducing the ability to make calculated columns user-context aware by dynamically responding to DAX functions including UserCulture(), UserPrincipalName(), CustomData(). This enables new scenarios like data translations, and we’re excited to see the creative ways the community will use this!<p></p>

<p>User-context-awareness can be set for calculated columns on <strong>Direct Lake on OneLake, Import </strong>and<strong> DirectQuery </strong>tables using the <strong>Expression Context</strong> property. Direct Lake on OneLake is in the process of deployment and will be available in the service in the next few weeks. Refer to the <a href="https://learn.microsoft.com/power-bi/transform-model/desktop-calculated-columns#expression-context" rel="noopener" target="_blank">Create calculated columns in Power BI Desktop</a> documentation for more information on user-context-aware calculated columns.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Screenshot_of_a_DAX_expression_in_the_formula_bar_to_dynamically_return_a_column" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336393i77DA19EDA120A54B/image-size/large?v=v2&amp;px=999" title="screenshot-of-a-dax-expression-in-the-formula-bar.png" /><span class="lia-inline-image-caption">Screenshot_of_a_DAX_expression_in_the_formula_bar_to_dynamically_return_a_column</span></span></p>

<p><em>Figure: A DAX expression in the formula bar to dynamically return a column with translated values based on the USERCULTURE() function.</em></p>

<p>In the following example, a multi-lingual semantic model and report uses both data and metadata translations. By changing the language URL parameters to simulate a different browser locale, everything is displayed in Portuguese, including product names from the Product table.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Animated_GIF_of_a_sales_report._The_browser_locale_is_overridden_to_Portuguese_a" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336394iCC73ECF784C410DE/image-size/large?v=v2&amp;px=999" title="animated-gif-of-a-sales-report-the-browser-locale-scaled.gif" /><span class="lia-inline-image-caption">Animated_GIF_of_a_sales_report._The_browser_locale_is_overridden_to_Portuguese_a</span></span></p>

<p><em>Figure: To use the feature in Power BI Desktop, you must enable the User-context-aware calculated columns preview feature switch.</em>
</p><h3>DAX user-defined functions (Preview)</h3>
Alongside our ongoing preview of <a href="https://aka.ms/powerbi-dax-UDFs-blog" rel="noopener" target="_blank">DAX user defined functions</a>, we’ve enhanced the DAX <a href="https://learn.microsoft.com/dax/nameof-function-dax" rel="noopener" target="_blank">NAMEOF</a> function to give you much finer control over how object names are returned. NAMEOF now supports optional parameters that let you choose exactly which part of a table, column, measure, or calendar name to return, and control how that name is formatted for display. The new function signature is:<p></p>

<p>NAMEOF ( &lt;object&gt; [, &lt;component&gt; [, &lt;escaped&gt;]] )</p>

<p>This makes it possible to programmatically reference just the table, just the column, or just the measure and improve usability for display scenarios, while keeping existing behavior unchanged for current models.
</p><h2>Visualizations</h2>
<h3>Date Picker by Powerviz</h3>
The Powerviz <a href="https://appsource.microsoft.com/product/power-bi-visuals/truvizinc1674781244292.date-picker-by-powerviz?tab=Overview" rel="noopener" target="_blank">Date Picker offers</a> a modern calendar view, Presets, Pop-up mode, Smart Button Label, Custom Preset Title, and more, making it a must-have date slicer for Power BI reports. Its rich formatting options help with brand consistency and a seamless UI experience.<p></p>

<p><strong>Key Features</strong>
<ul>
 	<li><strong>Smart Button Label</strong>: Make the Pop-up button instantly understandable by showing the selected range, preset name, or both as per your choice.</li>
 	<li><strong>Custom Preset Title</strong>: Localize preset names to your users’ language. Fully customize what each preset displays across the report.</li>
 	<li><strong>First Day of the Week</strong>: Customize your calendar experience by choosing which day your week starts — perfect for global teams and regional preferences.</li>
 	<li><strong>Display Mode</strong>:&nbsp;Choose between Pop-up and Canvas modes.</li>
 	<li><strong>Presets</strong>:&nbsp;Many commonly used presets like Today, Last Week, YTD, MTD, or create your preset using field.</li>
 	<li><strong>Default Selection</strong>:&nbsp;Control the date period selected when the user refreshes or reopens the report.</li>
 	<li><strong>Filter Type</strong>: Choose between Range and Start/End types.</li>
 	<li><strong>Themes</strong>:&nbsp;15+ pre-built themes with full customization.</li>
 	<li><strong>Holidays and Weekends</strong>: Customize holidays/weekends representation.</li>
 	<li><strong>Month Style</strong>: Select single- or double-month date slicer.</li>
</ul>
Other features included are Multiple date ranges, Import/Export Themes and more.
<ul>
 	<li>Try Date Picker visual for FREE from&nbsp;<a href="https://appsource.microsoft.com/product/power-bi-visuals/truvizinc1674781244292.date-picker-by-powerviz?tab=Overview">AppSource</a></li>
 	<li><a href="https://app.powerbi.com/view?r=eyJrIjoiOTU2MDdiNGItMWM2OC00YjgxLWFlNjgtZDQ4YTNkZjMzZTk0IiwidCI6ImNhODc1ZjVhLTcwNmMtNDFmNS04YTczLWNlMTQ0ZjMxMDhlMyIsImMiOjF9">Check out all features of the visual</a></li>
 	<li><a href="https://docs.powerviz.ai/powerviz/date-picker/introduction">Step-by-step instructions</a></li>
 	<li><a href="https://youtu.be/s-ok18Dgp8s?si=AypC9GtgUbftKkU3">YouTube Video</a></li>
 	<li><a href="https://powerviz.ai/">Learn more about visuals</a></li>
 	<li><a href="https://lnkd.in/gN_9Sa6U">Follow Powerviz<br />
</a></li>
</ul>
<span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336395iC6C5BEEB1F75BE4A/image-size/large?v=v2&amp;px=999" title="word-image-32376-17.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span> <span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336400i674F48C74BA512B1/image-size/large?v=v2&amp;px=999" title="word-image-32376-18.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span>
</p><h3>Drill Down Waterfall PRO by ZoomCharts</h3>
With powerful customization options and intuitive interactions, <strong>Drill Down Waterfall PRO</strong> helps report creators present financial and operational data in a way that is easy to explore and understand. The latest update expands the functionality of <strong>Change thresholds</strong> with a new <strong>Automatic mode</strong> that detects subtotals and calculates the difference between consecutive subtotal segments, enabling clearer storytelling in multi-period reports.<br />
Key features include:
<ul>
 	<li><strong>Automatic change thresholds:</strong> Automatically detect subtotal columns and calculate the change between each consecutive subtotal and the first and last subtotal.</li>
 	<li><strong>Custom Sequence: </strong>Have full control over the column order with the <em>Sequence </em>field.</li>
 	<li><strong>Drill Down: </strong>Use multiple categories to enable drill down directly on the chart.</li>
 	<li><strong>Automatic Subtotal Calculation</strong>: Automatically calculate subtotals if their fields are empty.</li>
 	<li><strong>Annotations: </strong>Display markers and comments on the chart from <strong>Comment and Comment Marker</strong> fields.</li>
 	<li><strong>Customization: </strong>Customize X and Y axes, legends, tooltip content, and adjust the appearance settings for positive, negative and total columns separately.</li>
 	<li><strong>Thresholds: </strong>Display up to four constant or dynamic thresholds as lines or areas.</li>
 	<li><strong>Cross-chart filtering: </strong>Dynamically filter data across multiple visuals to create interactive, insightful and intuitive reports.</li>
</ul>
<a href="https://zoomcharts.com/en/goto/?url=https%3A%2F%2Fmarketplace.microsoft.com%2Fen-us%2Fproduct%2FWA200000767%3Ftab%3DOverview&amp;utm_source=microsoftcom&amp;utm_medium=blog&amp;utm_campaign=feature_summary_april_2026&amp;utm_term=link">Get Drill Down Waterfall PRO on AppSource</a><p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336401iD9E41A6AADF58514/image-size/large?v=v2&amp;px=999" title="word-image-32376-19.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span> <span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336402i0A0B131DBA7ADE3A/image-size/large?v=v2&amp;px=999" title="word-image-32376-20.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span>
</p><p style="font-size: 16px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;">Closing</p>
That’s a wrap for the April 2026 Power BI update. This month’s release builds on recent investments across reporting, modeling, visuals, and Copilot, while introducing new previews for you to explore. As always, we appreciate your feedback—especially on preview features—and encourage you to continue sharing your input as we work on future updates.<p></p>

<p>&nbsp;
</p><p style="font-size: 18px; font-weight: 600; margin-top: 1em; margin-bottom: 0.5em;"><a href="https://www.microsoft.com/power-platform/products/power-bi/desktop?WT.mc_id=Blog_Desktop_Update" title=""><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_April_2026_Feature_Summary" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336368i631F5ECD2D5FAC5B/image-size/large?v=v2&amp;px=999" title="PBI-download-blog.png" /><span class="lia-inline-image-caption">Power_BI_April_2026_Feature_Summary</span></span></a></p>
&nbsp;<p></p>

<p>&nbsp;</p>

<p>&nbsp;</p>
