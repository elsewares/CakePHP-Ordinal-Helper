# CakePHP (2.0+) Ordinal Helper

A small helper to export ordinal numbers (1st, 3rd, 582nd, &c).

## Installation

Download or clone into app/View/Helper, then add

	var $helper = array('Ordinal');

to either AppController (for use app-wide), or the relevant individual controller.

## Use

Invoke the function like so:

	$this->Ordinal->addSuffix($num, $sup);

_$num_ is the number (pass an int, please) to be suffixed.


_$sup_ is a boolean - *true* wraps the suffix in a <sup> tag, false returns just the text.

