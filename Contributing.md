# Contributing to Remarkable

* Website: https://sanbox.org/remarkable
* Email me: chris@sanbox.org

## Using the issue tracker

The [issue tracker](https://github.com/chrisyongchu/Remarkable/issues) is the preferred method for reporting bugs, feature requests and submitting pull requests. Please respect the following restrictions:

* Please **do not** use the issue tracker for support requests.
* Please **do not** troll issues. 
* Please **do not** post comments that do not pertain to Remarkable. We reserve the right to delete comments which violate this rule.

## Reporting bugs

A bug is a consistent _replicable problem_ that is caused by the code in the repository. Good bug reports are extremely helpful!

Guidelines for reporting bugs:

1. **Validate your code** to ensure that your problem isn't caused by an error in your own code.
2. **Use the GitHub issue search** to check if the issue has already been reported by someone.
3. **Check if the issue has already been fixed**.

We shouldn't need to ask you for more information. Please try to be as detailed as possible in your report. Include information such as:

* Your environment
* Steps taken to replicate the issue
* Does it only occur in a specific browser or OS?

Details like the above can help us fix any potential bugs.

## Code guidelines

If you would like to contribute to Remarkable, first, I'd like to thank you! To adhere to code standards, please follow this [Code Guide](http://codeguide.co/#html).

### HTML 

* Use tags and elements appropriate for an HTML5 doctype.
* Use CDNs and HTTPS for third-party JS when possible.

### CSS

* Do not remove default `:focus` styles (e.g., `outline: none;`) without providing alternative styles.

### JS

* No semicolons (in client-side JS)
* 2 spaces (no tabs)
* strict mode
* Don't use [jQuery event alias convenience methods](https://github.com/jquery/jquery/blob/master/src/event/alias.js) (such as `$().focus()`). 

## License

By contributing your code, you agree to license your contribution under the [MIT License](https://sanbox.org/license/MIT).


