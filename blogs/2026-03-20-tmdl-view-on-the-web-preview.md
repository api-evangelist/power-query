---
title: "TMDL View on the Web (Preview)"
url: "https://community.fabric.microsoft.com/t5/Power-BI-Updates-Blog/TMDL-View-on-the-Web-Preview/ba-p/5173917"
date: "Fri, 20 Mar 2026 21:15:00 GMT"
author: "saralam"
feed_url: "https://community.fabric.microsoft.com/oxcrx34285/rss/board?board.id=fbc_pbiupdatesblog"
---
<p><em>If you haven’t already, check out Arun Ulag’s hero blog “</em><a href="https://aka.ms/FabCon-SQLCon-2026-news" rel="noopener" target="_blank" title=""><em>FabCon and SQLCon 2026: Unifying databases and Fabric on a single, complete platform</em></a><em>” for a complete look at all of our FabCon and SQLCon announcements across both Fabric and our database offerings.&nbsp;</em></p>

<hr />

<p><a href="https://learn.microsoft.com/power-bi/transform-model/desktop-tmdl-view" rel="noopener" target="_blank">TMDL View on the Web</a> will be available in the coming weeks, providing a powerful code-first semantic modelling experience directly to your browser.</p>

<p>With this new capability, Power BI developers can script, modify, and apply changes to semantic model objects using the <a href="https://learn.microsoft.com/analysis-services/tmdl/tmdl-overview?view=sql-analysis-services-2025" rel="noopener" target="_blank">Tabular Model Definition Language (TMDL)</a>—a human-readable code format that describes your entire semantic model as code—without switching to Power BI Desktop or downloading model files.</p>

<p>Watch the TMDL View on the Web demo in the <a href="https://aka.ms/TMDLDemoMonthlyUpdate" rel="noopener" target="_blank">March 2025 Update video</a>.
</p><h2>What is TMDL View on the Web?</h2>
TMDL View on the Web is a new feature in Power BI that enables developers to view and edit semantic models as code directly in the browser using TMDL. It expands the Power BI web modelling experience by introducing a rich code editor for working with TMDL scripts—giving pro developers full transparency into the semantic model code and enabling more efficient workflows through code editing.<p></p>

<p>TMDL View was initially introduced in Power BI Desktop in <a href="https://powerbi.microsoft.com/blog/tmdl-view-generally-available/" rel="noopener" target="_blank">January 2025</a> and became generally available in <a href="https://powerbi.microsoft.com/blog/tmdl-view-generally-available/" rel="noopener" target="_blank">September 2025</a>. Now, we’re introducing the same code-first modelling experience to published semantic models in the workspace—directly in your browser.</p>

<p>No downloads. No switching tools. Just seamless modelling on the web.
</p><h2>Key capabilities and benefits of TMDL View on the Web</h2>
TMDL View on the Web provides the following capabilities:<p></p>

<p><strong>Explore your published semantic model metadata</strong></p>

<p>Get full visibility into all objects and properties within your semantic model, including advanced properties not exposed in the standard UI.</p>

<p>To view the TMDL definition of any object, simply drag and drop it into the editor, or open the context menu and select “Script TMDL to Script tab” or “Script TMDL to Clipboard”.</p>

<p>This makes exploring and understanding your model structure faster and more efficient.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="TMDL_View_on_the_Web_showing_the_TMDL_definition_of_a_semantic_model_object_incl" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336413iDF23B5437CDBE6A4/image-size/large?v=v2&amp;px=999" title="tmdl-view-on-the-web-showing-the-tmdl-definition-o.png" /><span class="lia-inline-image-caption">TMDL_View_on_the_Web_showing_the_TMDL_definition_of_a_semantic_model_object_incl</span></span></p>

<p><em>Figure: Exploring published semantic model metadata in TMDL View on the Web by scripting the TMDL definition of an object, including advanced properties not exposed in the standard modelling UI.</em></p>

<p><strong>Enhanced development efficiency</strong></p>

<p>TMDL View on the Web includes a modern code editor designed to boost productivity with built-in IntelliSense, multiline editing for bulk updates, search and replace capabilities and more. For example, you can use IntelliSense and multiline editing to assign a display folder to all Sales-related DAX measures in a single operation—reducing repetitive work and improving consistency.</p>

<p>You can also take advantage of AI-powered tools such as GitHub Copilot to assist with authoring TMDL scripts. For instance, you can script your model as TMDL, use an AI assistant to generate or modify code, and then paste it back into the editor to preview and apply changes—streamlining your modelling workflow even further.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="TMDL_View_on_the_Web_code_editor_showing_IntelliSense-assisted_multiline_editing" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336414iC9E927AF11E52B3B/image-size/large?v=v2&amp;px=999" title="tmdl-view-on-the-web-code-editor-showing-intellise.png" /><span class="lia-inline-image-caption">TMDL_View_on_the_Web_code_editor_showing_IntelliSense-assisted_multiline_editing</span></span></p>

<p><em>Figure: Using multiline editing and IntelliSense in TMDL View on the Web to assign a display folder across multiple measures in a single operation.</em></p>

<p><strong>Modify any semantic model property/object</strong></p>

