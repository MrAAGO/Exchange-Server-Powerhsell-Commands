# Exchange-Server-Powerhsell-Commands

<!DOCTYPE html>
<html>
<head>
	<meta http-equiv="content-type" content="text/html; charset=utf-8"/>
	
</head>
<body lang="en-US" link="#000080" vlink="#800000" dir="ltr"><h1 class="western">
                          The Exchange Admin Center 
</h1>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<span style="font-variant: normal"><font color="#374151"><font face="S hne, ui-sans-serif, system-ui, apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, sans-serif, Helvetica Neue, Arial, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji"><font size="3" style="font-size: 12pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">The
Exchange Admin Center (EAC) is a web-based management console that
you can use to manage Exchange Server and Exchange Online. While the
EAC provides a graphical interface for managing Exchange, you can
also use PowerShell to perform many of the same tasks.</span></span></span></font></font></font></span>
</p>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
<p style="orphans: 2; widows: 2">Here is a list of some common
Exchange Admin Center-related PowerShell commands that you may find
helpful:</p>
<ol>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">New-Mailbox</span></b></code><b>:</b>
	This command creates a new mailbox for a user.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Set-Mailbox</span></b></code><b>:</b>
	This command modifies the properties of an existing mailbox.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Enable-Mailbox</span></b></code><b>:</b>
	This command re-enables a disabled mailbox and allows the user to
	access their mailbox and email again.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Disable-Mailbox</span></b></code>:
	This command disables a mailbox and removes it from the user's
	account, but retains the user's account and mailbox data in the
	database.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">New-MailContact</span></b></code>:
	This command creates a new mail contact, which is a type of
	recipient that represents an external email address.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Set-MailContact</span></b></code>:
	This command modifies the properties of an existing mail contact.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">New-MailUser</span></b></code>:
	This command creates a new mail user, which is a type of recipient
	that represents a user who does not have a mailbox.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Set-MailUser</span></b></code><b>:
	This command modifies the properties of an existing mail user.</b></p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">New-DistributionGroup</span></b></code>:
	This command creates a new distribution group, which is a type of
	recipient that represents a group of users or contacts.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Set-DistributionGroup</span></b></code>:
	This command modifies the properties of an existing distribution
	group.</p>
</ol>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<span style="font-variant: normal"><font color="#374151"><font face="S hne, ui-sans-serif, system-ui, apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, sans-serif, Helvetica Neue, Arial, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji"><font size="3" style="font-size: 12pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">Here
is a list of some common Exchange Server database-related PowerShell
commands that you may find helpful:</span></span></span></font></font></font></span>
</p>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
<p style="orphans: 2; widows: 2"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">Get-MailboxDatabase</span></code>:
This command retrieves a list of all mailbox databases in the
organization.</p>
<ol>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">New-MailboxDatabase</span></b></code>:
	This command creates a new mailbox database.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Set-MailboxDatabase</span></b></code>:
	This command modifies the properties of an existing mailbox
	database.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Remove-MailboxDatabase</span></b></code>:
	This command deletes a mailbox database.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Move-DatabasePath</span></b></code><b>:
	</b>This command moves the physical location of a mailbox database.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Update-MailboxDatabaseCopy</span></b></code><b>:</b>
	This command updates the status of a mailbox database copy in a
	database availability group (DAG).</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Suspend-MailboxDatabaseCopy</span></b></code><b>:</b>
	This command suspends replication for a mailbox database copy in a
	DAG.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Resume-MailboxDatabaseCopy</span></b></code><b>:</b>
	This command resumes replication for a mailbox database copy in a
	DAG.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Update-MailboxDatabaseCopyStatus</span></b></code><b>:</b>
	This command updates the status of a mailbox database copy in a DAG.</p>
	<li><p style="border: 1px solid #d9d9e3; padding: 0.02in"><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Add-MailboxDatabaseCopy</span></b></code><b>:</b>
	This command adds a mailbox database copy to a DAG.</p>
