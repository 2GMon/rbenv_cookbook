ruby-env Cookbook
=================

This cookbook install ruby with rbenv.

Attributes
----------

#### ruby-env::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['ruby-env']['user']</tt></td>
    <td>String</td>
    <td>install user name</td>
    <td><tt>vagrant</tt></td>
  </tr>
  <tr>
    <td><tt>['ruby-env']['group']</tt></td>
    <td>String</td>
    <td>install user group</td>
    <td><tt>vagrant</tt></td>
  </tr>
  <tr>
    <td><tt>['ruby-env']['version']</tt></td>
    <td>String</td>
    <td>ruby version</td>
    <td><tt>2.2.2</tt></td>
  </tr>
  <tr>
    <td><tt>['ruby-env']['rbenv_url']</tt></td>
    <td>String</td>
    <td>rbenv repository url</td>
    <td><tt>https://github.com/sstephenson/rbenv</tt></td>
  </tr>
  <tr>
    <td><tt>['ruby-env']['ruby-build_url']</tt></td>
    <td>String</td>
    <td>ruby-build repository url</td>
    <td><tt>https://github.com/sstephenson/ruby-build</tt></td>
  </tr>
</table>

Usage
-----
#### ruby-env::default

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[ruby-env]"
  ]
}
```

License and Authors
-------------------
Authors: 2GMon
