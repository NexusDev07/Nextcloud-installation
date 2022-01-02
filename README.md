<h1>Nextcloud</h1>
<h2>Presentation</h2>
The Nextcloud module for WiseCP allows you to offer your customers data storage services on a Nextcloud server.
<br />
<br />
<h2>Installation</h2>
<b>1 - </b>Upload on your server the folder named <code>Nextcloud</code>.
<br />
<br />
<b>2 - </b>Unzip the folder.
<br />
<br />
<b>3 - </b>Place the <code>Nextcloud</code> folder in the <code>coremio/modules/Servers/</code> path on your WiseCP system.
<br />
<br />
<b>4 - </b>Add the <code>777</code> permission recursively to the folder.
<br />
<br />
<h2>Configuration</h2>
<h4>Add a new server:</h4>
<b>1 - </b>Go to the server setup page.
<br />
<br />
<b>2 - </b>Click on the button to add a new server.
<br />
<br />
<b>3 - </b>Select the Nextcloud module.
<br />
<br />
<b>4 - </b>In the field for the IP address of the server, enter the URL of your Nextcloud (ex: <code>nextcloud.domain.ext</code>). In the field for the the username, enter your Nextcloud username. And in the field for the password, enter your Nextcloud password. Then enter the other information requested in the other fields.
<br />
<font color="orange"><b>Caution!</b> The credentials you enter must provide access to the administrator panel.</font>
<br />
<br />
<b>5 - </b>Click on the button to add the server.
<br />
<br />
<h4>Add a product:</h4>
<b>1 - </b>Go to the page to create a product (Dedicated/VPS Packages).
<br />
<br />
<b>2 - </b>Click on the button to create a new product.
<br />
<br />
<b>3 - </b>In the "Core" part, select the server configured for Nextcloud, and indicate the quota you wish to allocate in the "Quota" field. If you want your customers to be able to create other users on their quota, select the "Enable reseller" box (the <a href="https://apps.nextcloud.com/apps/groupquota">Group quota</a> module is required on your Nextcloud server).
<br />
<br />
<b>4 - </b>Click on the button to create the product.
<br />
<br />
<br />
<b>For any questions, bug reports, suggestions... do not hesitate to contact us by email at <code>developer@easygohost.net</code>.</b>
