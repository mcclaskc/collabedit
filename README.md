collabedit
==========

repo to store stuff I do on collabedit.com

latest:

```ruby
class Clasky
    
    @@awesome = true
    @@instances = 0;
    
    def initialize
        raise "There can only be one claskylander!" if @@instances == 1
        @@instances += 1
    end
    
    def self.is_awesome?
        @@awesome
    end
    
    def is_awesome?
        @@awesome
    end
    
end
```
