ntp Cookbook
============
This cookbook installs and configure ntp.

Requirements
------------
None

Attributes
----------
```json
{
  "ntp": {
    "servers": ["..", ".."]
  }
}
```

e.g.
#### ntp::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['ntp']['servers']</tt></td>
    <td>Boolean</td>
    <td>list of ntp servers</td>
    <td><tt>[European ntp servers]</tt></td>
  </tr>
</table>

Usage
-----
#### ntp::default
Just include `ntp` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[ntp]"
  ]
}
```

Contributing
------------
Need help for testing following best practises, if you can help you are welcome!

License and Authors
-------------------
License: MIT

Authors:

Simone Dall'Angelo
