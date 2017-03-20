# SoME Book List

## About
Display list of books from the Southern Maine Men's Book club in a searchable, filterable, pretty HTML table. Done in 100% JavaScript. 

Originally forked from [derekeder/csv-to-html-table](https://github.com/derekeder/csv-to-html-table), but later
converted to just using YAML data and jQuery DataTables directly.

Check out the live site: http://stephenhouser.github.io/some-books/

## Usage

In typical usage the `some-books.json` is updated with new books we have read or are reading. Then, viola, the site is magically and deliciously updated.

## About the Code

Originally adapted from [derekeder/csv-to-html-table](https://github.com/derekeder/csv-to-html-table). Which would convert CSV files for use by jQuery DataTables. I no longer use any of Derek's code, but have an appreciation and give thanks for his work.

Uses [jQuery](https://jquery.com), but only for the [jQuery DataTables](https://datatables.net) plugin.

Uses [jeremyfa/yaml.js](https://github.com/jeremyfa/yaml.js) to convert [YAML](http://www.yaml.org) to [JSON](http://www.json.org) for [jQuery DataTables](https://datatables.net).

Uses [Bootstrap Table](http://bootstrap-table.wenzhixin.net.cn) for the table display.

Uses Amazon cover and thumnail images as per [How to get book cover image url using ISBN](http://stackoverflow.com/questions/33886418/how-to-get-book-cover-image-url-using-isbn) on StackOverflow.

## Copyright

Copyright (c) 2017 Stephen Houser. Released under the [MIT License](https://github.com/stephenhouser/some-books/blob/master/LICENSE).