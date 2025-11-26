# Mocka API:er i React

## Övningar

### Movie search

Du hittar koden i mappen `movie-search`.
Instruktioner och user stories hittar ni här: https://gist.github.com/zocom-christoffer-wallenberg/8a7f78d324f53b14f850da9f86736388

### Swing notes

Skriv unit tester och mocka API:et för Swing notes. Du hittar koden i mappen `swing notes`.

Exempel på svar från API:et när man hämtar anteckningar:
```js
{
  notes: [
    {
      createdAt: "5/23/2024",
      id: "US0oobQukoiu8C8qmQxyM",
      note: "Min första anteckning",
      title: "Första anteckningen",
      username: "ada",
    },
    {
      createdAt: "5/23/2024",
      id: "_2FbzPa1QS9Pxjn4lvI7_",
      note: "Min andra anteckning",
      title: "Andra anteckningen",
      username: "ada",
    },
  ],
};
```

När man skapar en ny eller tar bort:
```js
{ success: true, message: "Note deleted" }
```