</ol>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
<p style="orphans: 2; widows: 2">The <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">Get-MailboxDatabase</span></code>
command retrieves a list of mailbox databases in your organization,
but it does not display the mailbox contents or users associated with
each database.</p>
<p style="border: 1px solid #d9d9e3; padding: 0.02in">To view the
users who have mailboxes in a specific mailbox database, you can use
the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">Get-Mailbox</span></code>
command and filter the results by the mailbox database using the
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">-Database</span></code>
parameter. 
</p>
<p style="border: 1px solid #d9d9e3; padding: 0.02in">For example:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Get-Mailbox -Database &quot;Mailbox Database 01&quot;</span></b></code></pre><p style="border: 1px solid #d9d9e3; padding: 0.02in">
This will retrieve a list of all the mailboxes in the &quot;Mailbox
Database 01&quot; database. If you want to see specific properties
for each mailbox, such as the user's display name or email address,
you can use the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">-Properties</span></code>
parameter and specify the properties you want to see. For example:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Get-Mailbox -Database &quot;Mailbox Database 01&quot; -Properties DisplayName, EmailAddresses</span></b></code></pre><p style="border: 1px solid #d9d9e3; padding: 0.02in">
This will show the display name and email addresses for each mailbox
in the &quot;Mailbox Database 01&quot; database.</p>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
<p style="orphans: 2; widows: 2">To save the output of a PowerShell
command to a text file, you can use the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">Out-File</span></code>
cmdlet. For example, to save the results of the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">Get-Mailbox</span></code>
command to a text file named &quot;MailboxList.txt&quot;, you can use
the following command:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Get-Mailbox -Database &quot;Mailbox Database 01&quot; -Properties DisplayName, EmailAddresses | Out-File -FilePath &quot;C:\Temp\MailboxList.txt&quot;</span></b></code></pre><p style="border: 1px solid #d9d9e3; padding: 0.02in">
This will create a new text file at the specified location and write
the output of the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Get-Mailbox</span></b></code><b>
</b>command to the file.</p>
<p style="border: 1px solid #d9d9e3; padding: 0.02in">If you want to
append the output to an existing text file instead of overwriting it,
you can use the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">-Append</span></code>
parameter. For example:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Get-Mailbox -Database &quot;Mailbox Database 01&quot; -Properties DisplayName, EmailAddresses | Out-File -FilePath &quot;C:\Temp\MailboxList.txt&quot; -Append</span></b></code></pre><p style="border: 1px solid #d9d9e3; padding: 0.02in">
This will add the output of the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Get-Mailbox</span></b></code>
command to the end of the &quot;<b>MailboxList.txt&quot;</b> file.</p>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
<p style="orphans: 2; widows: 2">To disable a mailbox in Exchange
Server, you can use the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Disable-Mailbox</span></b></code>
command. This will remove the mailbox from the user's account, but
the user's account and mailbox data will still be retained in the
database.</p>
<p style="border: 1px solid #d9d9e3; padding: 0.02in">To disable a
mailbox for a specific user, you can use the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">-Identity</span></b></code>
parameter to specify the user's mailbox. For example:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Disable-Mailbox -Identity &quot;John Smith&quot;</span></b></code></pre><p style="border: 1px solid #d9d9e3; padding: 0.02in">
To disable a mailbox for multiple users at once, you can pass a list
of identities to the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">-Identity</span></b></code>
parameter. For example:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Disable-Mailbox -Identity &quot;John Smith&quot;, &quot;Jane Doe&quot;</span></b></code></pre><p style="border: 1px solid #d9d9e3; padding: 0.02in">
To reconnect a disabled mailbox to a user account, you can use the
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">Enable-Mailbox</span></code>
command. This will re-enable the mailbox and allow the user to access
their mailbox and email again.</p>
<p style="border: 1px solid #d9d9e3; padding: 0.02in">To enable a
mailbox for a specific user, you can use the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">-Identity</span></code>
parameter to specify the user's mailbox. For example:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Enable-Mailbox -Identity &quot;John Smith&quot;</span></b></code></pre><p style="border: 1px solid #d9d9e3; padding: 0.02in">
To enable a mailbox for multiple users at once, you can pass a list
of identities to the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">-Identity</span></code>
parameter. For example:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">Enable-Mailbox -Identity &quot;John Smith&quot;, &quot;Jane Doe&quot;</span></b></code></pre><p style="orphans: 2; widows: 2">
To create a new mailbox in Exchange Server, you can use the
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">New-Mailbox</span></b></code>
command. This command allows you to specify various properties for
the new mailbox, such as the user's name, email address, and mailbox
database.</p>
<p style="border: 1px solid #d9d9e3; padding: 0.02in">Here is an
example of how to create a new mailbox for a user named &quot;John
Smith&quot; using the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">New-Mailbox</span></code>
command:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">New-Mailbox -Name &quot;John Smith&quot; -UserPrincipalName &quot;john.smith@contoso.com&quot; -Alias &quot;jsmith&quot; -Database &quot;Mailbox Database 01&quot;</span></b></code></pre><p style="border: 1px solid #d9d9e3; padding: 0.02in">
This command will create a new mailbox for John Smith with the email
address &quot;<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><a href="mailto:john.smith@contoso.com" target="_new">john.smith@contoso.com</span></a>&quot;,
an alias of &quot;jsmith&quot;, and store the mailbox in the &quot;Mailbox
Database 01&quot; database.</p>
<p style="border: 1px solid #d9d9e3; padding: 0.02in">You can also
use the <span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">-FirstName</span></b></code><b>,
</b><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">-LastName</span></b></code><b>,
and </b><span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><b><code class="western">-DisplayName</span></b></code>
parameters to specify the user's first and last name, and the display
name that will be displayed in the address book.</p>
<p style="border: 1px solid #d9d9e3; padding: 0.02in">For example:</p>
<pre class="western" style="border: 1px solid #d9d9e3; padding: 0.02in">
<span style="display: inline-block; border: 1px solid #d9d9e3; padding: 0.02in"><code class="western">N</code><b><code class="western">ew-Mailbox -Name &quot;John Smith&quot; -UserPrincipalName &quot;john.smith@contoso.com&quot; -Alias &quot;jsmith&quot; -Database &quot;Mailbox Database 01&quot; -FirstName &quot;John&quot; -LastName &quot;Smith&quot; -DisplayName &quot;John Smith&quot;</span></b></code></pre><p style="border: 1px solid #d9d9e3; padding: 0.02in">
<br/>
<br/>

</p>
<p style="line-height: 100%; orphans: 2; widows: 2; margin-bottom: 0in">
<br/>

</p>
</body>
</html>
