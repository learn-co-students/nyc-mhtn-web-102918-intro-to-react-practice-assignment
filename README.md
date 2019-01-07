# Assignment

Transform this data structure:

```
[
  { id: 1, name: "Steven", band: "Daft punk", song: "Digital Love" },
  {
    id: 2,
    name: "Jason",
    band: "Radiohead",
    song: "These are my twisted words"
  },
  {
    id: 3,
    name: "Vickty",
    band: "Khruangbin",
    song: "White gloves"
  }
];
```

into this html using `React`: 

```
<div>
  <h2>Steven preferences: </h2>
  <p>
    Steven loves Daft punk and recommends <strong>Digital Love</strong>
  </p>
</div>
<div>
  <h2>Jason preferences: </h2>
  <p>
    Jason loves Radiohead and recommends{" "}
    <strong>These are my twisted words</strong>
  </p>
</div>
<div>
  <h2>Vickty preferences: </h2>
  <p>
    Vickty loves Khruangbin and recommends <strong>White gloves</strong>
  </p>
</div> 
```