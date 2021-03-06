<h1 align="center">Wiki Map Project</h1>

## Table Of Contents

- [About](#about)
  - [Major Learnings](#major-learnings)
  - [Notable Features](#notable-features)
- [Visuals](#visuals)
  - [Screenshots](#screenshots)
  - [GIFs](#gifs)
- [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
- [Purpose](#purpose)
- [Credit](#credit)
  - [Vince Emond](#vince-emond)
  - [Kent Gulka](#kent-gulka)
  - [Ethan Loewen](#ethan-loewen)

# About

Wiki Map is a single page map collaboration app. The purpose of this app is to facilitate the creation and hosting of publicly available maps. Once created, each map can continue collecting more data through the submission and collaboration of other registered users. This app proves especially useful for mapping out locations that are typically not searchable in map search engines such as: Secret Waterfalls, Natural Hot Springs, Mushroom Foraging Zones, or even Nearby Free Parking Spots.

This application was created as a midterm project for [Lighthouse Labs'](https://www.lighthouselabs.ca/) Web Development Bootcamp by [Vince Emond](https://github.com/VinceEmond), [Kent Gulka](https://github.com/kgulka) and [Ethan Loewen](https://github.com/ethanloewen) with the purpose of practicing HTML, CSS, Javascript, jQuery AJAX and PostgreSQL and most importantly to practice the workflow of GIT version control when working as a team on a project.

## Major Learnings:
1. Planned and built an ERD, user stories and routes
2. Managed time and workload distribution to meet deadlines
3. Wrote SCSS style sheets from the ground-up
4. Utilized both jQuery and AJAX
5. Integrated Leaflet's map API

## Notable Features
* Simple and yet effective UI using collapsing folders
* Browse maps created by various owners
* Registered users can create their own maps and contribute pins to other maps
* Registered user can view a list of all maps they've contributed to
* Ability to Edit map pins with a new Name, Description or Image

# Visuals

## Screenshots


### Wiki Map - Main Layout
!["Wiki Map - Main Layout"](https://github.com/VinceEmond/wiki_map/blob/main/public/images/Github%20Readme/Wiki_Map_Screenshot_1.png?raw=true)

### Wiki Map - Edit Pin
!["Wiki Map - Edit Pin](https://github.com/VinceEmond/wiki_map/blob/main/public/images/Github%20Readme/Wiki_Map_Screenshot_2.png?raw=true)


## GIFs
### Folder Animations

![Folder Animations](https://github.com/VinceEmond/wiki_map/blob/main/public/images/Github%20Readme/Folder_Animations.gif?raw=true)

### Map Pin Focus Animation

![Map Pin Focus Animation](https://github.com/VinceEmond/wiki_map/blob/main/public/images/Github%20Readme/Map_Pin_Focus.gif?raw=true)

### Create New Map

![Create New Map](https://github.com/VinceEmond/wiki_map/blob/main/public/images/Github%20Readme/Create_New_Map.gif?raw=true)

### Add New Pins

![Add New Pins](https://github.com/VinceEmond/wiki_map/blob/main/public/images/Github%20Readme/Add_New_Pins.gif?raw=true)

### Edit Existing Pins

![Edit Existing Pins](https://github.com/VinceEmond/wiki_map/blob/main/public/images/Github%20Readme/Editing_Pins.gif?raw=true)

# Getting Started
1. Fork this repository, then clone your fork of this repository.
2. Install dependencies using the `npm install` command.
3. Create the necessary .env file using the `.env.example` file as a reference
4. Start the web server using the `npm run local` command.
5. Visit <http://localhost:8080/> in your browser.

## Dependencies
- Node 5.10.x or above
- Express: ^4.17.1
- chalk: ^2.4.2
- cookie-parser: ^1.4.6
- ejs: ^2.6.2
- pg: ^8.5.0
- morgan: ^1.9.1
- sass: ^1.35.1
- dotenv: ^2.0.0

# Purpose
Goals of the project:
- Building a website from scratch
- Independence from instruction
- Learning how projects are planned
- Having a deadline (building under the gun)
- Working with a full stack
- Collaborating with teamates (GIT version control)
- Demo practice

# Credit
### Team Tasks
- User Stories
- ERD Model
- Visual Layout and Design

## Vince Emond
- Readme - [README.md](README.md)
- ERD Diagram - [Wiki_Map_ERD_v06.png](planning/Wiki_Map_ERD_v06.png)
- Database
  - Schema - [Schema Files](db/schema/)
  - Seeds - [Seed Files](db/seeds/)
  - Queries - [Queries](db/queries/)
- Map Points
  - Routes - [map_points_route.js](routes/map_points_route.js)
  - jQuery & AJAX - [map_points.js](public/scripts/map_points.js)

## Kent Gulka
- Drafted App Routes - [Routes](planning/user-stories.mduser-stories)

- Routes
  - Login - [login_route.js](routes/login_route.js)
  - Maps - [maps_route.js](routes/maps_route.js)
  - Favourites - [favourites_route.js](routes/favourites_route.js)
  - Contributors - [contributors_route.js](routes/contributors_route.js)
- jQuery & AJAX
  - Login - [login.js](public/scripts/login.js)
  - Maps - [maps.js](public/scripts/maps.js)
  - Favourites - [favourites.js](public/scripts/favourites.js)
  - Contributors - [contributors.js](public/scripts/contributors.js)

## Ethan Loewen
- Wireframe - [Map_Wiki_Wireframe_v01](planning/Map_Wiki_Wireframe_v01.png)
- HTML / Front End - [index.ejs](views/index.ejs)
- SCSS Styling
  - [layout.scss](styles/layout.scss)
  - [main.scss](styles/main.scss)
  - [map.scss](styles/map.scss)
  - [pins.scss](styles/pins.scss)
  - [sidebar.scss](styles/sidebar.scss)
- API Integration - [Leaflet Maps](https://leafletjs.com/)
- Map Object - [map_visuals.js](public/scripts/map_visuals.js)



