##### Creates snippet that will setup a `test_helper` file by running `test_helper`
<em><sub>SimpleCov included to see coverage</sub></em>
```ruby
'SimpleCov':
  'prefix': 'test_helper'
  'body': """
  require 'simplecov'

  SimpleCov.start do
  end

  require 'minitest/autorun'
  require 'minitest/pride'

  require './lib/'
  require './lib/'
  """
```
