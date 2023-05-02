```ruby
def say **arg 
  p arg[:msg].to_s.gsub! '_',' '
end

say(msg: :hello_world)
```
