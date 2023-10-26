**Secure the Intelligent Enterprise with SAP Enterprise Threat
Detection**

**Exercise: Working with SAP Enterprise Threat Detection**

**Version TechEd 2023**

**Based on SAP Enterprise Threat Detection Version 2, Support Package
5**

Table of ContentS

[1. ETD User – ETD Roundtrip and Navigation
[3](#etd-user-etd-roundtrip-and-navigation)](#etd-user-etd-roundtrip-and-navigation)

[1.1. Start Page and Navigation to different tiles
[3](#start-page-and-navigation-to-different-tiles)](#start-page-and-navigation-to-different-tiles)

[1.2. Summary [22](#summary)](#summary)

[2. Security Expert - Working with the Forensic Lab
[22](#security-expert---working-with-the-forensic-lab)](#security-expert---working-with-the-forensic-lab)

[2.1. Filtering Data [23](#filtering-data)](#filtering-data)

[2.2. Modelling Charts [25](#modelling-charts)](#modelling-charts)

[2.3. Browse through the data and model your own individual charts
[28](#browse-through-the-data-and-model-your-own-individual-charts)](#browse-through-the-data-and-model-your-own-individual-charts)

[2.4. Working with Value Lists
[30](#working-with-value-lists)](#working-with-value-lists)

[2.5. Modeling Attack Detection Patterns
[31](#modeling-attack-detection-patterns)](#modeling-attack-detection-patterns)

[2.1. Summary [36](#summary-1)](#summary-1)

[3. ProcessING alerts and investigations
[36](#processing-alerts-and-investigations)](#processing-alerts-and-investigations)

[3.1. Viewing Alerts [37](#viewing-alerts)](#viewing-alerts)

[3.2. Investigating Alerts
[40](#investigating-alerts)](#investigating-alerts)

[3.3. Saving Evidence for Attacks
[49](#saving-evidence-for-attacks)](#saving-evidence-for-attacks)

[3.4. Summary [50](#summary-2)](#summary-2)

[4. Pseudonymization of User Data
[50](#pseudonymization-of-user-data)](#pseudonymization-of-user-data)

[4.1. Determining the True Identity of Users
[50](#determining-the-true-identity-of-users)](#determining-the-true-identity-of-users)

[4.2. Logging Access to User Identities
[53](#logging-access-to-user-identities)](#logging-access-to-user-identities)

[4.1. Summary [53](#summary-3)](#summary-3)

[5. Monitoring DashboardS
[53](#monitoring-dashboards)](#monitoring-dashboards)

[5.1. Viewing Default Monitoring Dashboard
[53](#viewing-default-monitoring-dashboard)](#viewing-default-monitoring-dashboard)

[5.2. Building your own Monitoring Dashboard
[55](#building-your-own-monitoring-dashboard)](#building-your-own-monitoring-dashboard)

[5.1. Summary: [57](#summary-4)](#summary-4)

<u>ETD Demo Users</u>

- Usernames: Demo01, …, Demo29: You get your User ID in the room

- Password: Welcome0

In this exercise replace **\<YOUR_USERNR\>** with your user number:

- DEMO**01** DEMO**ONE**

- DEMO**02** DEMO**TWO**

- ….

- DEMO**10** DEMO**TWENTYNINE**

Make use of the following pattern name for your own created content
(Charts, Patterns, Value-Lists, etc.) in this session:

***\<Chart name\>*** DEMO***\<YOUR_USERNR\>***

# ETD User – ETD Roundtrip and Navigation

**Tool Aspect**: In this Exercise you as an ETD User will be able to
navigate through the most important UIs of SAP Enterprise Threat
Detection. You will get knowledge about different UIs like Monitoring,
Alerts, Forensic Lab, Settings, (De-)Pseudonymization, Patterns, Value
Lists, etc.

## Start Page and Navigation to different tiles

In this Exercise you will open the start page and click on several tiles
to navigate forth and back

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol type="1">
<li><p>After Logging on you are in the launch pad. In this exercise you
will click on each of the red marked tiles to have a 1<sup>st</sup> look
what’s in there.</p></li>
</ol></td>
<td><img src="media/image2.png"
style="width:3.92153in;height:3.98333in" /></td>
</tr>
<tr class="even">
<td><ol start="2" type="1">
<li><p>Click on Tile Monitoring</p></li>
</ol></td>
<td><img src="media/image3.png"
style="width:1.58347in;height:1.79182in" /></td>
</tr>
<tr class="odd">
<td><ol start="3" type="1">
<li><p>The Default Monitoring page will be shown</p></li>
</ol></td>
<td><img src="media/image4.png"
style="width:3.92153in;height:1.89028in" /></td>
</tr>
<tr class="even">
<td><ol start="4" type="1">
<li><p>Click on the small tool icon in the upper right corner and select
another Monitoring page (e.g. Alert Statistics). Another Monitoring page
will be shown. In a later exercise you will learn how to create own
monitoring pages with own charts.</p></li>
</ol></td>
<td><img src="media/image5.png"
style="width:1.75547in;height:0.55769in" /><img src="media/image6.png"
style="width:1.54992in;height:1.91019in" /></td>
</tr>
<tr class="odd">
<td><ol start="5" type="1">
<li><p>Jump back to the launch pad via using upper left arrow or the
home button.</p></li>
</ol></td>
<td><img src="media/image7.png"
style="width:1.13343in;height:0.91675in" /></td>
</tr>
<tr class="even">
<td><ol start="6" type="1">
<li><p>In Tile Patterns, Click on the link ‘All’ or ‘Active’.</p></li>
</ol></td>
<td><img src="media/image8.png"
style="width:1.44179in;height:1.40846in" /></td>
</tr>
<tr class="odd">
<td><ol start="7" type="1">
<li><p>You see the list of the patterns, with their current state, and
how many alerts they raised.</p></li>
</ol></td>
<td><img src="media/image9.png"
style="width:3.92153in;height:0.92292in" /></td>
</tr>
<tr class="even">
<td><ol start="8" type="1">
<li><p>You can jump to the details of any pattern, by clicking on the
pattern name in the list.</p></li>
</ol></td>
<td><img src="media/image10.png"
style="width:3.92153in;height:2.17222in" /></td>
</tr>
<tr class="odd">
<td><ol start="9" type="1">
<li><p>When clicking on ‘Edit’, some parameter of the pattern can be
changed, e.g.:</p>
<ol type="a">
<li><p>Run frequency</p></li>
<li><p>Severity</p></li>
<li><p>Status (Active/Inactive)</p></li>
<li><p>Threshold</p></li>
<li><p>Test Mode Checkbox</p></li>
</ol></li>
</ol>
<p>You can save via using the ‘Save’ button</p></td>
<td><img src="media/image11.png"
style="width:3.9743in;height:0.97686in" /></td>
</tr>
<tr class="even">
<td><ol start="10" type="1">
<li><p>When clicking on the ‘Open’ Button, the Forensic Lab opens and
you can see the modeling of the patterns, as it is delivered by SAP. The
Forensic Lab will be explained in a separate part of this exercise, and
in other exercises about modeling own use cases.</p></li>
</ol></td>
<td><img src="media/image12.png"
style="width:3.61698in;height:0.64172in" /></td>
</tr>
<tr class="odd">
<td><ol start="11" type="1">
<li><p>Click the Home button to jump back to the launch pad.</p></li>
</ol></td>
<td><img src="media/image13.png"
style="width:0.99175in;height:0.64172in" /></td>
</tr>
<tr class="even">
<td><ol start="12" type="1">
<li><p>Klick on Tile ‘Value Lists’</p></li>
</ol></td>
<td><img src="media/image14.png"
style="width:1.44179in;height:1.39179in" /></td>
</tr>
<tr class="odd">
<td><ol start="13" type="1">
<li><p>You see the list containing all value lists. A value list can act
as a block-list or as an allow list. They are used as filter elements in
patterns, all list entries are used to filter based on these value list
entries in an inclusive or exclusive way.</p></li>
</ol>
<blockquote>
<p>Value lists can automatedly updated from outside via a rest endpoint,
if Checkbox ‘Automated’ is switched on.</p>
<p>Values can be added by customers (‘Add’), or SAP delivered values can
be removed (‘Remove Selected’). The changes to standard value lists are
not overwritten by updates.</p>
</blockquote></td>
<td><img src="media/image15.png"
style="width:3.92153in;height:1.86528in" /></td>
</tr>
<tr class="even">
<td><ol start="14" type="1">
<li><p>Go back to launch pad via the left arrow</p></li>
</ol></td>
<td><img src="media/image16.png"
style="width:2.41688in;height:0.65006in" /></td>
</tr>
<tr class="odd">
<td><ol start="15" type="1">
<li><p>Klick on Tile ‘Threat Situation Last Hour’.</p></li>
</ol></td>
<td><img src="media/image17.png"
style="width:1.44179in;height:1.47513in" /></td>
</tr>
<tr class="even">
<td><ol start="16" type="1">
<li><p>The UI shows the correlation between Users, Systems, Patterns,
Alerts, End User Machine Hostnames. The bigger a circle, the more an
entity is involved into the correlations. E.g. in the Screenshot the
User Pseudonym HRLP_7900 is involved in 9 different Alerts, based on two
patterns.</p></li>
</ol>
<blockquote>
<p>By that it can be easily found out where there are hot spots of
Alerts, Suspicious Activities or cyber Attacks correspondingly.</p>
<p>By hovering over an Alert, you can as well jump to the detailed Alert
list</p>
</blockquote></td>
<td><img src="media/image18.png"
style="width:3.92153in;height:1.60625in" /></td>
</tr>
<tr class="odd">
<td><ol start="17" type="1">
<li><p>You can toggle between the Threat Situation graphical view and
the detailed Alert list by clicking on the list button (and back from
the list)</p></li>
</ol></td>
<td><img src="media/image19.png"
style="width:1.67515in;height:0.7834in" /></td>
</tr>
<tr class="even">
<td><ol start="18" type="1">
<li><p>In the alert list, you can see all single alerts with already
some alert triggering information in the column ‘Trigger’. From here you
can jump to:</p>
<ol type="a">
<li><p>The Alert itself, with more detailed descriptions.</p></li>
<li><p>The Pattern description, as you find it in the Tile
‘Patterns’</p></li>
<li><p>The triggering Events, when clicking on the Link ‘Events’ in the
‘Trigger’ Description. This is as well possible from the opened single
alert</p></li>
</ol></li>
</ol></td>
<td><img src="media/image20.png"
style="width:3.92153in;height:1.60278in" /></td>
</tr>
<tr class="odd">
<td><ol start="19" type="1">
<li><p>In order to process alerts, you can mark several alerts belonging
together (i.e. having the same root cause) and start an investigation
(or add to an existing investigation).</p></li>
</ol>
<blockquote>
<p>An investigation is the evidence collection object in ETD. It will be
used for collecting all corelated alerts, screenshots, documents, single
logs, snapshots, etc., and finally provide a state and potential
resolvement. Alert and investigation handling is a separate
exercise.</p>
</blockquote></td>
<td><img src="media/image21.png"
style="width:2.35854in;height:0.30836in" /></td>
</tr>
<tr class="even">
<td><ol start="20" type="1">
<li><p>Click on one of the Alert IDs to jump to the Alert details. From
here you can jump to:</p>
<ol type="a">
<li><p>the pattern definition</p></li>
<li><p>the pattern workspace in the forensic lab. The time frame then
filters automatically to the time when the alert was raised, so you can
see the log events at time of the raising of the alert. Forensic Lab
will be part of another exercise</p></li>
<li><p>the triggering events, so you can see the detailed normalized and
original log data that was analyzed to raise the alert. Alert handling
is part of another excercise</p></li>
<li><p>the related events, by filtering on the alert raising time frame,
and different available correlating attributes (e.g. user, system
,…)</p></li>
</ol></li>
</ol>
<p>Additionally you can see the Severity (Low, Medium, High, Very High)
and a Score. The Pattern related default severity can be automatedly
raised if the system is a critical system related to confidentiality,
integrity and availability. The Score multiplies the pattern criticality
(related to confidentiality, integrity and availability) with the system
criticality related to attacks against confidentiality, integrity and
availability. It can vary between 0 and 100.</p></td>
<td><img src="media/image22.png"
style="width:3.92153in;height:2.54514in" /></td>
</tr>
<tr class="odd">
<td><ol start="21" type="1">
<li><p>Go back to the Alert list by clicking on the ‘back’ arrow. Then
go back to the launch pad by clicking again to the ‘back’ arrow or to
the home-button</p></li>
</ol></td>
<td><img src="media/image23.png"
style="width:0.73788in;height:0.61741in" /> <img src="media/image13.png"
style="width:0.99175in;height:0.64172in" /></td>
</tr>
<tr class="even">
<td><ol start="22" type="1">
<li><p>Click on Tile ‘Knowledge Base’.</p></li>
</ol></td>
<td><img src="media/image24.png"
style="width:1.45013in;height:1.35845in" /></td>
</tr>
<tr class="odd">
<td><ol start="23" type="1">
<li><p>You can choose between 3 lists.</p></li>
</ol>
<p>The list of ‘Semantic Events’ shows all events in a human
understandable wording and with a short explanation. The semantic events
are very often translations from a technical event ID. E.g. the
technical Event AU1 from a SAP Security Audit Log is translated to User,
Logon. The semantic events are used in the forensic lab to be filtered
on. Additional semantic events can be created by customers to be used
when ingesting own log data, that needs to be normalized (learned)</p>
<p>The list of ‘Attributes’ shows all normalized attributes in the Event
Database table with Display Name, short description and data type. Via
each of these attributes a correlation and filtering on events is
possible within the forensic lab. Each of the attributes can be
previewed in the forensic lab with the different scatterings/value
distributions.</p>
<p><strong>Information:</strong> Very often the Attributes are shown in
different roles. E.g, a user acting, and a user targeted. An acting user
can e.g. provide additional roles to a targeted user. Both users are
then part of the same log event, in their different roles.</p>
<p>The list of ‘Log Types’ shows all supported log types with short
names and descriptions. The log types are either the ones that are
supported out of the box or that were created there for usage in the log
learning tool, if ingesting own log data.</p></td>
<td><img src="media/image25.png"
style="width:3.92153in;height:1.43333in" /></td>
</tr>
<tr class="even">
<td><ol start="24" type="1">
<li><p>Go back to the launch pad via the back arrow.</p></li>
</ol></td>
<td><img src="media/image26.png"
style="width:2.01684in;height:0.37503in" /></td>
</tr>
<tr class="odd">
<td><ol start="25" type="1">
<li><p>Klick on Tile ‘System Administration’</p></li>
</ol></td>
<td><img src="media/image27.png"
style="width:1.43346in;height:1.35012in" /></td>
</tr>
<tr class="even">
<td><ol start="26" type="1">
<li><p>You see a list of systems with some major attributes.</p></li>
</ol></td>
<td><img src="media/image28.png"
style="width:3.92153in;height:1.90278in" /></td>
</tr>
<tr class="odd">
<td><ol start="27" type="1">
<li><p>Click on any of the lines to see the details.</p></li>
</ol>
<p>Some of the entries are filled from Meta data arriving from SAP
Application Server ABAP Systems:</p>
<ul>
<li><p>Role (e.g. Production, Test, …)</p></li>
<li><p>System Group</p></li>
<li><p>Database Host, Type, Version</p></li>
<li><p>Application Servers for the System Group</p></li>
</ul>
<p>Other entries can be maintained manually:</p>
<ul>
<li><p>Business Significance with regards to Confidentiality, Integrity
and Availability of the system. <strong>These attributes are multiplied
out with the corresponding pattern attributes for Confidentiality,
Integrity and Availability</strong> (see extra exercise) <strong>and
determine the raise of an Alert Severity as well as the Alert
Score!</strong></p></li>
<li><p>Location</p></li>
<li><p>Contact Persons</p></li>
<li><p>Organizational information (Names, LOB, phone number, mail
address)</p></li>
<li><p>Status (Active/Inactive)</p></li>
<li><p>Landscape Information</p></li>
</ul>
<p><strong>Information</strong>: We distinguish between System Integrity
and Data Integrity. System Integrity describes the integrity of SAP
Basis (e.g. Use cases related to manipulation of system configurations,
Security settings, debugging, etc.), Data integrity describes the
integrity of Business Data (Manipulation of Business data, spy out of
Data Privacy relevant data, etc.)</p>
<p><strong>Information</strong>: The system meta data attributes can be
partly used in the forensic lab to model patterns (e.g. System Type,
System Role, System Location, System ID, System Group ID)</p></td>
<td><img src="media/image29.png"
style="width:3.92153in;height:1.76667in" /></td>
</tr>
<tr class="even">
<td><ol start="28" type="1">
<li><p>Use the Home button to jump back to the launch pad</p></li>
</ol></td>
<td><img src="media/image13.png"
style="width:0.99175in;height:0.64172in" /></td>
</tr>
<tr class="odd">
<td><ol start="29" type="1">
<li><p>Click on Tile ‘Forensic Lab’</p></li>
</ol></td>
<td><img src="media/image30.png"
style="width:1.44179in;height:1.39179in" /></td>
</tr>
<tr class="even">
<td><ol start="30" type="1">
<li><p>In the UI you can see a filtering area on the left side and a
preview area on the right side (Pie Charts).</p></li>
</ol>
<p>In the forensic lab you can do analysis, correlation over all the log
data, semantic attributes, semantic events over shorter or longer time
frames. It can be used e.g. for User and System Behavior Analysis and
Threat Hunting. Here you can as well define own charts and patterns (as
SAP does it) and save them in a ‘Forensic Workspace’.</p>
<p>When starting up, it shows:</p>
<ul>
<li><p>Log data having arrived the last 15 minutes (can be changed to
any other time frame)</p></li>
<li><p>In the upper left pie chart: Log types having arrives in that
time frame</p></li>
<li><p>In the lower left pie chart: Semantic events which were contained
in the incoming log data</p></li>
<li><p>In the upper right pie chart: System IDs, from which data arrived
(as far as the log provides the information)</p></li>
</ul>
<p>The creation of charts, patterns, workspaces is part of additional
exercises.</p></td>
<td><img src="media/image31.png"
style="width:3.92153in;height:2.16875in" /></td>
</tr>
<tr class="odd">
<td><ol start="31" type="1">
<li><p>The basic navigation in the forensic lab is described
below.</p></li>
</ol>
<p>Click on the drop down box above any of the pie charts. You see all
the ~180 semantic attributes which are available ( see Knowledge Base)
and might be filled with values. Select e.g. ‘Service, Program Name’.
Then you see in the preview all the programs (in general SAP system
executable reports) which were called within the time frame, coming out
from different logs.</p>
<p>Click on any of the values in the list or within a pie chart (e.g. a
certain System ID, Actor), and in the context menu, click ‘Add to Path’.
The filter path gets a new filter subset, and all information is now
filtered according to this subset.</p>
<p>Click on another Attribute value (e.g. a certain semantic Event and
‘Add to Path’. Then you see two filter subsets, and all data is filtered
according to these two subsets.</p>
<p>You can jump between the different filter subset results by clicking
on the small pie chart at each subset.</p>
<p>You can edit the filter conditions by clicking on the small rectangle
upper right in each subset</p>
<p>You can create charts and patterns, look at normalized and original
data, use the logs in a ‘Case File’ (separate exercise later), by
clicking on the number under the subset, and opening a context
menu.</p></td>
<td><img src="media/image32.png"
style="width:3.92153in;height:5.08125in" /></td>
</tr>
<tr class="even">
<td><ol start="32" type="1">
<li><p>The forensic lab opens as an extra browser tab, you can close it
in the browser, and jump back to the launch pad browser tab.</p></li>
</ol></td>
<td><img src="media/image33.png"
style="width:3.92153in;height:0.33681in" /></td>
</tr>
<tr class="odd">
<td><ol start="33" type="1">
<li><p>Click on Tile ‘Resolve User Identity’</p></li>
</ol></td>
<td><img src="media/image34.png"
style="width:1.5168in;height:1.43346in" /></td>
</tr>
<tr class="even">
<td><ol start="34" type="1">
<li><p>In the UI you can enter a user Pseudonym, as you saw it e.g.
within Alert data, or in the forensic lab</p></li>
</ol>
<p>You can/should resolve a pseudonym, especially if a suspicious
activity was finally determined or acknowledged by the security
analyst.</p>
<p>If there is the need to do e.g. an ad’hoc analysis for a user, a
reverse resolution (UserID Pseudonym) can be done, and then even a jump
to the forensic lab can be done from within the reverse resolution,
prefiltered to the different roles (Acting, Targeted, …) of the user
id.</p>
<p>Information: A special Authorization/Role is needed to do the
resolution. A 4-eyes principle or special resolution policy can hence be
established.</p>
<p>(De-) Pseudonymization is part of another exercise.</p></td>
<td><img src="media/image35.png"
style="width:3.92153in;height:2.08611in" /></td>
</tr>
<tr class="odd">
<td><ol start="35" type="1">
<li><p>Jump back to launch pad by using the home button.</p></li>
</ol></td>
<td><img src="media/image13.png"
style="width:0.99175in;height:0.64172in" /></td>
</tr>
<tr class="even">
<td><ol start="36" type="1">
<li><p>Click on Tile ‘Security Notes’</p></li>
</ol></td>
<td><img src="media/image36.png"
style="width:1.45846in;height:1.36321in" /></td>
</tr>
<tr class="odd">
<td><ol start="37" type="1">
<li><p>If the corresponding meta data transfer is set up in the Source
SAP Application Server ABAP Systems, the UI provides an overview about
available and relevant security notes and the patch state of the systems
related to these notes.</p></li>
</ol>
<p>It shows if a note is relevant for a certain system (or not), By
Clicking on e.g. the CVSS Base Score Column, a sorting is possible, and
an overview can be provided related to the most important Security
notes. The filtering allows as well to find out if e.g. a certain note
is relevant for a certain system, etc.</p>
<p>This functionality as such can be as well provided by other tools
from SAP and partners, it is just a precondition for the ‘Patch Risk
Score’ shown in ‘System Monitoring’, together with a ‘Business Attack
Score’ and a ‘Business Risk Score’.</p></td>
<td><img src="media/image37.png"
style="width:3.92153in;height:1.13681in" /></td>
</tr>
<tr class="even">
<td><ol start="38" type="1">
<li><p>Jump back to launch pad by using the home button.</p></li>
</ol></td>
<td><img src="media/image13.png"
style="width:0.99175in;height:0.64172in" /></td>
</tr>
<tr class="odd">
<td><ol start="39" type="1">
<li><p>Click on Tile ‘System Monitoring’.</p></li>
</ol></td>
<td><img src="media/image38.png"
style="width:1.42512in;height:1.35845in" /></td>
</tr>
<tr class="even">
<td><ol start="40" type="1">
<li><p>The UI shows per different system roles (Production, Test, …) the
different scores:</p></li>
</ol>
<ul>
<li><p>Business Risk Score: System criticality as to the maintained
criticality in ‘System Administration’ about Confidentiality, Integrity
and Availability. It can be changed by changing/maintaining the values
in ‘System Administration’.</p></li>
<li><p>Business Attack Score: Aggregated Alert Score from Alerts related
to the system landscape, or to single systems, or to single systems and
clients. If there exist non-processed Alerts related to the system, with
a high Alert score, then the Business Attack Score is high.</p></li>
<li><p>Patch Risk Score: Based on the Patch State (See Tile ‘Security
Notes’), the criticality of the system and the criticality of relevant
notes which are not patched, a Patch Risk Score is calculated.</p></li>
</ul>
<p>In the 1<sup>st</sup> UI the Scores are shown in an aggregated way,
drill down is possible. The next level shows the same scores for a whole
system. The next drilldown level shows the Scores for a system and its
correlated clients. The next drilldown shows the detailed information,
why the scores are high low:</p>
<ul>
<li><p>List of top 20 open Alerts</p></li>
<li><p>List of top 20 missing security patches</p></li>
</ul>
<p>Navigation into each Alert is possible from there.</p></td>
<td><p><img src="media/image39.png"
style="width:3.92153in;height:0.48681in" /></p>
<p>Aggregated Landscape View</p>
<p><img src="media/image40.png"
style="width:3.92153in;height:1.03819in" /></p>
<p>Aggregated System ID View</p>
<p><img src="media/image41.png"
style="width:3.92153in;height:1.13333in" /></p>
<p>Aggregated System/Client View</p>
<p><img src="media/image42.png"
style="width:3.92153in;height:1.60486in" /></p>
<p>Detailed View for one System or System and client</p></td>
</tr>
<tr class="odd">
<td><ol start="41" type="1">
<li><p>Jump back to launch pad by using the home button.</p></li>
</ol></td>
<td><img src="media/image13.png"
style="width:0.99175in;height:0.64172in" /></td>
</tr>
<tr class="even">
<td><ol start="42" type="1">
<li><p>Click on Tile ‘Record of Actions’</p></li>
</ol></td>
<td><img src="media/image43.png"
style="width:1.43346in;height:1.40012in" /></td>
</tr>
<tr class="odd">
<td><ol start="43" type="1">
<li><p>In the UI you can see all actions either done automatically or by
Users using ETD.</p></li>
</ol>
<p>In the example a filtering took place about actions that happened
last day and that were triggered by user DEMO01. User DEMO01 resolved a
user pseudonym TMHY_28081 and looked up the user pseudonym for user
DEMO01.</p>
<p>In the filter it can be selected via very different Entity Types
about what happened in the ETD system.</p>
<p>The functionality is built in for compliance reasons, to get exact
information about who did what and to be able to find out this was
compliant/incompliant.</p>
<p>Information: The Record of Action Log is additionally used for ETD
self-monitoring. Patterns/Use cases that throw alerts are available,
e.g. in the case of critical changed to a pattern (e.g. deactivate
it)</p></td>
<td><img src="media/image44.png"
style="width:3.92153in;height:1.33403in" /></td>
</tr>
<tr class="even">
<td><ol start="44" type="1">
<li><p>Jump back to launch pad by using the home button.</p></li>
</ol></td>
<td><img src="media/image13.png"
style="width:0.99175in;height:0.64172in" /></td>
</tr>
<tr class="odd">
<td><ol start="45" type="1">
<li><p>Click on Tile ‘Settings’</p></li>
</ol></td>
<td><img src="media/image45.png"
style="width:1.42512in;height:1.40846in" /></td>
</tr>
<tr class="even">
<td><ol start="46" type="1">
<li><p>In the UI you can see the different possibilities for ETD
configuration.</p></li>
</ol>
<ul>
<li><p>Manage Storage: Here you can define the retention periods for Hot
Storage and Warm Storage. Information: To determine these values, SAP
provides a sizing guide.</p></li>
<li><p>Manage Alert Publishing: Here you can define an Alert
Forwarding/Pushing from ETD to any Rest Endpoint. You can define the
base URL to send to (credentials are created within the HANA platform),
the Alert format, a filter maintained in Menu item ‘Pattern Filter’,
whether the triggering events shall be added to the alert, and whether
the Alert status shall be set to ‘Forwarded’. Additionally, you can
define mail receivers to send the alerts via mail.</p></li>
<li><p>Pattern Filter: Here you can define different filters you can use
either to push out only certain alerts, or to hand over the filter ID
via the Alert retrieval API to get only the alerts related to the
patterns within the filter</p></li>
<li><p>Content Replication: If you use a 2-tier ETD landscape (one
pre-prod for Pattern creation and testing, one prod for running the
patterns and processing alerts. Then the objects (like Workspaces,
patterns, value lists, as well as e.g. maintained system meta data) can
be transported from the pre-prod system to the prod system. In this UI
you can define the transport directions for this data. The configuration
of the transport directions are done in a configuration file (described
in the SAP help documentation)</p></li>
<li><p>Time Zone: Here you can define whether the ETD users work always
in UTC timezone (makes sense if the ressourcces are distributed over the
world. So that they can easily discuss critical topics and speak about
the same time) or in local time zone (easier in case everyone works in
the same time zone)</p></li>
<li><p>Anomaly Detection: You can define whether you want to collect
data as well for currently inactive anomaly detection patterns. Reason:
If you set such a Pattern active at a later point in time´, it can
directly create alerts, instead of needing to start now collecting data
over e.g. 12 weeks with some waiting time if the 12 weeks more than the
retention time.</p></li>
<li><p>Custom Values: You can create own custom values for
investigations and workspaces. In the example screenshot further
investigation values are created to define a kind of a current
processing state by different security analyst levels</p></li>
<li><p>Workload Management: If queries start to be to memory exhausting,
the HANA DB slows down for other users to fulfill the current request
with all resources needed. In order to allow other to work, during such
a ‘heavy’ query is running, the workload management restricts the
resources to a maximum threshold for executing one query.</p></li>
<li><p>Pseudonymization: can be switched on and off, depending on the
Country specific, industry specific, company specific
regulations.</p></li>
</ul></td>
<td><p><img src="media/image46.png"
style="width:3.92153in;height:1.62361in" /></p>
<p>Retention Times</p>
<p><img src="media/image47.png"
style="width:3.92153in;height:1.71111in" /></p>
<p>Alert forwarding</p>
<p><img src="media/image48.png"
style="width:4.02277in;height:0.94109in" /></p>
<p>Pattern Filter</p>
<p><img src="media/image49.png"
style="width:3.92153in;height:1.70764in" /></p>
<p>Custom Values</p></td>
</tr>
<tr class="odd">
<td><ol start="47" type="1">
<li><p>Jump back to launch pad by using the home button.</p></li>
</ol></td>
<td><img src="media/image13.png"
style="width:0.99175in;height:0.64172in" /></td>
</tr>
</tbody>
</table>

## Summary

**Tool Aspect:** You learned how to navigate within SAP Enterprise
Threat Detection, and by that you went through the most relevant UIs and
functionalities, allowing you to understand, what it is made for, and
how things are correlated (e.g., information from knowledge base, and
what you see in alerts and in the forensic lab). Some of the tools are
further explored in detail in the following exercises.

# Security Expert - Working with the Forensic Lab 

**Security Aspect**: The Security Expert sometimes needs to do an ad-hoc
analysis about things that happen in the landscape, or he gets a hint
about certain suspicious behavior of an IP Address, within an SAP
System, of certain program calls etc.

He might need to create own charts to easier interpret the data and the
suspicious behavior within, and even he might need to create an own
detection patterns to get future alerts about the suspicious actions he
found during his analysis.

**Tool Aspect:** The forensic lab is one the most important application
in SAP Enterprise Threat Detection and helps you to gain insight about
what is going on at present in your system landscape.

Forensic lab supports workspaces for identifying and analyzing
weaknesses or attacks and supports the modelling of charts or attack
detection patterns. For attack detection patterns, you create the
configurations, which you want SAP Enterprise Threat Detection to use to
scan for events that match the pattern. No coding or complex regex/SQL
queries are needed, instead SAP Enterprise Threat Detection takes care
of transforming your attack detection pattern model to SAP HANA
optimized queries.

In this exercise you will learn how to work with the forensic lab, how
to analyze log events and how to create charts and attack detection
patterns.

## Filtering Data

In this exercise, you will display failed log on attempts, and you will
learn how filters can be created.

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="48" type="1">
<li><p>Open tile <strong>Forensic Lab</strong> in the SAP Enterprise
Threat Detection Launchpad.</p></li>
</ol></td>
<td><img src="media/image50.png"
style="width:3.9256in;height:1.2198in" /></td>
</tr>
<tr class="even">
<td rowspan="2"><ol start="49" type="1">
<li><p>The initial screen of the forensic lab shows the log events from
last 15 minutes. The left part of the workspace contains the filter
paths. The right part of the workspace is used to display the log
events. They are called browsing charts. You can e.g. see which log
types – <em>Event, Log Type</em> - are received, from which systems -
<em>System ID, Actor</em> - or which actions - <em>Event (Semantic)</em>
- have been performed. Change the drop-down value in one of the browsing
charts to see information about other semantic attributes.</p></li>
</ol></td>
<td rowspan="2"><img src="media/image51.png"
style="width:3.92153in;height:2.16875in" /></td>
</tr>
<tr class="odd">
</tr>
<tr class="even">
<td><ol start="50" type="1">
<li><p>Push button <em>Change time period.</em></p></li>
</ol>
<blockquote>
<p>Change time period selection to <em><strong>1 hour</strong></em> and
push button <em>OK</em> to analyze the log events from last day.</p>
<p>Look at the path and the browsing charts that have been updated.</p>
</blockquote></td>
<td><img src="media/image52.png"
style="width:3.92153in;height:2.16875in" /></td>
</tr>
<tr class="odd">
<td><ol start="51" type="1">
<li><p>To add a filter for failed logon events, click on legend <em>User
Logon, Failure.</em></p>
<p><strong>Hint:</strong> If there are no <em>User Logon, Failure</em> Events, please log out of ETD, and try to logon by explicitly using a wrong password for one time. Then a <em>User Logon, Failure</em> Event arrives. After that you can logon with the right password again</p></li>
</ol></td>
<td><img src="media/image53.png"
style="width:3.92153in;height:2.16875in" /></td>
</tr>
<tr class="even">
<td><ol start="52" type="1">
<li><p>Select menu item <em>Add to Path.</em> This will create a filter
for failed logons that have been occurred in the last day. It is shown
as <em>Subset</em> in the filter path.</p></li>
</ol></td>
<td><img src="media/image54.png"
style="width:1.14356in;height:0.88777in"
alt="C:\Users\D026896\AppData\Local\Temp\SNAGHTMLff779cc.PNG" /></td>
</tr>
<tr class="odd">
<td><ol start="53" type="1">
<li><p>Look at <em>Path1</em> and see the subset that has been added.
Observe that the browsing charts have been updated as well.</p></li>
</ol></td>
<td><img src="media/image55.png"
style="width:3.92153in;height:3.85556in" /></td>
</tr>
</tbody>
</table>

## 

## 

## Modelling Charts

Based on the subset you have created in the filter path, you can further
filter the log events, or you can create charts to see more details. In
this exercise you will create a chart of failed logon events including
information about systems and users.

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="54" type="1">
<li><p>Push button <img src="media/image56.png"
style="width:0.15278in;height:0.125in" /> right to the subset number.
This opens a drop-down menu with all available operations you can
perform on the subset. Select menu item <em>Create Chart</em></p></li>
</ol></td>
<td><img src="media/image57.png"
style="width:3.92153in;height:3.8625in" /></td>
</tr>
<tr class="even">
<td><ol start="55" type="1">
<li><p>Show the Chart:</p></li>
</ol>
<p>Click on the Chart Icon lower left. The Chart opens on the right part
of the UI</p></td>
<td><img src="media/image58.png"
style="width:2.01684in;height:1.22511in" /></td>
</tr>
<tr class="odd">
<td rowspan="2"><ol start="56" type="1">
<li><p>Change the chart name:</p></li>
</ol>
<blockquote>
<p><em>Click on the pencil symbol</em></p>
<p><em>In the Popup enter:</em></p>
<p><em>Failed Logon DEMO<strong>&lt;YOUR_USERNR&gt;</strong></em></p>
<p>Press o.k.</p>
</blockquote></td>
<td rowspan="2"><p><img src="media/image59.png"
style="width:3.30683in;height:0.64532in" /></p>
<p><img src="media/image60.png"
style="width:1.65387in;height:0.62383in" /></p></td>
</tr>
<tr class="even">
</tr>
<tr class="odd">
<td><ol start="57" type="1">
<li><p>Push button <img src="media/image61.png"
style="width:0.22222in;height:0.16667in" />. Add the following
description and push button <em>OK.</em></p></li>
</ol>
<blockquote>
<p>Description:</p>
<p><em>Failed Logon Events by Systems and Users</em></p>
</blockquote></td>
<td><img src="media/image62.png"
style="width:2.20792in;height:1.75242in"
alt="C:\Users\D026896\AppData\Local\Temp\SNAGHTML100168e3.PNG" /></td>
</tr>
<tr class="even">
<td><ol start="58" type="1">
<li><p>Click on link <em>Append group by field</em> and add field
<em>System ID, Actor.</em> The chart will be updated with the system
information on which failed logon attempts have been observed.</p></li>
</ol></td>
<td><img src="media/image63.png"
style="width:3.2825in;height:2.18248in" /></td>
</tr>
<tr class="odd">
<td><ol start="59" type="1">
<li><p>Click on link <em>Append group by field</em> and add field
<em>System Role, Actor.</em> The chart will be updated with additional
system role information.</p></li>
</ol></td>
<td><img src="media/image64.png"
style="width:3.31861in;height:2.20858in" /></td>
</tr>
<tr class="even">
<td><ol start="60" type="1">
<li><p>Click on link <em>Append group by field</em> and add field
<em>User Account Name Pseudonym, Target.</em> The chart will be updated
with additional user information.</p></li>
</ol></td>
<td><img src="media/image65.png"
style="width:3.59456in;height:2.43691in" /></td>
</tr>
<tr class="odd">
<td><ol start="61" type="1">
<li><p>You can now save your changes.</p></li>
</ol>
<blockquote>
<p>On the left lower area enable checkbox <em>Shared</em>. This allows
other users to access your charts.</p>
<p>Push button <em>Save</em>.</p>
</blockquote></td>
<td><img src="media/image66.png"
style="width:3.61175in;height:1.69166in" /></td>
</tr>
<tr class="even">
<td><ol start="62" type="1">
<li><p>Provide name and namespace for your workspace and push button
<em>OK.</em></p></li>
</ol>
<blockquote>
<p>Name:</p>
<p><em>My first workspace
DEMO<strong>&lt;YOUR_USERNR&gt;</strong></em></p>
<p>Namespace:</p>
<p><em>http://demo</em></p>
</blockquote></td>
<td><img src="media/image67.png"
style="width:2.41084in;height:1.78087in" /></td>
</tr>
</tbody>
</table>

## Browse through the data and model your own individual charts

In your newly created workspace, *my first workspace
DEMO\<YOUR_USERNR\>* you can add a new path by pushing the button
<img src="media/image68.png" style="width:0.53267in;height:0.15536in" />.
On the new path you can create new filters by adding new subsets either
via the browsing charts or by clicking on the link
<img src="media/image69.png" style="width:0.52122in;height:0.15443in" />.
AND operator
<img src="media/image70.png" style="width:0.21395in;height:0.14912in" />
between subsets can be toggled to an OR operator
<img src="media/image71.png" style="width:0.18507in;height:0.14925in" />.

Also have a close look on the *Subset Selection* options (Example):

<img src="media/image72.png" style="width:2.7419in;height:0.96675in" />

<img src="media/image73.png" style="width:3.49272in;height:2.06257in" />

You can filter specific fields (= *Field*) from semantic attributes
using a specific operator (=*Operators)* and providing corresponding
filter values (= *Value*)

You can use the option *Reference* to correlate Events from one path to
another path

You can use Value-List containing pre-defined values for filtering the
data

Make use of the following chart name for your own created charts:

**\<Chart name\>** *DEMO**\<YOUR_USERNR\>***

Save your changes. To retrieve the Workspace when opening a new Forensic
Lab UI, click on *‘Manage Workspaces’* and select your own one.

<img src="media/image74.png" style="width:5.72915in;height:3.1532in" />

## Working with Value Lists

Value List allows to simplify the filtering of events. Instead of adding
multiple values manually into the Subset Filter multiple times, you can
filter the data for multiple values more easily by using a value-list.

Patterns delivered by SAP Enterprise Threat Detection makes as well use
of value-lists. To tune the patterns in the way that the use case fits
to the customers environment, the value lists can be adjusted and
enhanced accordingly.

Open a new SAP ETD Launchpad tab in your browser and have a closer look
on tile *Value Lists:*

<img src="media/image75.png" style="width:6.92639in;height:1.36389in" />

In the *Value List* application, you can view existing ones that are
delivered with SAP Enterprise Threat Detection

The value lists delivered with SAP Enterprise Threat Detection have
pre-defined values, that can be adjusted and enhanced

You can also create your own value lists

## Modeling Attack Detection Patterns

The forensic lab supports the creation of attack detection patterns. The
procedure is similar to the procedure of creating charts. Attack
detection patterns are as well based on a particular subset of log
events. Now you will create a pattern that will deliver an alert when
SAP Standard users execute critical function modules in critical
systems.

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="63" type="1">
<li><p>Push button <em>Create</em> and then ‘New’ to create a new
workspace.</p></li>
</ol></td>
<td><img src="media/image76.png"
style="width:3.92153in;height:0.99097in" /></td>
</tr>
<tr class="even">
<td><ol start="64" type="1">
<li><p>In the Chart for ‘Event (Semantic) Search for Event
<em>Executable, RFC enabled Function Module, Run</em>, and by clicking
on the Event, select <em>Add to Path</em>.</p></li>
</ol>
<blockquote>
<p>As result, your filter path now has a filter on this event</p>
</blockquote></td>
<td><p><img src="media/image77.png"
style="width:3.92153in;height:1.34792in"
alt="C:\Users\D026896\AppData\Local\Temp\SNAGHTML27c2fc11.PNG" /></p>
<p><img src="media/image78.png"
style="width:1.49799in;height:2.01576in" /></p></td>
</tr>
<tr class="odd">
<td><ol start="65" type="1">
<li><p>By clicking <em>Add new subset</em> in the path, you can add
value lists to the path.</p></li>
</ol>
<blockquote>
<p>To filter on the value list with critical function modules
(pre-delivered by SAP), in the popup select:</p>
</blockquote>
<ul>
<li><p>Field: <em>Service, Function Name</em></p></li>
<li><p>Operator: <em>IN VALUE LIST</em></p></li>
<li><p>Value: <em>ABAPBlocklistedFunctionModules</em></p></li>
</ul>
<blockquote>
<p>Then press <em>OK</em></p>
<p><em>As a result, another subset was added to the filter
path.</em></p>
</blockquote></td>
<td><p><img src="media/image79.png"
style="width:1.45139in;height:0.36386in"
alt="C:\Users\D026896\AppData\Local\Temp\SNAGHTML27cb3e72.PNG" /></p>
<p><img src="media/image80.png"
style="width:3.19384in;height:2.26007in" /></p></td>
</tr>
<tr class="even">
<td><ol start="66" type="1">
<li><p>Now, additionally add the following filter paths, as shown above,
to further select on critical systems, and on SAP Standard
Users:</p></li>
</ol>
<blockquote>
<p>Subset 3:</p>
<p>Field: <em>System ID, Actor</em></p>
<p>Operator: <em>IN VALUE LIST</em></p>
<p>Value: <em>DemoCriticalSystems</em></p>
<p>Subset 4:</p>
<p>Field: <em>User Account Name Pseudonym, Actor</em></p>
<p>Operator: <em>IN VALUE LIST</em></p>
<p>Value: <em>SAPStandardUsers</em></p>
<p>As a result, subsets 3 and 4 should have been added to the filter
path.</p>
</blockquote></td>
<td><img src="media/image81.png"
style="width:2.85381in;height:8.24897in" /></td>
</tr>
<tr class="odd">
<td><ol start="67" type="1">
<li><p>Save the Workspace</p></li>
</ol></td>
<td><img src="media/image82.png"
style="width:3.23293in;height:2.26425in" /></td>
</tr>
<tr class="even">
<td><ol start="68" type="1">
<li><p>Now create a Pattern that creates an Alert if the filter in
subset 4 is not zero.</p></li>
</ol>
<blockquote>
<p>Click on the small triangle within subset 4 and then in the popup
click on <em>Create Pattern</em></p>
</blockquote></td>
<td><img src="media/image83.png"
style="width:2.03375in;height:1.62033in" /></td>
</tr>
<tr class="odd">
<td><ol start="69" type="1">
<li><p>On the right side of the screen you can now model the
Pattern:</p></li>
</ol>
<blockquote>
<p>Name: <em>CriticalFunctionModuleCalls&lt;DEMO_UserNO&gt;</em></p>
<p>Timeframe: <em>Last 30 Minutes</em></p>
<p>Status: <em>Active</em></p>
<p>Execution Output: <em>Alert</em></p>
</blockquote></td>
<td><img src="media/image84.png"
style="width:3.92153in;height:1.44653in" /></td>
</tr>
<tr class="even">
<td><ol start="70" type="1">
<li><p>To show data in the future Alerts, field grouping is needed.
Exactly the grouped fields are each per grouping raising an Alert and
exactly the grouped fields are shown in the upcoming Alerts.</p></li>
</ol>
<blockquote>
<p>Press <em>Append group by field</em> and select the following fields
to be grouped on:</p>
</blockquote>
<ul>
<li><p><em>System ID, Actor</em></p></li>
<li><p><em>Service, Function Name</em></p></li>
<li><p><em>User Account Name Pseudonym, Actor</em></p></li>
</ul></td>
<td><p><img src="media/image85.png" style="width:2.64583in;height:0.5in"
alt="C:\Users\D026896\AppData\Local\Temp\SNAGHTML27f8621c.PNG" /></p>
<p><img src="media/image86.png"
style="width:2.14557in;height:1.32275in" /></p></td>
</tr>
<tr class="odd">
<td><ol start="71" type="1">
<li><p>Do further settings within the Pattern:</p></li>
</ol>
<blockquote>
<p>Execution: <em>Scheduled</em></p>
<p>Runs Every (min): <em>2</em></p>
<p>Alert Severity: <em>High</em></p>
<p>Credibility of the Attack:</p>
<p>Confidentiality: <em>Proven</em></p>
<p>System Integrity: <em>Suspected</em></p>
<p>Data Integrity: <em>Suspected</em></p>
<p>Success of Attack</p>
<p>Confidentiality: <em>Successful</em></p>
<p>System Integrity: <em>Undetermined</em></p>
<p>Data Integrity: <em>Undetermined</em></p>
<p><strong>Important</strong>: Set the Pattern to value
<em><strong>Shared</strong></em></p>
<p><strong>Finally Save again</strong></p>
<p><strong>Notes</strong>: the scheduled execution of each 2 minutes is
for demo purposes only, so that alerts are raised when waiting. The
scheduled execution times to select are dependent on:</p>
</blockquote>
<ul>
<li><p>Criticality of the Alert. The more critical the smaller the
execution intervals</p></li>
<li><p>Numbers of aggregated log events to be considered in a certain
time interval, to raise the Alert, if the threshold is bigger than one.
<strong>Example</strong>: More than 3 failed logons per user and system
within a timeframe of 5 Minutes or 30 Minutes or 2 hours or one week are
considered to be alerted?</p></li>
<li><p>The Time frame selected for the whole workspace.
<strong>Example</strong>: A selected time frame of last week aggregates
the data of one week, but an execution of the pattern each 2 minutes
might sometimes still make sense, but very often the selected values do
not fit. Mostly the time frames of workspace time interval and
Pattern-execution time interval should be similar, with some overlap. A
typical value would be the execution of a Pattern each 10 minutes and
the time interval of a Workspace of last 15 minutes.</p></li>
</ul></td>
<td><p><img src="media/image87.png"
style="width:1.25689in;height:3.67111in" /></p>
<p><img src="media/image88.png"
style="width:1.87477in;height:1.14569in" /></p></td>
</tr>
<tr class="even">
<td><ol start="72" type="1">
<li><p>Check corresponding Alerts in he Alerts-Tile in the starting Page
of ETD. After while (if the Filter Path in the workspace shows numbers
bigger than zero).</p></li>
</ol>
<blockquote>
<p>Find the Alerts for your Pattern in the Alert list and see the detail
information that corresponds to the grouping in the modeled Pattern.</p>
<p>Click on the Alert ID and see the details within the Alert.</p>
<p><strong>Note</strong>: Alert and Investigation handling will be
handled in a later chapter</p>
</blockquote></td>
<td><p><img src="media/image89.png"
style="width:0.71528in;height:0.67951in"
alt="C:\Users\D026896\AppData\Local\Temp\SNAGHTML2cc12897.PNG" /></p>
<p><img src="media/image90.png" style="width:3.92153in;height:0.21181in"
alt="C:\Users\D026896\AppData\Local\Temp\SNAGHTML2d4450c3.PNG" /></p>
<p><img src="media/image91.png"
style="width:4.2734in;height:2.02281in" /></p></td>
</tr>
</tbody>
</table>

## Summary

**Security Aspect:** As a Security Expert you are now able to do
forensic analysis and find suspicious behaviors and evidences in big
amounts of data. Now you can visualize this data as to your needs and
create own Attack Detection Patterns in case you need to get Alerts on
future occurrences of this situation.

**Tool Aspect:** You learned how to use the Forensic Lab to look into
data, create Charts and Patterns and how to save them and to make them
available to others.

**Note**: The example pattern you modelled is already part of the
standard content delivery of ETD

# ProcessING alerts and investigations

**Security Aspect:** As a Security Analyst in Level 1, 2 or 3 one of
your main tasks is to check for raised Alerts and to process them. You
need to answer questions like

- Was this a real Alert or a false positive?

- What are evidences which need to be collected to proof the attack or
  misuse?

- Are there additional Alerts related to this Alert?

Then you may need to collect the evidences and to follow a Standard
Operation Procedure for the further actions.

**Tool Aspect:** SAP Enterprise Threat Detection raises alerts as
notification for potential attacks as they are happening. An alert
includes references to the log events and the attack detection patterns
or the anomaly detection patterns that led to its creation. Alerts are
processed and analyzed by making use of various applications provided by
SAP Enterprise Threat Detection. After your analysis of an alert, you
can mark it as an attack, or a suspected attack and you can add it to an
investigation. Investigations are collections of related material such
as alerts, related events, case files, and snapshots. They are the
central item with which more than one person might work with (e.g.
monitoring agents and/or security experts).

## Viewing Alerts

As the monitoring agent of a company, you need to monitor the alerts and
react immediately. In the case of a suspected attack, it is usually the
user or the hostname behind it or the system affected that you need to
identify.

In this exercise you will learn how alerts are viewed and how an
investigation is started in case of a suspected attack.

<table>
<colgroup>
<col style="width: 42%" />
<col style="width: 57%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="73" type="1">
<li><p>Open tile <em>Open Alerts – Very High Last Day,</em> or as well
click on the <em>Alerts</em> Tile, if no severity ‘very high’ alerts are
available<em>.</em></p></li>
</ol></td>
<td><img src="media/image92.png"
style="width:3.61771in;height:1.43201in" /></td>
</tr>
<tr class="even">
<td rowspan="2"><ol start="74" type="1">
<li><p>Open Filter Bar. Add the pattern you have created until step 71
as filter and push button <em>GO.</em></p></li>
</ol>
<blockquote>
<p><em>CriticalFunctionModuleCalls&lt;DEMO_UserNO&gt;</em></p>
<p><em>Comment:</em></p>
<p><em>This is only needed for this exercise due to having multiple
users working on the same exercise. In generals the Alerts List User
Interface is used as a worklist for alerts by the monitoring
agent.</em></p>
</blockquote></td>
<td rowspan="2"><img src="media/image93.png"
style="width:3.5976in;height:0.53in" /></td>
</tr>
<tr class="odd">
</tr>
<tr class="even">
<td><ol start="75" type="1">
<li><p>Look at the alert that has been raised.</p></li>
</ol>
<blockquote>
<p>The severity of the alert provides the firsts indication how to
prioritize the worklist of a monitoring agent.</p>
<p>Under column ‘Trigger’ you can see the system on which a critical
function module was executed.</p>
</blockquote></td>
<td><img src="media/image94.png"
style="width:3.83392in;height:1.00009in" /></td>
</tr>
<tr class="odd">
<td><ol start="76" type="1">
<li><p>Push button <em>View Threat Situation</em> and see e.g. the
<em>Network Hostname Initiator</em> that has been used for downloading
data.</p></li>
</ol></td>
<td><p><img src="media/image95.png"
style="width:3.82292in;height:0.44097in" /></p>
<p><img src="media/image96.png"
style="width:2.72134in;height:1.9126in" /></p></td>
</tr>
<tr class="even">
<td><ol start="77" type="1">
<li><p>Switch back to the <em>Alerts List View</em> and click on alert
<em>ID</em> to see more details about the alerts</p></li>
</ol></td>
<td><img src="media/image97.png"
style="width:4.41389in;height:0.55694in" /></td>
</tr>
<tr class="odd">
<td><ol start="78" type="1">
<li><p>Look at the header Information of the alerts. It shows basic data
about the alert such as the pattern it was created by or by which
metrics the alert has been triggered. Use the links to see the details
of the alert.</p></li>
</ol></td>
<td><img src="media/image98.png"
style="width:3.82292in;height:2.15278in" /></td>
</tr>
<tr class="even">
<td><ol start="79" type="1">
<li><p>Click on the <em>Triggering Events</em> to see more
details.</p></li>
</ol></td>
<td><img src="media/image99.png"
style="width:3.21356in;height:1.82948in" /></td>
</tr>
<tr class="odd">
<td><ol start="80" type="1">
<li><p>See the details of the events that has led to the alert creation
e.g. the system where a suspicious activity has been detected or the
transaction in which the download was executed.</p></li>
</ol></td>
<td><img src="media/image100.png"
style="width:3.72868in;height:1.96086in" /></td>
</tr>
<tr class="even">
<td><ol start="81" type="1">
<li><p>Click on button <em>Back</em> to return to the alert details
view.</p></li>
</ol></td>
<td><img src="media/image101.png"
style="width:1.0832in;height:0.78115in" /></td>
</tr>
<tr class="odd">
<td><ol start="82" type="1">
<li><p>Click on <em>System ID</em> to see the details of the affected
system.</p></li>
</ol></td>
<td><img src="media/image102.png"
style="width:3.74455in;height:0.54349in" /></td>
</tr>
<tr class="even">
<td><ol start="83" type="1">
<li><p>Look at the details of the affected system.</p></li>
</ol></td>
<td><img src="media/image103.png"
style="width:3.82292in;height:1.03056in" /></td>
</tr>
<tr class="odd">
<td><ol start="84" type="1">
<li><p>Under tab <em>Connected Systems</em> you can see that the
affected system has done a remote communication.</p></li>
</ol></td>
<td><img src="media/image104.png"
style="width:3.59405in;height:1.84827in" /></td>
</tr>
<tr class="even">
<td><ol start="85" type="1">
<li><p>Open a new browser tab and open SAP Enterprise Threat Detect
Launchpad. Open tile <em>Systems</em> to see the details of the system
to which a remote communication has taken place.</p></li>
</ol></td>
<td><img src="media/image105.png"
style="width:3.82292in;height:0.7875in" /></td>
</tr>
<tr class="odd">
<td><ol start="86" type="1">
<li><p>Enter the System ID in the search field an select the system to
see the details. <em>(Hint: if there are too many systems in the ETD
system, the filter only works for the shown Systems in the list. In case
the system S4H/100 is not found, please page down until it is
shown)</em></p></li>
</ol></td>
<td><img src="media/image106.png"
style="width:3.82292in;height:0.82014in" /></td>
</tr>
</tbody>
</table>

## 

## Investigating Alerts

Investigations are collections of related material such as alerts, case
files, and snapshots. They are the central item with which the
monitoring agents and/or the security expert starts his forensic
research, as they can lead to an incident.

When the monitoring agent considers an alert suspicious, an
investigation gets started. The investigation gets a description, a
severity, a status and comments can be added. The investigation can be
shared easily, either in emails or as tiles in the launchpad, or even as
a PDF file. More alerts and other related material can be added later,
and the status can be changed in order to make tracking of the
investigation easy. It is also possible to create a CSV file with a list
of all triggering or related events of the alerts in the investigation.

As the investigation is an item that more than one person might work
with, there is a discussion and timeline tab in which manual comments as
well as changes to the investigation are tracked.

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="87" type="1">
<li><p>In the Alerts worklist view, select the alert and push button
<em>Start Investigation.</em> Choose <em>Start From Template</em> 
<em>Information Disclosure</em></p></li>
</ol>
<blockquote>
<p><strong><mark><u>INFORMATION:</u></mark></strong></p>
<p>The Investigation Popup should be prefilled from the template, but as
to a software bug, this automated filling does not happen.</p>
<p>By that please fill in:</p>
</blockquote>
<ul>
<li><p>Description: Download sensitive information</p></li>
<li><p>Severity: Very High</p></li>
<li><p>Status: In Process</p></li>
<li><p>Attack: Suspected</p></li>
<li><p>Management Visibility: Level 1 Security Operations</p></li>
<li><p>Comment: &lt;Any comment you want&gt;</p></li>
</ul></td>
<td><img src="media/image107.png"
style="width:2.64736in;height:1.24788in" /></td>
</tr>
<tr class="even">
<td><ol start="88" type="1">
<li><p>Set yourself as processor of the investigation, set the Status to
In Process and check the instructions how to handle this type of alert.
Push button <em>Add and Show Investigation.</em></p></li>
</ol></td>
<td><img src="media/image108.png"
style="width:1.797in;height:1.80465in" /></td>
</tr>
<tr class="odd">
<td><ol start="89" type="1">
<li><p>Click on tab <em>Alerts</em> and click on alert <em>ID</em> to
further investigate details of the alert.</p></li>
</ol></td>
<td><img src="media/image109.png"
style="width:3.20802in;height:1.00137in" /></td>
</tr>
<tr class="even">
<td><ol start="90" type="1">
<li><p>Click on related events to gain more insight about the potential
threat.</p></li>
</ol></td>
<td><img src="media/image110.png"
style="width:3.38954in;height:1.29107in" /></td>
</tr>
<tr class="odd">
<td><ol start="91" type="1">
<li><p>Select the event row to see more details. Add to your
investigation if relevant.</p></li>
</ol></td>
<td><img src="media/image111.png"
style="width:3.85504in;height:1.96404in" /></td>
</tr>
<tr class="even">
<td><ol start="92" type="1">
<li><p>Update Investigations with your current investigation analysis
results. E.g. use the tab discussions and add comments or screenshots to
affected system details, size of downloaded data, hostname or user
information. Screenshots can be added via Drag &amp; Drop. <em>(In the
picture on the right you see a screenshot which is pasted into the
comment field)</em></p></li>
</ol></td>
<td><img src="media/image112.png"
style="width:3.01782in;height:1.42629in" /></td>
</tr>
<tr class="odd">
<td><ol start="93" type="1">
<li><p>Make use of Alert Clusters to visualize alerts based on the
users, hostnames, systems or patterns involved. Open a new browser tab
and start SAP Enterprise Threat Detection Launchpad. Open tile
<em>Fields of Attention – Alert Clusters.</em></p></li>
</ol></td>
<td><img src="media/image113.png"
style="width:2.895in;height:2.12434in" /></td>
</tr>
<tr class="even">
<td><ol start="94" type="1">
<li><p>Choose button <em>Settings.</em></p></li>
</ol></td>
<td><img src="media/image114.png"
style="width:3.53983in;height:0.67667in" /></td>
</tr>
<tr class="odd">
<td><ol start="95" type="1">
<li><p>Change Graph Settings as follows:</p></li>
</ol>
<blockquote>
<p>Time range:<br />
<em>1 Hour</em></p>
<p>Focus of attention:<br />
<em>Hostname</em></p>
<p>Entity of attention:</p>
<p><em>System ID. Actor</em></p>
<p><em>System ID, Target</em></p>
<p><em>Account Name Pseudonym, Acting</em></p>
<p><em>Account Name Pseudonym, Targeted</em></p>
<p>Push button <em>OK.</em></p>
</blockquote></td>
<td><img src="media/image115.png"
style="width:1.76357in;height:2.80379in" /></td>
</tr>
<tr class="even">
<td><ol start="96" type="1">
<li><p>Push button <em>Filter</em> and only enable the hostname that has
triggered the alerts.</p></li>
</ol></td>
<td><img src="media/image116.png"
style="width:1.8251in;height:1.41563in" /></td>
</tr>
<tr class="odd">
<td><ol start="97" type="1">
<li><p>Look at the alert graph focusing on the selected hostname and see
how it is connected to patterns, alerts and systems. Click on the
hostname node to see further details.</p></li>
</ol></td>
<td><img src="media/image117.png"
style="width:2.50897in;height:1.92949in" /></td>
</tr>
<tr class="even">
<td><ol start="98" type="1">
<li><p>Look at the alerts and events shown on the timeline where this
hostname was involved.</p></li>
</ol></td>
<td><img src="media/image118.png"
style="width:3.35293in;height:1.68649in" /></td>
</tr>
<tr class="odd">
<td><ol start="99" type="1">
<li><p>You can slide and/or stretch the view to better visualize the
events on the timeline. Start your analysis from left to right to get an
understanding what has been done by the given hostname until the alerts
have been raised.</p></li>
</ol></td>
<td><img src="media/image119.png"
style="width:3.92291in;height:1.8732in" /></td>
</tr>
<tr class="even">
<td><ol start="100" type="1">
<li><p>Click on the circle to see the event details.</p></li>
</ol></td>
<td><img src="media/image120.png"
style="width:2.87571in;height:3.0784in" /></td>
</tr>
<tr class="odd">
<td><ol start="101" type="1">
<li><p>Push button <em>Add to Case File</em> <img
src="media/image121.png" style="width:0.28566in;height:0.22852in" /> to
add all relevant events that are related to the alert creation.</p></li>
</ol></td>
<td><img src="media/image122.png"
style="width:3.03824in;height:1.57744in" /></td>
</tr>
<tr class="even">
<td><ol start="102" type="1">
<li><p>Save your case file by pushing the button Save. Provide name and
namespace as follows and push button <em>OK.</em></p></li>
</ol>
<blockquote>
<p>Name:</p>
<p>Download path <em>DEMO&lt;YOUR_USERNR&gt;</em></p>
<p>Namespace:</p>
<p><a href="http://demo"><em>http://demo</em></a></p>
</blockquote></td>
<td><img src="media/image123.png"
style="width:2.93327in;height:1.76245in" /></td>
</tr>
<tr class="odd">
<td><ol start="103" type="1">
<li><p>Push button <em>Add to Investigation.</em></p></li>
</ol></td>
<td><img src="media/image124.png"
style="width:1.79767in;height:0.59922in" /></td>
</tr>
<tr class="even">
<td><ol start="104" type="1">
<li><p>Select your investigation and push button <em>Add and Show
Investigation.</em></p></li>
</ol></td>
<td><img src="media/image125.png"
style="width:3.52764in;height:0.69154in" /></td>
</tr>
<tr class="odd">
<td><ol start="105" type="1">
<li><p>Update the investigation Discussion with your analysis
results.</p></li>
</ol></td>
<td><img src="media/image126.png"
style="width:3.24461in;height:1.58402in" /></td>
</tr>
<tr class="even">
<td><ol start="106" type="1">
<li><p>Open forensic lab and change time range to last 2 hours. Analyze
the log events and see if you can find further events related to the
remote system and the SAP Standard user that has been mis-used.</p></li>
</ol></td>
<td><img src="media/image127.png"
style="width:2.89332in;height:1.43872in" /></td>
</tr>
<tr class="odd">
<td><ol start="107" type="1">
<li><p>Create the following filters:</p></li>
</ol>
<blockquote>
<p>System ID, Actor = <em>S4H/100</em></p>
<p>User Account Name Pseudonym, Acting = <em>SAP*</em></p>
</blockquote></td>
<td><img src="media/image128.png"
style="width:1.24326in;height:1.88295in" /></td>
</tr>
<tr class="even">
<td><ol start="108" type="1">
<li><p>Look at the browsing chart for <em>Event (Semantic)</em> and see
the event <em>Data, Monitored Data, Access.</em></p></li>
</ol></td>
<td><img src="media/image129.png"
style="width:3.80369in;height:2.64109in" /></td>
</tr>
<tr class="odd">
<td><ol start="109" type="1">
<li><p>Add a filter for this event.</p></li>
</ol></td>
<td><img src="media/image130.png"
style="width:1.00364in;height:2.61423in" /></td>
</tr>
<tr class="even">
<td><ol start="110" type="1">
<li><p>Create a chart with the following <em>Group By</em>
fields:</p></li>
</ol>
<blockquote>
<p><em>Event (Semantic)</em></p>
<p><em>System ID, Actor</em></p>
<p><em>User Account Pseudonym, Actor</em></p>
<p><em>Service, Function Name</em></p>
<p><em>Parameter Value, String</em></p>
<p><em>Generic, Outcome</em></p>
</blockquote></td>
<td><img src="media/image131.png"
style="width:3.70293in;height:1.98163in" /></td>
</tr>
<tr class="odd">
<td><ol start="111" type="1">
<li><p>Provide the following chart name.</p></li>
</ol>
<blockquote>
<p>Chart name:</p>
<p><em>Data Access DEMO&lt;YOUR_USERNR&gt;</em></p>
<p>Enable checkbox <em>Shared</em> and push button <em>Save</em>.
Provide the following workspace name.</p>
<p>Name:</p>
<p><em>Unsuccessful Data Access DEMO&lt;YOUR_USERNR&gt;</em></p>
<p>Namespace:</p>
<p><em>http://demo</em></p>
</blockquote></td>
<td><img src="media/image132.png"
style="width:3.18593in;height:2.87676in" /></td>
</tr>
<tr class="even">
<td><ol start="112" type="1">
<li><p>Push button <em>Add chart to snapshot page.</em></p></li>
</ol></td>
<td><img src="media/image133.png"
style="width:3.92153in;height:0.70694in" /></td>
</tr>
<tr class="odd">
<td><ol start="113" type="1">
<li><p>Push button <em>Create a new snapshot page.</em> Provide the
following snapshot page name and push button <em>Add and
Show.</em></p></li>
</ol>
<blockquote>
<p>Snapshot page name:</p>
<p><em>Data Access DEMO&lt;YOUR_USERNR&gt;</em></p>
</blockquote></td>
<td><p><img src="media/image134.png"
style="width:3.92153in;height:1.99861in" /></p>
<p><img src="media/image135.png"
style="width:2.83358in;height:0.4167in" /></p></td>
</tr>
<tr class="even">
<td><ol start="114" type="1">
<li><p>Push button <em>Add snapshot page to investigation.</em></p></li>
</ol></td>
<td><img src="media/image136.png"
style="width:2.96953in;height:3.03789in" /></td>
</tr>
<tr class="odd">
<td><ol start="115" type="1">
<li><p>Select your investigation and push button <em>Add and Show
Investigation.</em></p></li>
</ol></td>
<td><img src="media/image137.png"
style="width:2.96022in;height:1.02089in" /></td>
</tr>
<tr class="even">
<td><ol start="116" type="1">
<li><p>You find the Snapshot in the <em>Objects-</em>Tab of the
Investigation</p></li>
</ol>
<blockquote>
<p>Edit and update the investigation with your findings and close
it.</p>
</blockquote></td>
<td><img src="media/image138.png"
style="width:3.09731in;height:1.7058in" /></td>
</tr>
</tbody>
</table>

## Saving Evidence for Attacks

## 

Print an investigation or save it to a PDF file. Such a PDF file can,
for example, be used to attach an investigation to an external ticketing
system.

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="117" type="1">
<li><p>Within an investigation details push button <em>Print.</em> Push
<em>Save</em> to save the content of an investigation as PDF
file.</p></li>
</ol>
<blockquote>
<p>This investigation can now be handed over to the Incident Management
Team for further processing such as contacting the person behind the
user pseudonym and contact system owner of production system to disable
SAP Standard user SAP*.</p>
</blockquote></td>
<td><img src="media/image139.png"
style="width:2.7919in;height:1.64896in" /></td>
</tr>
</tbody>
</table>

## Summary

**Security Aspect:** As a Security Analyst you should be able to save
the collected evidences to an investigation. You know now how to analyze
the alert to avoid the false positives with several tools provided by
ETD, and print the investigation in PFD format as a hard copy.

**Tool Aspect:** You learned how to view the Alerts, create an
Investigation and assign alerts to it. You can find the User behind this
alert using Threat Situation. You also know how to view the details of
an Alert with its triggering Events, as well as add different objects to
an investigation. You’ve got to know the advanced tools, such as Case
Files.

# Pseudonymization of User Data

**Security Aspect:** The users involved in a potential cyberattack are
always the most interesting attributes for a Security Analyst. However,
all the person-related data must be protected before the collected
evidences indicating a real attack. SAP Enterprise Threat Detection
replaces the real user ID with User Pseudonym so that no user can be
identified during all phases of analysis. Only with very restrictive
access right the User Pseudonym can be resolved to real user.

**Tool Aspect:** You will learn how to resolve the User Pseudonym.

Pseudonymization is a procedure by which the user ID and other
person-related data in a record is replaced by a pseudonym, so as to
make it difficult or impossible to identify the person in question. In
contrast to the anonymization procedure, pseudonymized data still
references the original data.

SAP Enterprise Threat Detection frequently changes the pseudonym
associated with a user. The applications of SAP Enterprise Threat
Detection, such as the forensic lab, can only access the current
pseudonym of a user. You cannot use your past knowledge of user
pseudonyms to pursue a user. SAP Enterprise Threat Detection protects
this application with authorizations and records read-access to this
data.

## Determining the True Identity of Users

When suspicious events occur, you may be required to determine the true
identity of the person behind the alias shown in the user interface.
User Pseudonym can be resolved by authorized group of users only.

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="118" type="1">
<li><p>Logon to SAP Enterprise Threat Detection Launchpad with the
following user and open tile <em>Resolve User Identity</em></p></li>
</ol>
<blockquote>
<p>User: DEMO<em>&lt;YOUR_USERNR&gt;</em></p>
<p>Password: Welcome0</p>
</blockquote></td>
<td><img src="media/image140.png"
style="width:1.62078in;height:1.55508in" /></td>
</tr>
<tr class="even">
<td rowspan="2"><ol start="119" type="1">
<li><p>Enter (a) user pseudonym and push button <em>OK. A</em> clear
user name is then shown below</p></li>
</ol>
<blockquote>
<p><strong>Hint</strong>: You can e.g. find a user pseudonym in the
alerts that were raised, or in Forensic Lab you can select one within a
predefined visualization by e.g. viewing <em>User Account Name
Pseudonym, Actor</em></p>
<p><img src="media/image141.png"
style="width:1.53328in;height:1.09081in" /></p>
</blockquote></td>
<td rowspan="2"><img src="media/image142.png"
style="width:3.7727in;height:1.88468in" /></td>
</tr>
<tr class="odd">
</tr>
<tr class="even">
<td><ol start="120" type="1">
<li><p>Additionally, you can calculate the corresponding, system
dependent user accounts by clicking on the corresponding button
<em>Calculate Related Amounts</em>.</p></li>
</ol></td>
<td><img src="media/image143.png"
style="width:3.92153in;height:0.36667in" /></td>
</tr>
<tr class="odd">
<td><ol start="121" type="1">
<li><p>When clicking onto the line(s) in the list, you can view the meta
data coming from different systems.</p></li>
</ol></td>
<td><img src="media/image144.png"
style="width:1.46506in;height:1.45443in" /></td>
</tr>
<tr class="even">
<td><ol start="122" type="1">
<li><p>Additionally, there is the possibility to do a reverse resolution
from a clear user name to the actual pseudonym.</p></li>
</ol></td>
<td><img src="media/image145.png"
style="width:3.74623in;height:1.28567in" /></td>
</tr>
<tr class="odd">
<td><ol start="123" type="1">
<li><p>By clicking on Button <em>Process in Forensic Lab</em> you can
directly filter on that user and check what the user did in different
roles, e.g. as Actor, or as Target.</p></li>
</ol></td>
<td><img src="media/image146.png"
style="width:2.78801in;height:2.11409in" /></td>
</tr>
<tr class="even">
<td><ol start="124" type="1">
<li><p>The result in the Forensic Lab looks like that.</p></li>
</ol></td>
<td><img src="media/image147.png"
style="width:3.65686in;height:1.98288in" /></td>
</tr>
</tbody>
</table>

## Logging Access to User Identities

Personal user information is protected by local laws and regulations,
SAP Enterprise Threat Detection logs when someone accesses this
information.

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="125" type="1">
<li><p>Click on tab <em>Log</em> and see the audit log for user
resolutions</p></li>
</ol>
<blockquote>
<p>Hint: The same information plus furthermore about who was doing what
within ETD is found in Tile <em>Record of Actions</em></p>
</blockquote></td>
<td><p><img src="media/image148.png"
style="width:3.76915in;height:1.08195in" /></p>
<p><img src="media/image149.png"
style="width:3.92153in;height:0.71667in" /></p></td>
</tr>
</tbody>
</table>

## Summary

**Security Aspect:** As a User of a special authorized group you can
find the real user behind a User Pseudonym.

**Tool Aspect:** You learned how to resolve a User with “Resolve User
Identity”

# Monitoring DashboardS

**Security Aspect**: During the daily operation of security monitoring a
Security Agent needs to have an overview of the whole landscape. In ETD
they include active alerts, the status of investigations and the log
events. Since every agent has his own interested aspect, the content of
the monitor must be able to be configured individually. In addition to
the security related data he needs also an overview regarding the
connected systems, to avoid unnecessary loss or delay of events.

**Tool Aspect**: Monitoring dashboards provide an overview of the
events, alerts, and investigations in the system. The monitoring user
interface is visualized for all users of SAP Enterprise Threat
Detection. You can adjust the refresh rate, the number of charts and
patterns displayed, and the time span monitored by the indicators of the
Monitoring application. Monitoring dashboards can be customized the way
you need.

It is possible to define favorite monitoring dashboards by each
individual user.

## Viewing Default Monitoring Dashboard

When opening the monitoring tile, a default monitoring dashboard is
displayed. The default monitoring dashboard is typically used as a video
wall.

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="126" type="1">
<li><p>Open tile <strong>Monitoring</strong> in the SAP Enterprise
Threat Detection Launchpad.</p></li>
</ol></td>
<td><img src="media/image150.png"
style="width:3.1502in;height:1.04726in" /></td>
</tr>
<tr class="even">
<td rowspan="2"><ol start="127" type="1">
<li><p>The initial screen shows the default monitoring dashboard with
standard charts such as Events by Time, Events by System or Alerts by
Severity. The default monitoring dashboard is typically used as a video
wall.</p></li>
</ol></td>
<td rowspan="2"><img src="media/image151.png"
style="width:3.51583in;height:1.95186in" /></td>
</tr>
<tr class="odd">
</tr>
<tr class="even">
<td><ol start="128" type="1">
<li><p>Click on the button <em>Setting</em> <img
src="media/image152.png" style="width:0.18056in;height:0.125in" /> to
see configuration details of the default monitoring dashboard.</p></li>
</ol></td>
<td><img src="media/image153.png"
style="width:1.46684in;height:1.61438in" /></td>
</tr>
</tbody>
</table>

## 

## Building your own Monitoring Dashboard

<table>
<colgroup>
<col style="width: 41%" />
<col style="width: 58%" />
</colgroup>
<thead>
<tr class="header">
<th>Explanation</th>
<th>Screenshot</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol start="129" type="1">
<li><p>Use the default monitoring dashboard to create your individual
one. Change the values as follows and push button <em>Save As
…</em></p></li>
</ol>
<blockquote>
<p>Number of Columns: <em>2</em></p>
<p>Number of Rows: <em>2</em></p>
<p>Is Default: <em>not checked</em></p>
</blockquote></td>
<td><img src="media/image154.png"
style="width:1.69816in;height:2.02919in" /></td>
</tr>
<tr class="even">
<td rowspan="2"><ol start="130" type="1">
<li><p>Enter the name and namespace and push button
<em>Save.</em></p></li>
</ol>
<blockquote>
<p>Name:</p>
<p><em>My monitoring dashboard</em>
DEMO<em><strong>&lt;YOUR_USERNR&gt;</strong></em></p>
<p>Namespace:</p>
<p><a href="http://demo"><em>http://demo</em></a></p>
</blockquote></td>
<td rowspan="2"><img src="media/image155.png"
style="width:2.15402in;height:1.28819in" /></td>
</tr>
<tr class="odd">
</tr>
<tr class="even">
<td><ol start="131" type="1">
<li><p>Push button <em>Settings</em> <img src="media/image152.png"
style="width:0.18056in;height:0.125in" /> to replace the left chart
below.</p></li>
</ol></td>
<td><img src="media/image156.png"
style="width:3.92153in;height:1.69861in" /></td>
</tr>
<tr class="odd">
<td><ol start="132" type="1">
<li><p>Search for your chart by scrolling through the list. Mark the
chart you created and click on the Select Button</p></li>
</ol></td>
<td><img src="media/image157.png"
style="width:3.92153in;height:0.8375in" /></td>
</tr>
<tr class="even">
<td><ol start="133" type="1">
<li><p>Look at left chart below that has been changed and
updated</p></li>
</ol></td>
<td><img src="media/image158.png"
style="width:3.09651in;height:1.64449in" /></td>
</tr>
<tr class="odd">
<td><ol start="134" type="1">
<li><p>Push button <em>Settings</em> <img src="media/image152.png"
style="width:0.18056in;height:0.125in" /> to replace the right chart
below.</p></li>
</ol></td>
<td><img src="media/image159.png"
style="width:3.13579in;height:1.55655in" /></td>
</tr>
<tr class="even">
<td><ol start="135" type="1">
<li><p>Select one of your <strong>patterns</strong> and push button
<em>Select.</em></p></li>
</ol></td>
<td><img src="media/image160.png"
style="width:3.92153in;height:0.70625in" /></td>
</tr>
<tr class="odd">
<td><ol start="136" type="1">
<li><p>Look at right chart below that has been changed and
updated</p></li>
</ol></td>
<td><img src="media/image161.png"
style="width:3.57534in;height:1.98109in" /></td>
</tr>
<tr class="even">
<td><ol start="137" type="1">
<li><p>Click on the button Setting <img src="media/image152.png"
style="width:0.18056in;height:0.125in" /> and push button Save to save
your monitoring dashboard.</p></li>
</ol></td>
<td><img src="media/image162.png"
style="width:2.39604in;height:1.45606in" /></td>
</tr>
</tbody>
</table>

## Summary:

**Security Aspect:** As a Security Monitoring Agent you have learned
that the Monitoring Dashboard is the most important tool for you to deal
with your daily security monitoring task.

**Tool Aspect:** You learned how to open the default Monitoring
Dashboard and customize it to fit your own need
