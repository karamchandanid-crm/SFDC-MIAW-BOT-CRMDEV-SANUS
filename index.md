<html>
  <head>
    <title>
      MIAW Demo: CRMDEV - Sanus Live Chat (sandbox)
    </title>
    <style>
      h1{
        display: none;
      }
    </style>
  </head>
  <body>
    <h2> MIAW Demo: CRMDEV - Sanus Live Chat (sandbox)</h2>
    <script type='text/javascript'>
    	function initEmbeddedMessaging() {
    		try {
    			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
    
    			embeddedservice_bootstrap.init(
				'00DOz000004sefh',
				'Sanus_Live_Chat_Github',
				'https://legrandav--crmdev.sandbox.my.site.com/ESWSanusLiveChatGithub1731989339524',
				{
					scrt2URL: 'https://legrandav--crmdev.sandbox.my.salesforce-scrt.com'
				}
			);
    		} catch (err) {
    			console.error('Error loading Embedded Messaging: ', err);
    		}
    	};
    </script>
    <script type='text/javascript' src='https://legrandav--crmdev.sandbox.my.site.com/ESWSanusLiveChatGithub1731989339524/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
