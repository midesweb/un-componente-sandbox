# \<dile-timestamp-to-date\>

Polymer component to show a date, in an appropriate format to human read, from a timestamp

`<dile-timestamp-to-date>`

## Polymer Element to display a date

Polymer component to show a date, in an appropriate format to human read.

The date to display is entered by seting a timestamp.

It also posible to set a format to introduce the way to present the date to the user.

```html
<dile-timestamp-to-date
  timestamp="491066777700"
  format="en"
></dile-timestamp-to-date>
````

## Styling

Custom property | Description | Default
----------------|-------------|---------
`--dile-timestamp-to-date | Mixin applied to entire element | {}

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing this Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
