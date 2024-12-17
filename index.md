<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DTH000002jj6H',
				'Web_Chat_Test',
				'https://parker--deva5.sandbox.my.site.com/ESWWebChatTest1734469194430',
				{
					scrt2URL: 'https://parker--deva5.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://parker--deva5.sandbox.my.site.com/ESWWebChatTest1734469194430/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
