*Verify Missing Objects - DU 6*
=============


Script verifies and displays the missing objects in Dollar Universe 6.
http://github.com/Automic-Community/Verify-Missing-Objects---DU-6

<!-- List of attached files -->
Contents of Solution Package:

						
								*Dollar_Universe-Verify_Missing_Objects.zip
								
						


Documenation and Instructions
---

<p><span><strong class="bbc">Description</strong></span><br />&nbsp;<br />This script verifies and displays the missing objects in Dollar Universe 6. These "missing objects" are objects that are expected by other object but not defined locally.<br />&nbsp;<br />For example: a session uses an uproc but the uproc is not defined locally.</p>
<p>&nbsp;</p>
<p><strong class="title">Target environments:</strong> Windows, Unix</p>
<p><strong class="title">Prerequisites:</strong> Perl</p>
<p>&nbsp;</p>
<p><span><strong class="bbc">Usage</strong></span><br />&nbsp;<br />This is a Perl script. You need then to have perl installed to run it. You can however specify the node name and the area. You then don't need to have Perl everywhere. It can be run remotely.<br />&nbsp;<br />Example:</p>
<pre class="prettyprint lang-auto linenums:0 prettyprinted"><span class="pun">&gt;</span><span class="pln"> perl du_verify</span><span class="pun">.</span><span class="pln">pl EXP hklpmsup01

&nbsp;</span><span class="typ">Checking</span><span class="pln"> </span><span class="typ">Configuration</span><span class="pun">...</span><span class="pln"> &nbsp;</span><span class="typ">Local</span><span class="pln"> node &nbsp;</span><span class="pun">/</span><span class="pln"> area</span><span class="pun">:</span><span class="pln"> EXP

&nbsp;MU missing</span><span class="pun">:</span><span class="pln"> DATABASE_PRD
&nbsp;MU missing</span><span class="pun">:</span><span class="pln"> HKLPM</span><span class="pun">.</span><span class="pln">ORSYP</span><span class="pun">.</span><span class="pln">DEV

&nbsp;</span><span class="typ">Resource</span><span class="pln"> missing</span><span class="pun">:</span><span class="pln"> CHECK_SYSTEM

&nbsp;</span><span class="typ">Uproc</span><span class="pln"> missing</span><span class="pun">:</span><span class="pln"> ALARM_RECONF
&nbsp;</span><span class="typ">Uproc</span><span class="pln"> missing</span><span class="pun">:</span><span class="pln"> U_PRJ005_STARTPURGE
&nbsp;</span><span class="typ">Uproc</span><span class="pln"> missing</span><span class="pun">:</span><span class="pln"> U_PRJ005_Z_OPERATION

&nbsp;</span><span class="typ">Objects</span><span class="pln"> missing</span><span class="pun">:</span><span class="pln"> </span><span class="lit">6</span></pre>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
