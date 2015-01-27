[![NPM version](https://badge.fury.io/js/gsl-const.svg)](http://badge.fury.io/js/gsl-const)

# gsl-const
physical constants for JS via GNU Scientific Library

## Installation

```
npm install gsl-const
```

## Usage

```
gsl_const = require('gsl-const');
console.log( gsl_const.CGS.SPEED_OF_LIGHT );
```

## Reference

See [GSL Documentation](http://www.gnu.org/software/gsl/manual/html_node/Physical-Constants.html#Physical-Constants) for 
a list of all available constants. The prefix `GSL_CONST_` should always be replaced by the name of the variable holding the
module (in above case, gsl_const), followed by a dot, then the name of the unit system (CGS, CGSM, MKS, MKSA, NUM), another
dot and the name of the constant. 
