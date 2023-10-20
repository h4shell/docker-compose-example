add this line in wordpress/wp-config.php

<code>
$domain = 'http://testwordpress.com';
define('WP_SITEURL', $domain);
define('WP_HOME', $domain);
</code>

if you want a tunnel for vscode codeplace run this command

<code>
ssh -R 80:localhost:8080 nokey@localhost.run
</code>