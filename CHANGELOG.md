# Changelog

## v1.6.1
Fixed height for long stacks.

## v1.6.0
Added links to MDN and Stack Overflow for help.

## v1.5.0
- Added output of total number of errors.
- Increased size of buttons.

## v1.4.0
Added ability to change text for button copy.

## v1.3.0
- Added screen properties in detailed message
- Error loading for css, image and script files
- Separate template for detailed message

Example:
```js
showJSError.init({
    errorLoading: true,
    templateDetailedMessage: 'Before\n{message}\nAfter'
});
```

## v1.2.0
Added bower support.
