## Introduction[](#introduction)

`anomaly.field_type.repeater`

The repeater field type adds repeating data structures to your forms.


### Configuration[](#introduction/configuration)

Below is a list of available configuration with default values:

    "example" => [
        "type"   => "anomaly.field_type.repeater",
        "config" => [
            "related"        => null,
            "max"            => null,
            "min"            => null,
            "add_row"        => "anomaly.field_type.repeater::button.add_row",
        ]
    ]

###### Configuration

<table class="table table-bordered table-striped">

<thead>

<tr>

<th>Key</th>

<th>Example</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>

related

</td>

<td>

`\Anomaly\RepeatersModule\Example\ExampleModel::class`

</td>

<td>

The related repeater model. You can also define any model via API.

</td>

</tr>

<tr>

<td>

max

</td>

<td>

5

</td>

<td>

The maximum items allowed.

</td>

</tr>

<tr>

<td>

min

</td>

<td>

2

</td>

<td>

The minimum items allowed.

</td>

</tr>

<tr>

<td>

add_row

</td>

<td>

module::button.add_example

</td>

<td>

The translatable text for the "add row" button.

</td>

</tr>

</tbody>

</table>
