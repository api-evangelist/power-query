---
title: "Deep Dive into Modern Visual Defaults and Customizing Theme Improvements (Preview)"
url: "https://community.fabric.microsoft.com/t5/Power-BI-Updates-Blog/Deep-Dive-into-Modern-Visual-Defaults-and-Customizing-Theme/ba-p/5173925"
date: "Wed, 18 Mar 2026 13:08:15 GMT"
author: "DataZoe"
feed_url: "https://community.fabric.microsoft.com/oxcrx34285/rss/board?board.id=fbc_pbiupdatesblog"
---
<p><em>If you haven’t already, check out Arun Ulag’s hero blog “</em><a href="https://aka.ms/FabCon-SQLCon-2026-news" rel="noopener" target="_blank"><em>FabCon and SQLCon 2026: Unifying databases and Fabric on a single, complete platform</em></a><em>” for a complete look at all of our FabCon and SQLCon announcements across both Fabric and our database offerings.&nbsp;</em></p>

<hr />

<p>Power BI Desktop visuals now start with a modern look. This preview introduces an updated base theme aligned with&nbsp;<a href="https://fluent2.microsoft.design/" rel="noopener" target="_blank">Fluent 2</a>, featuring subtitles, uniform padding, style presets, and a grey canvas background at 1920x1080 by default. Charts display smooth lines; slicers default to dropdown mode, and buttons have a refreshed appearance without manual formatting.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_report_page_example_using_the_modern_default_theme_KPI_cards_and_charts" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336436iE1A1B6519155E3BE/image-size/large?v=v2&amp;px=999" title="power-bi-report-page-example-using-the-modern-defa.png" /><span class="lia-inline-image-caption">Power_BI_report_page_example_using_the_modern_default_theme_KPI_cards_and_charts</span></span></p>

<p><em>Figure: Modern default report page with updated base theme (Fluent 2 styling).</em></p>

<p>This update is designed to let you produce polished reports without having to use the formatting pane each time you include a visual. Let’s take a deeper look into what’s changed with this new default experience.
</p><h2>Canvas and background updates</h2>
The default canvas size increases to 1920x1080, giving you more space to work with. Only new pages use this setting—the initial page in a report retains the previous default size of 1280x720.<p></p>

<p>The wallpaper and background are now shades of grey, providing better contrast when you add visuals to the page. This subtle change makes your content stand out more clearly against the canvas.
</p><h2>Uniform visual styling</h2>
All visuals now share the same structural font style, colors, and sizes. Axis titles are turned off by default, while titles and subtitles are turned on. You'll also notice a uniform increase in padding and borders with rounded corners applied across visuals.<p></p>

<p>These changes create a cohesive, polished look across your entire report. The styling uses structural colors throughout the theme, so when you customize the current theme through&nbsp;<strong>View</strong>&nbsp;&gt;&nbsp;<strong>Themes</strong>, your changes flow throughout all visuals and apply to new visuals you create.
</p><h2>Style presets by visual type</h2>
Many visuals now include built-in style presets, so you can quickly shift to a different look with a single selection.
<h3>Charts</h3>
Chart visuals offer presets that adjust axis and label visibility. The&nbsp;<strong>Default</strong>&nbsp;preset shows the axis without labels. The&nbsp;<strong>Data labels</strong>&nbsp;preset turns off the axis in favor of data labels and markers where appropriate—particularly useful when working with small multiples.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Example_of_chart_style_presets_in_Power_BI_sales_by_segment_with_a_legend_shown" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336435iBBA2A24B9CB122D5/image-size/large?v=v2&amp;px=999" title="example-of-chart-style-presets-in-power-bi-sales.png" /><span class="lia-inline-image-caption">Example_of_chart_style_presets_in_Power_BI_sales_by_segment_with_a_legend_shown</span></span></p>

<p><em>Figure: Chart style presets (Default vs. Data labels) for quickly changing label and axis visibility.</em></p>

<p>Line charts use smooth lines by default and include two additional presets for straight lines with and without data labels.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Deep_Dive_into_Modern_Visual_Defaults_and_Customizing_Theme_Improvements_Preview" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336441i011F96A82464B2C2/image-size/large?v=v2&amp;px=999" title="line-chart-styling-presets-in-power-bi-showing-s.png" /><span class="lia-inline-image-caption">Deep_Dive_into_Modern_Visual_Defaults_and_Customizing_Theme_Improvements_Preview</span></span>

</p><p>" /&gt;</p>

