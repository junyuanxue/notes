Modern UI by Karolis

* Each each is just a function that returns data:
  ```
  fn(data)
  App(data)
  <App data={data} />
  ```

  - A component is just a function in React.


* Data changes all the time (through server, interaction, effect), how do you keep the UI up to date?
  - Wrap it in `render` and call it again and again. Or give it an `update` function
  - E.g. Redux
  - When data changes, should either only call `render` or `update`, rather than injecting something else into the DOM.
  - Rerender the whole app once something changes.


* Example and counter-example: https://github.com/QubitProducts/tiny-atom
