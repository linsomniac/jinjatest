# JinjaTest -- Simple Jinja2 Template Expander

This is a simple Jinja2 template expander, it reads a template file and prints the
expanded template to stdout.  One use of this is to quickly iterate, testing
combinations of whitespace trimming for a desired result.

Variables can be provided using command-line arguments.

## Examples

    #  template with variables set in the Jinja2 environment
    $ jinjatest --set user=sean --json '{"group_names": ["dev", "stg"]}' template.j2
    [...]
    #  Template from stdin
    $ date | jinjatest -
    [...]

## Requirements

- Python 3

## License

CC0 1.0 Universal, see LICENSE file for more information.

<!-- vim: ts=4 sw=4 ai et tw=85
-->
