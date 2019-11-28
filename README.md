# Marketplace Connector
Microweber Marketplace Connector

```
<?php
include 'MicroweberMarketplaceConnector.php';

$connector = new MicroweberMarketplaceConnector();
$templatesUrl = $connector->get_templates_download_urls();

var_dump($templatesUrl);
?>

```
