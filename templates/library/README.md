# <%= project.slug %>

<%= project.description %>

## Installation

```sh
npm install <%= project.slug %>
```

## Usage

```js
import <%= project.name %> from "<%= project.slug %>";

// ...

const deviceName = await <%= project.name %>.getDeviceName();
```

## Scripts

- `yarn bootstrap`: setup project by installing all dependencies and pods.
- `yarn typescript`: type-check files with typescript.
- `yarn lint`: lint files with eslint.
- `yarn test`: run unit tests with jest.
- `yarn example start`: start the metro server for the example app.
- `yarn example android`: run the example app on Android.
- `yarn example ios`: run the example app on iOS.

## License

MIT
