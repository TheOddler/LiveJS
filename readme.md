This is an alternative version of [LiveJS by Q42](livejs.com) that also checks the actual content of each file.
This is less efficient, but works with servers that don't return the monitored headers.

# How?

Just include [PabloProductions.be/LiveJS/livejs.js](pabloproductions.be/LiveJS/livejs.js) and it will monitor the current page including local CSS and Javascript by sending consecutive GET requests to the server.

Changes to CSS will be applied dynamically and HTML or Javascript changes will reload the page.
