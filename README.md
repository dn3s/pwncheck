# pwncheck

Keep tabs on all your accounts from the CLI. With pretty colors!

Uses [haveibeenpwned](https://haveibeenpwned.com/)'s REST API.

## Requirements

- Linux
- Recent Python3
- Python `Requests` module

## Usage

- `pwncheck <email1> [<email2> [...<emailn>]]`
- Create a file at `~/.emails`, with one email address per line to save on typing
- Once you've addressed a leak and don't need to be alerted about it anymore,
  append a space, followed by the name (The first word after the date of the
  leak) to the end of the email address in your `~/.emails` file. Multiple
  leaks can be separated by single spaces.

## Example

`~/.emails`:

```
example1@example.com
example2@examlpe.com Dropbox
example2@examlpe.com Lastfm LinkedIn Yahoo Tumblr 000webhost
example3@example.com Adobe
```
