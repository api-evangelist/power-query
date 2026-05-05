---
title: "Dataflows: Thank you for eight years of Gen1—and why Gen2 is the future"
url: "https://community.fabric.microsoft.com/t5/Power-BI-Updates-Blog/Dataflows-Thank-you-for-eight-years-of-Gen1-and-why-Gen2-is-the/ba-p/5173910"
date: "Thu, 02 Apr 2026 16:00:00 GMT"
author: "millopis"
feed_url: "https://community.fabric.microsoft.com/oxcrx34285/rss/board?board.id=fbc_pbiupdatesblog"
---
<p><strong><em>Updated on 20 April 2026:</em></strong><em> Thanks so much for all the engagement on this topic since the original publishing of this blog post on 2 April 2026.&nbsp;We’ve&nbsp;seen several recurring questions, and&nbsp;we’d&nbsp;like to clarify our position on a few key points.</em>&nbsp;</p>

<ul>
<li><strong><em>Dataflow Gen1&nbsp;remains&nbsp;supported</em></strong><em>, but it is in a legacy state and </em><strong><em>won’t&nbsp;receive future innovation</em></strong><em>. We understand many customers have built important,&nbsp;business</em>‑<em>critical&nbsp;solutions on Gen1, and those existing workloads can continue to run while future investments are planned around Dataflow Gen2.</em>&nbsp;</li>
</ul>

<ul>
<li><strong><em>Primary call to action for Premium customers</em></strong><em>: For Premium customers who already have access to Fabric, Dataflow Gen2 is the recommended path to take advantage of the latest improvements across functionality, productivity, performance, pricing, scale, reliability, and more. Many teams find it helpful to start by evaluating Gen2 for new or evolving workloads where these benefits can be realized quickly.</em>&nbsp;</li>
</ul>

<ul>
<li><strong><em>Guidance for Pro and Premium Per User (PPU) customers</em></strong><em>: Many customers rely on Dataflow Gen1 in Pro/PPU today, and it can continue to be the right choice depending on the scenario. If Gen1 best fits your current use case, it&nbsp;remains&nbsp;supported and existing workloads can continue to run as-is. As we introduce new Dataflow Gen2 paths for Pro/PPU scenarios,&nbsp;we’ll&nbsp;share clear guidance and recommended steps to help with a smooth transition.</em>&nbsp;</li>
</ul>

<ul>
<li><strong><em>GCC support for Premium customers</em></strong><em>: For customers using Dataflows Gen1 in GCC environments on Premium, </em><strong><em>Dataflow Gen2 support in GCC will be available before any future transition milestones</em></strong><em>, ensuring a supported upgrade path.</em>&nbsp;</li>
</ul>

<p><strong><em>More granular Fabric controls</em></strong><em>: Customers have asked for&nbsp;finer</em>‑<em>grained&nbsp;enablement than&nbsp;today’s&nbsp;all</em>‑<em>or</em>‑<em>nothing&nbsp;Fabric switch. Work is underway to provide </em><strong><em>more granular administrative controls</em></strong><em>, including the ability to </em><strong><em>enable only Dataflow Gen2</em></strong><em>, so capabilities can be rolled out incrementally with the right governance.</em>&nbsp;</p>

<p><em>Original post (2 April 2026):</em></p>

<p>For more than eight years, customers have relied on <strong>Power BI Dataflows (Gen1)</strong> as a core part of their analytics solutions. We’re grateful for the trust you placed in the Power Query experience to build reusable, low-code data preparation pipelines that power reports, semantic models, and downstream analytics.</p>

<p>Now, we’re sharing an update on the future of Dataflows.</p>

<p><strong>Dataflows Gen2</strong> builds on everything you know from Gen1—preserving the familiar Power Query authoring experience—while delivering major improvements in scale, flexibility, cost efficiency, and manageability. Going forward, <strong>all new Dataflow innovation will land only in Dataflows Gen2</strong>.</p>

<h2>The future of Dataflows Gen1</h2>

<p>Power BI Dataflows Gen1 has reached the end of active innovation and is moving into a <strong>Legacy</strong> state:</p>

<ul>
<li>Existing Gen1 dataflows will continue to work for the foreseeable future. However, specific retirement dates for Gen1 are <strong>being finalized</strong>, and we’ll share details as plans progress. For customers running Gen1 at <strong>Premium capacity</strong>, we will provide at least 12 months’ notice before Dataflow Gen1 is retired. (If you’re using Gen1 on <strong>Pro</strong> or <strong>Premium-Peruser</strong>, we still strongly recommend planning a move to <strong>Dataflows Gen2</strong> to take advantage of the latest investments.)</li>

<li>In the meantime, Gen1 artifacts will remain available and will be clearly marked as <strong>Legacy</strong> in product experiences, including the <strong>New Artifact</strong> menu.</li>

<li>No new features are planned for Dataflows Gen1. Support will be limited to a narrow set of high impact issues, where changes can be delivered safely within the existing architecture. Many of the remaining Gen1 limitations would require significant architecture changes and are best addressed by moving to Dataflows Gen2, which was designed to solve these scenarios more comprehensively.</li>
</ul>

<p>The previous statements<strong> apply to all Dataflows Gen1</strong>—including usage on <strong>Pro, PPU, and Premium licenses</strong>.</p>

<h2>What’s new in Dataflows Gen2</h2>

<p>Dataflows Gen2 retains the familiar Power Query experience while introducing substantial platform-level improvements to scale, performance, governance, and cost efficiency. The following updates provide additional details on each benefit area to help customers understand the full scope of Gen2 enhancements.</p>

<h3>More flexible destinations</h3>

<p>Dataflows Gen2 supports a significantly broader range of output destinations, enabling alignment with diverse data architectures across business, departmental, and enterprise scenarios.</p>

<ul>
<li><strong>SharePoint and OneDrive</strong> are ideal for business users who need refreshed files (CSV, Excel) for downstream workflows, Office automation, or integrations with Power Automate and Teams.</li>

<li><strong>Azure Data Lake Storage</strong> is a great fit for customers building scalable ingestion pipelines for data science, machine learning, or lakehouse scenarios.</li>

<li><strong>Azure SQL Database / SQL MI</strong> enables operational reporting, standardized relational storage, and hybrid analytics scenarios.</li>

<li><strong>Microsoft Fabric Lakehouse / Warehouse / SQL analytics endpoints</strong> are the most seamless destination option for customers aligning with the Fabric vision. Gen2 integrates deeply with Fabric runtimes, unlocking better performance, more consistent semantics, and governance alignment.</li>

<li><strong>Snowflake and other cloud databases</strong> support multi‑cloud architectures and reduces friction for enterprise customers already standardized on multiple warehouse technologies.</li>
</ul>

<p>This broader range of destinations allows teams to use dataflows as a <strong>general-purpose low-code data ingestion and transformation layer</strong>, enabling many more scenarios never supported before with Dataflow Gen1.</p>

<h3>Improved performance and scale</h3>

<p>Dataflows Gen2 is built on the Fabric runtime and a modernized execution engine that delivers a step‑change in performance, reliability, and scalability.</p>

<ul>
<li><strong>Modern query evaluation</strong> leverages Fabric's elastic compute layer to automatically manage scaling behavior, minimizing the need for manual optimization or workload tuning.</li>

<li><strong>Fast Copy technology</strong> supports high-throughput ingestion into Fabric destinations, enabling sustained data movement measured in gigabytes per minute.</li>

<li><strong>Parallelized execution</strong> enables multiple partitions and transformation steps to be processed concurrently, significantly reducing refresh durations compared to Gen1.</li>

<li><strong>Enhanced support for large datasets</strong> includes improvements in memory handling, high-cardinality data processing, and unbounded ingestion patterns.</li>

<li><strong>Predictable refresh behavior</strong> ensures more consistent performance under varying workload conditions.</li>
</ul>

<p>Together, these improvements establish a more durable and high-performance engine for data preparation, especially in enterprise environments that rely on large or frequently refreshed dataflows.</p>

<h3>Built-in AI assistance</h3>

