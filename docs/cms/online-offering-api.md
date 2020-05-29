---


---

<h1 id="online-offering-api">Online Offering API</h1>
<h2 id="background">Background</h2>
<p>The purpose of the Online Offering API is to allow Ministry of Labour, Training and Skills Development (MLTSD) approved training providers not using the SkillsPass system to list online (E-Learning) offerings in the MLTSD Marketplace.</p>
<p>Note that the API provides a listing service only for the MLTSD Marketplace. Any attempts at booking training will be redirected back to the training provider’s own website, and it is up to the individual training provider to manage that booking accordingly.</p>
<p>The API currently supports only online offerings related to both Joint Health and Safety Committee Part One. This is captured in the <em>trainingStandardKey</em> attribute in the reference documentation, and the complete list of support values is included in the <em>Technical</em> section below. Training providers must always map their class offerings to one of these standard courses.</p>
<p>MLTSD-approved training providers are issued a unique identifier by MLTSD, which must be included with every request. Please refer to the <em>networkKey</em> attribute in the reference documentation.</p>
<h2 id="supported-actions">Supported Actions</h2>
<p><a href="https://bluedrop360apiv2network.docs.apiary.io/#reference/online-offerings/add-online-offering/add-an-online-offering"><em>Add Online Offering</em></a> Call to add an online offering to the MLTSD Marketplace.</p>
<p><a href="https://bluedrop360apiv2network.docs.apiary.io/#reference/online-offerings/online-offering/patch-an-online-offering"><em>Patch Online Offering</em></a> Call to update information for an existing online offering in the MLTSD Marketplace.</p>
<p><a href="https://bluedrop360apiv2network.docs.apiary.io/#reference/online-offerings/online-offering/delete-an-online-offering"><em>Delete Online Offering</em></a> Call to remove an online offering from the MLTSD Marketplace.</p>
<h2 id="technical">Technical</h2>
<p>Supported values for <em>trainingStandardKey</em>:</p>
<ul>
<li><em>JHSC-2014-1-E-O</em>
<ul>
<li>JHSC - Part 1 (English, Online)</li>
</ul>
</li>
<li><em>JHSC-2014-1-F-O</em>
<ul>
<li>JHSC - Part 1 (French, Online)</li>
</ul>
</li>
</ul>

