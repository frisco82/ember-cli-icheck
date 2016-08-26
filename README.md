# ember-cli-icheck

ember-cli addon component for [iCheck](http://fronteed.com/iCheck/)

## Installation

* `ember install ember-cli-icheck-1.1`

## Usage

* In any `.hbs` file,
	- `{{i-check checked=variable}}`
	- `{{i-check type="radio" checked=variable}}`
	- `{{i-check type="checkbox" checked=variable checkboxClass='icheckbox_whatever-style'}}`
	- `{{i-check type="radio" checked=variable radioClass='iradio_whatever-style' areaIncrease="30%"}}`

* Defaults:
	- checkboxClass: 'icheckbox_square-blue'
	- radioClass: 'iradio_square-blue'
	- increaseArea: '20%'
