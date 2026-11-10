# PharmaSys price feed

Official Egyptian medicine prices (source: dwaprices.com), one record per pack, matched by barcode.
Updated daily by a GitHub Action. Used by the PharmaSys app's "Price Updates" page.

`prices.json`: `{generated, count, items: [{id, b: [barcodes], p: price EGP, o: previous price, d: date of last change, n: name, a: Arabic name}]}`
