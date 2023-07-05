# Note
## MUI
- [Sx vs Style props](https://stackoverflow.com/questions/72527461/when-should-i-use-style-instead-of-sx-prop-in-material-ui)

## EsLint
- [No unused vars for typescript](https://stackoverflow.com/questions/57802057/eslint-configuring-no-unused-vars-for-typescript)

## TypeScript
- [ways to declare a function in interface](https://stackoverflow.com/questions/30179394/multiple-ways-to-declare-a-function-on-a-typescript-interface-how-are-they-diff/30179665#30179665)
- Ts is for compilation-time, not runtime
- readonly acts like const but it checks at compilation-time
  ```
  interface Sth {
    readonly array: number[];
    readonly num: number;
  }

  const sth: Sth = {
    array: [1, 2, 3],
    num: 100,
  }

  sth.num =  10 // this doesn't work

  sth.array[0] = 4 // this works bc it's pointing to the memory location
  ```
### CSS
- [flex vs inline-flex](https://stackoverflow.com/a/27459133)
## Etc
- [UI/UX fundamentals for front end dev](https://medium.com/@hayavuk/ui-ux-design-fundamentals-for-the-front-end-developers-688ba43eaed4)
- [Resize `<Map>` from react-map-gl on render](https://stackoverflow.com/a/72984557)
- [Enabling click through div to underlying elements](https://stackoverflow.com/a/4839672)
- [Jest-exception to be thrown](https://stackoverflow.com/a/61982656)


