*This repository is a mirror of the [component](http://component.io) module [puckey/pad-number](http://github.com/puckey/pad-number). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/puckey-pad-number`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# pad-number

  Component: convert a number to a string with n leading zeroes.

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
