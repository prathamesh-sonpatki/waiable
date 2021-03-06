# Waiable

waiable gem is the Rails **W**&#8203;eb **A**&#8203;ccessibility **I**&#8203;nitiative for differently **able**.

This gem forces all Rails ActionView components to be compliant with WAI-ARIA standards.
If you are looking to contribute, please  go through the contributing section below.


## Installation

Add this line to your application's Gemfile:

    gem 'waiable'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install waiable

## Usage


## Contributing
###First the basic examples
1. We are maintaining a set of [Accessibility Examples](https://github.com/techvision/accessibilityexamples). 
These examples are going to form the basis of our WAIable gem. 
2. The approach is going to be 
  a. to build a basic example with JavaScript/jQuery, HTML and CSS in our [Accessibility Examples](https://github.com/techvision/accessibilityexamples) repository. Out there, basic examples go under public/basicExamples directory.
  b. Then scan the HTML, JS and CSS implemented to parameterize it. Implement the same in a simple Rails application under the same [Accessibility Examples](https://github.com/techvision/accessibilityexamples) repository

###Taking widget to WAIAble
1. Come up with a wiki that discusses the way widget would be invoked from a Rails view.
2. Conclude the discussion in point 1. Then create issues to write out corresponding minitests for WAIable WAI-ARIA widget.
3. Finally implement a running widget in WAIable.

###How to go about it?
1. Fork it 
https://github.com/techvision/waiable/fork
2. Create your feature branch ( git checkout -b my-new-feature )
3. Commit your changes ( git commit -am 'Add some feature' )
4. Push to the branch ( git push origin my-new-feature )
5. Create new Pull Request