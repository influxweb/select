select
======

Minimally custom-styled select element.

## Basic (required) markup

* a container element
* label text element
* the select

We like to use a `label` around a `span` for the label text followed by the `select`.  This ensures that the `label` is pointing to the correct form field, and neatly contains the text so that we can more easily modify the DOM with enhanced markup and styles.

`&lt;label>
	&lt;span>Shipping method:&lt;/span>
	&lt;select name="demo">
		&lt;option>Ground (7-9 days)&lt;/option>
		&lt;option>Prioritized (3-5 days)&lt;/option>
		&lt;option>2-day&lt;/option>
		&lt;option>Next business day&lt;/option>
	&lt;/select>
&lt;/label>`

The basic version of the select is usuable on all devices that can render HTML:
PIC

## Enhancements