<p><em>Figure: Line chart default smoothing and alternate presets (straight lines, with/without data labels).</em>
</p><h3>Tables and matrix</h3>
Table and matrix visuals already had many presets available, and these have been refreshed with this update to match the new modern styling.
<h3>Buttons and navigators</h3>
Buttons and navigators now look like Fluent 2 buttons by default. They use your first theme data color as the button color, with styling configured for different states (default, hover, pressed). Multiple style presets are available to customize their appearance further.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Power_BI_button_styling_presets_panel_showing_multiple_button_styles_for_example" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336442i9C68BA7B7E0C9173/image-size/large?v=v2&amp;px=999" title="power-bi-button-styling-presets-panel-showing-mult.png" /><span class="lia-inline-image-caption">Power_BI_button_styling_presets_panel_showing_multiple_button_styles_for_example</span></span></p>

<p><em>Figure: Button and navigator presets with Fluent 2 styling (default/outline/rotation examples).</em>
</p><h3>Cards</h3>
The card visual receives updates that reduce padding and remove the reference label background, creating a cleaner presentation for your key metrics.
<h3>Slicers</h3>
Slicers see significant updates in styling. The classic slicer default changes to dropdown mode. During preview, it may initially appear as a list with dropdown styling—reset the slicer to default to switch it to dropdown mode.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Slicer_presets_in_Power_BI_showing_segment_selections_All_Government_Midmarket_E" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336443iCDEB14119F3DA4D4/image-size/large?v=v2&amp;px=999" title="slicer-presets-in-power-bi-showing-segment-selecti.png" /><span class="lia-inline-image-caption">Slicer_presets_in_Power_BI_showing_segment_selections_All_Government_Midmarket_E</span></span></p>

<p><em>Figure: Slicer style presets with the modern default dropdown slicer experience.</em></p>

<p>The style presets include:
<ul>
 	<li><strong>Default</strong>: Applies styling and changes mode to drop down</li>
 	<li><strong>List</strong>: Changes type and mode to list view</li>
 	<li><strong>Tile</strong>: Changes type and mode to tile view</li>
</ul>
Each preset adjusts both the visual style and the slicer mode in one selection.
</p><h3>Small multiples layout</h3>
Small multiples have been updated to consolidate the categorical axis. Instead of starting in a 2x2 arrangement, small multiples now begin in a 1x4 or 4x1 layout depending on the orientation of your categorical axis. This change provides a more logical default view of your data.<p></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="Bar_chart_with_small_multiples_showing_sales_by_segment_across_countries_Canada" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336445iB83F8C7CC17C3535/image-size/large?v=v2&amp;px=999" title="bar-chart-with-small-multiples-showing-sales-by-se.png" /><span class="lia-inline-image-caption">Bar_chart_with_small_multiples_showing_sales_by_segment_across_countries_Canada</span></span></p>

<p><em>Figure: Updated small multiples default layout (consolidated to the categorical axis, 1×4 or 4×1).</em>
</p><h2>Customizing and resetting themes</h2>
As with any formatting change made directly on a visual, your customizations take precedence over the base theme or any custom theme applied to the report. This remains true until you reset to default.<p></p>

<p>You can now reset individual sections in the formatting pane to default values. This targeted approach avoids resetting data-bound formatting or actions configured on the visual—you only reset the specific section you select.</p>

<p>The base theme on existing reports remains unchanged until you go to&nbsp;<strong>View</strong>&nbsp;&gt;&nbsp;<strong>Themes</strong>&nbsp;&gt;&nbsp;<strong>Customize current theme</strong>&nbsp;and select&nbsp;<strong>Update theme</strong>. The theme schema also supports setting page size and defining reusable named colors.</p>

<p>&nbsp;
</p><h2>Next steps</h2>
<ul>
 	<li><strong>Enable the preview</strong>: Navigate to&nbsp;<strong>Options and settings</strong>&nbsp;&gt;&nbsp;<strong>Options</strong>&nbsp;&gt;&nbsp;<strong>Preview features</strong>&nbsp;and turn on&nbsp;<strong>Modern visual defaults and customizing theme improvements</strong>. This preview is available in Power BI Desktop, and published reports retain the new base theme for editing in the browser.</li>
</ul>
<h3><a href="https://microsoft.sharepoint.com/:w:/s/AzureDataContentStrategy/IQBS4x7ArL5fT5p7WX_8Ts63AdT-2lC_ZNYxlFboykXKLuE?e=lXmXd7&amp;CID=97631665-72f2-f0c9-2a4c-b0d4d515bac3">Learn more</a></h3>
Refer to the <a href="https://learn.microsoft.com/power-bi/create-reports/power-bi-reports-visual-defaults" rel="noopener" target="_blank">Modern visual defaults documentation</a> for detailed guidance on this feature.
<h3>Share feedback</h3>
Try it out and share your thoughts through the <a href="https://forms.office.com/r/w8djJXSR1A" rel="noopener" target="_blank">Modern Visual Defaults (Preview) Feedback form</a>.<p></p>
