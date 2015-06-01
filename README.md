# polymer-datatables

**This element is compatible with Polymer 0.5.**

__Example:__

```
    <polymer-datatables-table
      data="{{ data }}"
      tableApi="{{ tableApi }}"
      perPage="{{ perPage }}"
      columns="{{ columns }}"
      perPageCount="{{ perPageCount }}"
      filters="{{ filters }}"
      pageTotal="{{ pageTotal }}"
      resultTotal="{{ resultTotal }}"
      currentPage="{{ currentPage }}"></polymer-datatables-table>
    <polymer-datatables-filter
      tableApi="{{ tableApi }}"
      column="position"
      columns="{{ columns }}"
      filters="{{ filters }}"></polymer-datatables-filter>
    <polymer-datatables-search
      tableApi="{{ tableApi }}"></polymer-datatables-search>
    <polymer-datatables-pages
      perPage="{{ perPage }}"
      perPageCount="{{ perPageCount }}"
      pageTotal="{{ pageTotal }}"
      currentPage="{{ currentPage }}"></polymer-datatables-pages>
    <polymer-datatables-perpage-selector
      perPage="{{ perPage }}"
      perPageCount="{{ perPageCount }}"
      pageTotal="{{ pageTotal }}"
      currentPage="{{ currentPage }}"></polymer-datatables-perpage-selector>
    <polymer-datatables-result-range
      data="{{ data }}"
      perPage="{{ perPage }}"
      resultTotal="{{ resultTotal }}"
      perPageCount="{{ perPageCount }}"
      currentPage="{{ currentPage }}"></polymer-datatables-result-range>
    <polymer-datatables-previous
      tableApi="{{ tableApi }}"
      pageTotal="{{ pageTotal }}"
      currentPage="{{ currentPage }}">Previous</polymer-datatables-previous>
    <polymer-datatables-next
      tableApi="{{ tableApi }}"
      pageTotal="{{ pageTotal }}"
      currentPage="{{ currentPage }}">Next</polymer-datatables-next>
    <polymer-datatables-export-csv
      filename="csv"
      columns="{{ columns }}"
      data="{{ data }}">Export</polymer-datatables-export-csv>
```
# Elements

#### `<polymer-datatables-table>`

Creates datatable

#### `<polymer-datatables-filter>`

Creates datatable filters

#### `<polymer-datatables-search>`

Creates datatable searchbox

#### `<polymer-datatables-pages>`

Created pagination

#### `<polymer-datatables-perpage-selector>`

Creates dropdown to select records per page

#### `<polymer-datatables-result-range>`

Creates current page count. Ex. '1-25 of 50'

#### `<polymer-datatables-previous>`

Creates button to go to the previous page

#### `<polymer-datatables-next>`

Creates button to go to the next page

#### `<polymer-datatables-export-csv>`

Creates button download CSV for all data

# Attributes

#### `data`

An array of data.

#### `tableApi`

An object returned from the polymer-datatables-table for using datatables api.

#### `perPage`

Records shown  per page.

#### `columns`

Array representing the table header.

#### `perPageCount`

Array for the options in 'Rows Per Page' dropdown.

#### `filters`

Object returned from datatables

#### `pageTotal`

Returns total number of pages

#### `resultTotal`

Return total number of records

#### `currentPage`

Return number for current page.