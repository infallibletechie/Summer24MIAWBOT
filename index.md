<html>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DWs000000hWe9',
				'MIAW_GitHub_with_Omni_Flow_and_BOT',
				'https://storm-4d7d0ef01463a2.my.site.com/ESWMIAWGitHubwithOmni1715703021987',
				{
					scrt2URL: 'https://storm-4d7d0ef01463a2.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://storm-4d7d0ef01463a2.my.site.com/ESWMIAWGitHubwithOmni1715703021987/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
