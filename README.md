bootstrap-dropdown-control
==========================

Provides support for placing form-elements in Bootstrap dropdowns

Features
--------
* prevents bootstrap dropdown from hiding when clicking inside
* automatically focus the first visible form element when the dropdown is shows up
* close dropdown on blur when the new active element is not in dropdown content

Examples
--------


Javascript initialization
```
$('.dropdown-control').dropdownControl({
  showOnFocus: true, 
  focusInput: true
})
```

Markup
```
<div class="btn-group">
  <button type="button" class="btn btn-default dropdown-toggle dropdown-control">
     Filters <span class="caret"></span>
  </button>
  <div class="dropdown-menu" role="menu">
    <div class="form-group">
      <input type="text" class="form-control">
    </div>
  </div>
</div>
```

Options
-------
<table>
  <tr>
    <th>Name</th><th>Description</th><th>Default</th>
  </tr>
  <tr>
    <td>focusInput</td><td>automatic focus first element</td><td>false</td>
  </tr>
  <tr>
    <td>showOnFocus</td><td>automatically opens the dropdown on focus</td><td>false</td>
  </tr>
</table>

Example Demo
------------
See it in action here:
http://rawgithub.com/benignware/bootstrap-dropdown-control/master/examples/index.html