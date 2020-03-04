## Description
**This is a readme description**
----
## Reasons
The reasons to use this pattern
----
## Patterns
- a first pattern is to used only the interface JpaRepository. This should be the prefered pattern when it is possible.
- a second pattern is to use the interface JpaRepository plus an implementation which provides specific implementations which often used TypedQuery.
- a third pattern can be found when the interface inherit from BaseDAO. This seems link to the old code which was using JDO and not JPA. So when you see, these classes it meens the refactoring is not finish.
- etc
- etc
----
## Use cases
----
### Details
Provide more details about use cases
----
#### Examples
Provide examples about your patterns usage


# Foobar

Foobar is a Python library for dealing with word pluralization.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```pytho
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
