# ctx_reg-cookbook

TODO: Enter the cookbook description here.

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['ctx_reg']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### ctx_reg::default

Include `ctx_reg` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[ctx_reg::default]"
  ]
}
```

## License and Authors

Author:: Todd Pigram (<todd@toddpigram.com>)
