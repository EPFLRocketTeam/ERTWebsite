# ERTWebsite
EPFL Rocket Team Website

# How-to
When publishing commits, please write its ID as the Summary of the commit.
## HTML Edits
The ID is as follows :
**HTML-BB-CC-XXXX-YYYY**

BB is the page number and CC the sub-page number.
The odd sub-page numbers are for english pages and the even sub-page numbers are for French pages.

| Page N° | Sub-page N° | Page | html file |
|---------|-------------|------|-----------|
|**01** | **XX** | **Home** | |
| _01_ | _01_ | _Home_ | `index` |
| _01_ | _02_ | _Accueil_ | `indexfr` |
|**02** | **XX** | **About** |
| _02_ | _01_ | _About_ | `about` |
| _02_ | _02_ | _A propos_ | `aboutfr` |
| _02_ | _03_ | _The ERT_ | `about` |
| _02_ | _04_ | _L'ERT_ | `aboutfr` |
| _02_ | _05_ | _Spaceport America Cup_ | `about` |
| _02_ | _06_ | _La SA Cup_ | `aboutfr` |
| **03** | **XX** | **Lineup** |
| _03_ | _01_ | _Matterhorn (2018)_ | `lineup` |
| _03_ | _02_ | _Matterhorn (2018)_ | `lineupfr` |
| _03_ | _03_ | _Eiger (2019)_ | `lineup` |
| _03_ | _04_ | _Eiger (2019)_ | `lineupfr` |
| **04** | **XX** | **Projects** |
| _04_ | _01_ | _Matterhorn (2018)_ | `projects` |
| _04_ | _02_ | _Matterhorn (2018)_ | `projects_fr` |
| _04_ | _03_ | _Eiger (2019)_ | `projects` |
| _04_ | _04_ | _Eiger (2019)_ | `projects_fr` |
| **05** | **XX** | **Sponsors** | |
| _05_ | _01_ | _Sponsors_ | `sponsors` |
| _05_ | _02_ | _Sponsors_ | |
| **06** | **XX** | **News** | |
| _06_ | _01_ | _News_ | `news` |
| _06_ | _02_ | _Actualités_ | |
| **07** | **XX** | **Gallery** | |
| _07_ | _01_ | _Gallery_ | `gallery` |
| _07_ | _02_ | _Gallery_ | `galleryfr` |
| _07_ | _03_ | _Matterhorn (2018)_ | |
| _07_ | _04_ | _Matterhorn (2018)_ | |
| _07_ | _05_ | _Eiger (2019)_ | |
| _07_ | _06_ | _Eiger (2019)_ | |
| **08** | **XX** | **Contact** | |
| _08_ | _01_ | _Contact_ | `contact` |
| _08_ | _02_ | _Contact_ | `contact_fr` |
| **09** | **XX** | **Member page** |
| _09_ | _01_ | _Login_ | |
| _09_ | _02_ | _Login_ | |
| _09_ | _03_ | _Profile page_ | |
| _09_ | _04_ | _Profil_ | |
| _09_ | _05_ | _Home page_ | |
| _09_ | _06_ | _Accueil_ | |

XXXX is the task number.
YYYY is the commit number for the given task.

## CSS Edits
The ID is as follows :
**CSS-A-XXXX-YYYY**

A is the category :

| Code | Category |
|------|----------|
| G | General |
| L | Large screen |
| D | Desktop/Medium screen |
| S | Small screens |
| M | Mobile screens |

XXXX is the task number.
YYYY is the commit number for the given task.

# Tasks
## HTML
### Home page

| ID | Task |
|----|------|

### About page

| ID | Task |
|----|------|

### Lineup page

| ID | Task |
|----|------|
| `HTML-03-02-0001` | Add a link to each of the email adresses |
| `HTML-03-03-0001` | Add a link to each of the email adresses |
| `HTML-03-04-0001` | Add a link to each of the email adresses |
| `HTML-03-03-0002` | Put the Eiger lineup first (do not commit to master yet) |
| `HTML-03-04-0002` | Put the Eiger lineup first (do not commit to master yet) |
| `HTML-03-01-0002` | Create seperate sections for each of the projects |
| `HTML-03-02-0002` | Create seperate sections for each of the projects |
| `HTML-03-01-0003` | Update timeline to make it look like the AMZ one |
| `HTML-03-02-0003` | Update timeline to make it look like the AMZ one |

### Projects page

| ID | Task |
|----|------|
| `HTML-04-01-0001` | Create a seperate page for Matterhorn |
| `HTML-04-02-0001` | Create a seperate page for Matterhorn |
| `HTML-04-03-0001` | Create a seperate page for Eiger |
| `HTML-04-04-0001` | Create a seperate page for Eiger |
| `HTML-04-01-0002` | Add a link to the DR documents |
| `HTML-04-02-0002` | Add a link to the DR documents |

### Sponsors page

| ID | Task |
|----|------|
| `HTML-05-01-0001` | Add a link to each of the sponsors |
| `HTML-05-02-0001` | Create a french version of the sponsors page |
| `HTML-05-01-0002` | Adjust the background to have a coherent page |
| `HTML-05-02-0002` | Adjust the background to have a coherent page |


### News page

| ID | Task |
|----|------|
| `HTML-06-02-0001` | Create the french version of the news page |
| `HTML-06-01-0001` | Add the twitter feed |
| `HTML-06-02-0002` | Add the twitter feed |
| `HTML-06-01-0002` | Add the link to each of the newsletters |
| `HTML-06-02-0003` | Add the link to each of the newsletters |

### Gallery page

| ID | Task |
|----|------|
| `HTML-07-01-0001` | Have a best-of picture selection with a picture of Matterhorn as a link to the 2018 pictures and Eiger for the 2019 ones |
| `HTML-07-02-0001` | Have a best-of picture selection with a picture of Matterhorn as a link to the 2018 pictures and Eiger for the 2019 ones |
| `HTML-07-03-0001` | Create a 2018 picture gallery page |
| `HTML-07-04-0001` | Create a 2018 picture gallery page |
| `HTML-07-05-0001` | Create a 2019 picture gallery page |
| `HTML-07-06-0001` | Create a 2019 picture gallery page |

### Contact page

| ID | Task |
|----|------|
| `HTML-08-01-0001` | Compactify the text at the top of the page |
| `HTML-08-02-0001` | Compactify the text at the top of the page |
| `HTML-08-01-0002` | Give the fill-in boxes a white fill and rounded edges |
| `HTML-08-02-0002` | Give the fill-in boxes a white fill and rounded edges |

### Member page

| ID | Task |
|----|------|
| `HTML-09-01-0001` | Create a login page |
| `HTML-09-02-0001` | Create a login page |
| `HTML-09-03-0001` | Create a profile page |
| `HTML-09-04-0001` | Create a profile page |
| `HTML-09-05-0001` | Create a home page |
| `HTML-09-06-0001` | Create a home page |

## CSS

| ID | Task |
|----|------|
| `CSS-G-0001` | Find a nice/nicer font for the text |
| `CSS-G-0002` | Find better color matches for the text and the background |
| `CSS-G-0003` | Change the outline of the images upon hover : slow it down and change the color |
| `CSS-G-0004` | Find better color matches for the text and the background |

## Various developments

 - Host Slack, Mattermost or equivalent on a sub-domain
 - Have a file-sharing system for external persons

# Archived/Completed tasks
| ID | Task |
|----|------|
| `HTML-03-01-0001` | Add a link to each of the email adresses |