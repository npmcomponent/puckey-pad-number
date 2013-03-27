
# pad-number

  Component: create a string representation of a number with leading zeroes.

  Using @Pointy's [answer](http://stackoverflow.com/a/10073788) on Stackoverflow.

## Installation

    $ component install puckey/pad-number

## API
   
	var pad = require('pad-number');

	console.log(pad(10, 4)); // '0010'

	console.log(pad(10, 5)); // '00010'

	console.log(pad(10, 1)); // '10'

	// Optional padding character:
	console.log(pad(10, 5, '-')); // '---10'

## License

  MIT
