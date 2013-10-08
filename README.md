zach-punch
==========

Testing out punch for Zach
- https://github.com/laktek/punch
- http://zach.is/

## Development

To see it in dev, install punch (link above), then run

	cd zach-punch; punch s

and view in browser.  

To copy / upload to a static site,

	cd zach-punch && punch g && cd output && tar cvfz ../zp-output.tgz * && cd ..
	scp zp-output.tgz to.some.hosting.site.com:
