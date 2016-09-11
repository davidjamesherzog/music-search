# Music Search

This is a music mobile application that makes use of the iTunes API.  You can search for a musician and then select an album and view all the deatils of that album.

Technologies used:

- Ionic 2
- Angular 2
- Typescript
- Gulp

## Install

Install the following global libraries:

```bash
npm install -g cordova
npm install -g ionic@beta
npm install -g typescript
npm install -g typings
npm install -g tsd
```

# Create project

Use the following command to create an Ionic 2 project.

```bash
ionic start musicSearch tutorial --v2 --ts
```

# Create Pages

This app has two pages.  Creating them is a one time event.

``` bash
ionic g page music
ionic g page music-details
```

# Create Providers

This app has one service that interacts with the iTunes API.

```bash
ionic g provider itunes
```

# Run Project

Running the project is as simple as running the following command.

```bash
ionic serve
```