<p>Dataflows Gen2 introduces integrated AI capabilities designed to accelerate development, improve quality, and reduce the learning curve for users working with complex transformations.</p>

<ul>
<li><strong>Copilot-assisted authoring</strong> converts natural-language instructions into Power Query logic, improving productivity and lowering the barrier to entry for users with limited M expertise.</li>

<li><strong>Code explanation capabilities</strong> translate complex or legacy M scripts into easy-to-understand natural language descriptions, improving maintainability and simplifying onboarding.</li>

<li><strong>Automated performance and foldability recommendations</strong> help users align transformations to foldable patterns, resulting in faster load times and lower compute consumption.</li>

<li><strong>AI-powered data quality insights</strong> assist with identifying semantic types, outliers, and join keys and detecting common data issues early in the pipeline.</li>
</ul>

<p>These capabilities provide consistent guidance across the authoring lifecycle and support organizations with diverse skill levels.</p>

<h3>Richer diagnostics</h3>

<p>Gen2 introduces a more comprehensive set of diagnostics designed to improve traceability, troubleshooting, and operational reliability.</p>

<ul>
<li><strong>Detailed refresh history</strong> now includes detailed timing information to clarify where time is spent during execution.</li>

<li><strong>Expanded logging and instrumentation</strong> provide visibility into foldability decisions, connector behaviors, authentication flows, and network operations.</li>

<li><strong>More consistent refresh semantics</strong> across all destinations ensures uniform behavior regardless of the target storage system.</li>

<li><strong>Greater operational transparency</strong> supports root-cause analysis and reduces the time required to identify and resolve failures.</li>
</ul>

<p>These diagnostic improvements help teams manage dataflows more efficiently and maintain higher levels of operational readiness.</p>

<h3>Tiered pricing and potential cost savings</h3>

<p>The introduction of a tiered pricing model is a major advantage for customers transitioning from Gen1.</p>

<ul>
<li>Gen2 decouples Dataflows execution from Premium capacity consumption, aligning compute usage with Fabric’s capacity unit (CU)–based architecture.</li>

<li>This model allows customers to <strong>pay only for the compute resources required</strong> rather than maintaining always-on Premium capacity for workloads that may be intermittent or variable.</li>

<li>Elastic scaling ensures that high-volume or burst workloads can consume proportionally more compute during peak times, while lighter workloads incur lower costs.</li>

<li>Organizations with unpredictable or seasonal refresh patterns may see <strong>material cost reductions</strong> compared to Gen1 running on Premium capacity.</li>
</ul>

<p>This flexible cost model provides more predictable and efficient resource utilization, particularly for enterprises with diverse or rapidly evolving data refresh patterns.</p>

<h2>Our recommendation: Start planning your upgrade</h2>

<p>If you’re starting a new project, <strong>we strongly recommend using Dataflows Gen2</strong>. It offers better performance, richer diagnostics, built‑in AI, broader destination support, and a more flexible cost model.</p>

<p>For existing Gen1 dataflows, now is the right time to <strong>begin planning your upgrade</strong>:</p>

<ul>
<li>Use <a href="https://learn.microsoft.com/fabric/data-factory/migrate-to-dataflow-gen2-using-save-as" rel="noopener" target="_blank">Save as Dataflow Gen2</a> for quick, low effort upgrades of individual dataflows.</li>

<li>For larger migration scenarios, the <strong>Save As API</strong> enables <strong>bulk migration and automation</strong>, supporting CI/CD workflows.</li>

<li>For programmatic or large‑scale upgrades, refer to the <a href="https://learn.microsoft.com/fabric/data-factory/dataflow-gen2-migrate-from-dataflow-gen1-scenarios" rel="noopener" target="_blank">Migrate to Dataflow Gen2 (CI/CD) guidance</a>.</li>
</ul>

<p>Starting now allows you to modernize incrementally, beginning with a subset of your portfolio while keeping all your Power Query skills fully transferable.</p>

<h2>Thank you</h2>

<p>Thank you again for your long-standing investment in Dataflows and Power Query. We’re excited to support your transition to <strong>Dataflows Gen2</strong> and to help you unlock new capabilities for the next generation of analytics solutions.</p>
