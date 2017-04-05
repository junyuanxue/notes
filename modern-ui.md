Modern UI by Karolis

* Each each is just a function that returns data:
  ```
  fn(data)
  App(data)
  <App data={data} />
  ```

* A component is just a function in React
* Data changes all the time (through server, interaction, effect), how do you keep the UI up to date?
  - Wrap it in `render` and call it again and again. And give it an `update` function
  - E.g. Redux