<p>Edit properties and objects directly in the browser—including advanced settings such as partition definitions or properties like <strong>isAvailableInMdx</strong>, which are not exposed in the standard modelling interface. This capability gives developers full control over their semantic models, enabling advanced configurations without relying on external tools or downloading the model.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="TMDL_View_on_the_Web_showing_a_TMDL_script_where_the_isAvailableInMdx_property_i" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336416i0E22DC1414BDBCA0/image-size/large?v=v2&amp;px=999" title="tmdl-view-on-the-web-showing-a-tmdl-script-where-t.png" /><span class="lia-inline-image-caption">TMDL_View_on_the_Web_showing_a_TMDL_script_where_the_isAvailableInMdx_property_i</span></span></p>

<p><em>Figure: Editing isAvailableInMdx property in TMDL View on the Web, with a side‑by‑side preview showing the before‑and‑after impact on the TMDL definition.</em></p>

<p><strong>Increased reusability and collaboration</strong></p>

<p>Easily share and reuse semantic model objects by sharing TMDL scripts.</p>

<p>For example, to reuse a Calendar table from another semantic model or from a centralized gallery such as <a href="https://community.fabric.microsoft.com/t5/TMDL-Gallery/bd-p/pbi_tmdlgallery" rel="noopener" target="_blank">TMDL gallery</a>, copy its TMDL script, paste it into your target model, preview the changes, and apply them.</p>

<p><span class="lia-inline-image-display-wrapper"><img alt="TMDL_Gallery_page_showing_a_Calendar_table_example_with_its_TMDL_definition_avai" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336420i5020198B88C897DF/image-size/large?v=v2&amp;px=999" title="tmdl-gallery-page-showing-a-calendar-table-example.png" /><span class="lia-inline-image-caption">TMDL_Gallery_page_showing_a_Calendar_table_example_with_its_TMDL_definition_avai</span></span></p>

<p><em>Figure: TMDL Gallery page showcasing a Calendar table shared as a reusable TMDL script for reuse across semantic models.</em></p>

<p><span class="lia-inline-image-display-wrapper"><img alt="TMDL_View_on_the_Web_displaying_a_TMDL_script_from_the_TMDL_Gallery_pasted_into" src="https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1336421iC3FE362672053F22/image-size/large?v=v2&amp;px=999" title="tmdl-view-on-the-web-displaying-a-tmdl-script-from.png" /><span class="lia-inline-image-caption">TMDL_View_on_the_Web_displaying_a_TMDL_script_from_the_TMDL_Gallery_pasted_into</span></span></p>

<p><em>Figure: Reusing a TMDL script from the TMDL Gallery by pasting it into another model in TMDL View on the Web, previewing the changes, and applying them.</em>
</p><h2>Key differences between TMDL View in Desktop and TMDL View on the Web</h2>
To help you understand how the web experience differs from the Desktop version, here’s a side-by-side comparison of key functional differences between TMDL View in Power BI Desktop and TMDL View on the Web:
<table>
<tbody>
<tr>
<td><strong>Key Difference</strong></td>
<td><strong>TMDL View in Power BI Desktop</strong></td>
<td><strong>TMDL View on the Web</strong></td>
</tr>
<tr>
<td>View mode and Edit mode</td>
<td>No distinct modes—changes can be made and applied to the model at any time</td>
<td>Introduces two modes: View mode (to script and preview changes) and Edit mode (to apply them to the model), enabling safer experimentation before committing changes.</td>
</tr>
<tr>
<td>Script persistence</td>
<td>TMDL scripts are saved as part of the semantic model. A model may contain previously saved scripts.</td>
<td>Scripts do not persist. They are discarded when the semantic model or browser is closed. Previously saved scripts were not displayed.</td>
</tr>
<tr>
<td><a href="https://learn.microsoft.com/power-bi/transform-model/service-semantic-model-version-history" rel="noopener" target="_blank">Version history support</a></td>
<td>Not available.</td>
<td>Leverages workspace version history to restore previous versions of the semantic model if needed.</td>
</tr>
<tr>
<td>Write permissions</td>
<td>Not applicable. Desktop authoring does not rely on workspace permission levels.</td>
<td>Requires write permissions on the semantic model to open and use the experience.</td>
</tr>
</tbody>
</table>
TMDL View on the Web will begin rolling out in preview over the coming weeks. Here's how to prepare:
<ul>
 	<li>Watch the demo: <a href="https://aka.ms/TMDLDemoMonthlyUpdate" rel="noopener" target="_blank">March 2025 Update video</a></li>
 	<li>Explore the documentation:
<ul>
 	<li><a href="https://learn.microsoft.com/analysis-services/tmdl/tmdl-overview?view=sql-analysis-services-2025" rel="noopener" target="_blank">Tabular Model Definition Language</a></li>
 	<li><a href="https://learn.microsoft.com/power-bi/transform-model/desktop-tmdl-view" rel="noopener" target="_blank">TMDL View</a></li>
</ul>
</li>
</ul>
We look forward to seeing how you use TMDL View on the Web to accelerate your semantic modelling workflows and bring code-first development practices to your Power BI projects.<p></p>

<p>Questions? Leave a comment!</p>
