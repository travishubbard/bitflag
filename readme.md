bitflag
=======

Parameterize your API using bit flags to specify what your API returns.

You can specify more than one parameter option by adding bit flags together and entering the sum as the parameter value.

For example, to receive both page title and canonical URL form, enter Cols=5 (1 + 4).

For example, create an API that returns information regarding a paragraph of text:

Parameter:		analysis_actions

URL Metric				Bit Flag	Description Free Access?

Entity Extraction		1			The title of the page, if available	
Sentiment				4			The canonical form of the URL
Language				8			The subdomain of the URL (for example, apiwiki.moz.com)