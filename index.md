<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'fr'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DAY000008Qoz3',
				'KalitiChatbot_EmbeddedDeployment',
				'https://kalitisolutions--portaldev.sandbox.my.site.com/ESWKalitiChatbotEmbedded1744729782883',
				{
					scrt2URL: 'https://kalitisolutions--portaldev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://kalitisolutions--portaldev.sandbox.my.site.com/ESWKalitiChatbotEmbedded1744729782883/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


</body>
</html>
