## How to solve this challenge?

1. Read the "Challenge description" below.
2. Make changes to the [challenge.rb](./challenge.rb) file.
3. Commit your changes.
4. Wait for the result of the "GitHub Classroom Workflow" action. If it is green - congratulations, you solved this challenge! If not - try again!
      - If you cannot see any auto-grading workflows on the  [Actions](../../actions) page, learn how to fix it in [this repo](https://github.com/microverse-students/autograding-troubles-ruby).
5. *You can watch an example of how to solve a challenge in [this video](https://microverse.pathwright.com/library/fast-track-algorithms-data-structures/69123/path/step/113963868/)*

Note: We use RSpec for checking your solution with unit tests. You can [install](https://github.com/rspec/rspec) it and use it in your local environment if you like.


## Challenge description

### Balanced Brackets

There are 3 kinds of Brackets: [] {} (). Given a String  of characters, check if all the brackets in the String are Balanced. A  string is balanced if all the start and end brackets are in a correct  order so they match each other.
Here are some balanced Strings:

- {}
- (hello)[world]
- [({}{}{})([])]

Here are some Unbalanced ones:

- (hello - no ending )
- ([)] - The [ is improperly enclosed in the ().
- )( - There's an ending ) without a ( before it.

Return true if a line is balanced and false otherwise.

#### Examples

The following are 3 test cases:

```rb
puts balanced_brackets?('(hello)[world]')
# => true

puts balanced_brackets?('([)]')
# => false

puts balanced_brackets?('[({}{}{})([])]')
# => true
```

### Troubleshooting

If you cannot see any auto-grading workflows on the [Actions](../../actions) page, learn how to fix it in [this repo](https://github.com/microverse-students/autograding-troubles-ruby).
