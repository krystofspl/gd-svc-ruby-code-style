GoodData Services Ruby Code Style Standards
-------------------------------------------
 
## Import the code style file into RubyMine

RubyMine -> Preferences -> Editor -> Code Style -> Ruby -> Scheme: Import scheme (XML)

## When editing in RubyMine: 

<kbd>⌘</kbd><kbd>⌥</kbd><kbd>L</kbd>
Will automatically reformat the code so that indenting etc follows the standards. Note that only the basic formatting is achieved this way.

## Run RuboCop before formatting:

Install if you don't have it installed yet:

`~> gem install rubocop`

Run:

`~> rubocop -c /path/to/.rubocop.yml /path/to/code`

Or have the yml file inside the repository and don't use the -c parameter.
`~> rubocop`

**Fixing *warning*, *error* and *fatal* is mandatory, fixing others is recommended.**