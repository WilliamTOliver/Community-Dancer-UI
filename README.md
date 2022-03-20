# Community Dancer UI

## Intro
This is both a repository for a portfolio project and in it's structure (commits, readme, and changelog) instructions on how to construct a React/TypeScript UI.

To learn how to build a project like this, start in either the commits (broad strokes in commit messages + isolated code change diffs) or change log (detailed descriptions of changes)

This is paired with Community Dancer API which serves the same purpose (portfolio piece + instruction) but for a Express/TypeScript + Postgres/TypeORM REST API.

## Tools

### TypeScript
- Why: This project was built as an instructuional tool primarily for developers coming from a typed language background (C#, Java...) and for that reason uses TS to offer a shallower learning curve and some familiarity compared with going straight to JS.

### React
- Why: JS/TS UI frameworks have some differences, however, if you can get comfortable using one, you can probably work just fine in any of them. React was chosen as it is the primary context used by the author at time of writing, this could just as well be done in Vue with Vuetify instead of Material-UI or Angular with Angular-Material. 

### Material UI
- Why: Material UI (MUI for short) lets us quickly and with little effort put together really good looking UIs. While you don't have to use this, in whatever UI framework (react in this case)  you use, I recommend using whatever the primary Material design kit is for that framework unless you have a very good reason to not to do so. 

## Development
To run this project locally:
- `npm i`
- `npm start`




## Sources
Based originally on material-ui's [example React/TS project](https://github.com/mui/material-ui/tree/master/examples/create-react-app-with-typescript)
