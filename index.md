# ElectroCRUD 2 (beta) ![GitHub Release Date](https://img.shields.io/github/release-date/garrylachman/ElectroCRUD.svg?style=for-the-badge)
### CRUD?
Create, Read, Update, and Delete (CRUD) are the four basic functions of persistent storage (Database).

### Why?
After a failed search for a basic admin panel that not involves writing code or installs web-based solutions, I come with ElectroCRUD idea.

### ElectroCRUD v1
The ElectroCRUD v1 was born in 2016, An Electron application that made it possible to create a friendly dashboard with data tables, search, widgets, filter & relations with few clicks without any experience in programming.

### ElectroCRUD v2
After a few years that the project was inactive, I decided to bring it an alive again. The codebase was build from scratch using Electron+Angular8. Many of the original functionality is still missing, but I'm working to cover backward compatibility.

## Download Binaries ![GitHub release](https://img.shields.io/github/release/garrylachman/ElectroCRUD.svg?style=for-the-badge)
We are in early beta !!!

* [Mac OSX (Release beta)](https://github.com/garrylachman/ElectroCRUD/releases/download/2.0.0-beta/ElectroCRUD-2.0.0-beta.dmg)
* [Linux (Release beta)](https://github.com/garrylachman/ElectroCRUD/releases/download/2.0.0-beta/ElectroCRUD.2.0.0-beta.AppImage)
* [Windows (Release beta)](https://github.com/garrylachman/ElectroCRUD/releases/download/2.0.0-beta/ElectroCRUD.2.0.0-beta.exe)

## Download Sources
[ElectroCRUD on GitHub](https://github.com/garrylachman/ElectroCRUD)

### Functionality
- [x] MySQL Support
- [x] SSH Tunnels
- [x] Accounts (represent a database)
  - [x] Add / Edit
  - [x] Test connection (ssh, db)
  - [ ] Export / Import
- [x] Views (represent a table) 
  - [x] Add new view & Edit view configurations
  - [x] Data table with pagination
  - [x] Search
  - [x] Permissions (C,R,U,D)
  - [x] Terminology
  - [x] Selection of columns to display or search by
  - [x] Add new record / Edit record
  - [x] Edit record
  - [ ] Export data in various formats like: csv, dump
- [ ] Views relations
  - [ ] One to one, One to many
  - [ ] Drill from view to view
- [ ] View widgets (display aggragated data in the view)
  - [ ] Add / Edit / Remove widgets
  - [ ] Aggregation functions (AVG, SUM, MIN, MAX)
  - [ ] Apply filters on widget data
- [ ] View filters (build where clauses to filter the data)
  - [ ] Add / Edit / Remove filter in each view
  - [ ] One click apply / unapply on view data
  - [ ] Simple & friendly interface to build where clauses
- [ ] Process manager (view running queries)
- [ ] Export / Import of all user accounts.

### Databases
- [x] MySQL/MariaDB
- [ ] MSSQL
- [ ] PostgreSQL
- [ ] Oracle

## Screenshots
<img src="https://i.imgur.com/gV1QHYK.png" width="49.5%" style="" /> <img width="49.5%" src="https://i.imgur.com/02DoYz1.png" style="" />
<img src="https://i.imgur.com/CotNi4G.png" style="" width="49.5%" /> <img width="49.5%" src="https://i.imgur.com/9MEQMbL.png" style="" />
<img src="https://i.imgur.com/QzlYVJu.png" style="" />


![GitHub All Releases](https://img.shields.io/github/downloads/garrylachman/ElectroCRUD/total.svg?style=for-the-badge) 
![GitHub package.json version](https://img.shields.io/github/package-json/v/garrylachman/ElectroCRUD.svg?style=for-the-badge)