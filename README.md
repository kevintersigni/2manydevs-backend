# 2manydevs


Voici ma première app Strapi pour réaliser mon site perso.

Hybride entre blog, journal et portfolio, je me suis basé sur ce tuto --> [Build a blog with Next (React.js) and Strapi](https://strapi.io/blog/build-a-blog-with-next-react-js-strapi). J'ai donc utilisé [Next.js](https://nextjs.org/) pour le front hébergé chez [Vercel](https://vercel.com/) et [Strapi](https://strapi.io/) pour le CMS hébergé sur [Heroku](https://www.heroku.com/) avec l'add-on PostgreSQL pour la base de données. 
Le tuto était très incomplet et j'ai diggé un certain nombre d'informations. J'en ferais un tuto en français sur ce nouveau site dans un article dédié.

J'ai connecté le provider [Cloudinary](https://cloudinary.com/) pour stocker les images et j'ai ajouté un autre éditeur WYSIWYG pour remplacer le natif de Strapi : [Strapi CKEditor5 plugin](https://github.com/Roslovets-Inc/strapi-plugin-ckeditor5).
Pour rendre correctement le HTML avec [React markdown](https://github.com/remarkjs/react-markdown) j'ai utilisé les packages [rehype-raw](https://github.com/rehypejs/rehype-raw) et [rehype-sanitize](https://github.com/rehypejs/rehype-sanitize).

Côté design je n'ai pas utilisé un des starters Strapi mais plutôt un [template de blog](https://github.com/strapi/strapi-template-blog) contenant une [UI](https://getuikit.com/). Une V2 avec un design custom arrivera prochainement ;)

L'objectif pour moi à travers ce site est d'apprendre, de produire et d'apprendre en produisant !


## Demo

Lien du projet : <a href="https://2manydevs.com//" target="_blank">2manydevs</a>



Frontend 👉🏼   [par là](https://github.com/kevintersigni/2manydevs-frontend)



## Skills & packages
Strapi, PostgreSQL, Cloudinary, Node.


## Installation

Install my-project with yarn 👇🏼

#### Clone this repository:

`git clone https://github.com/kevintersigni/2manydevs-backend.git`

#### Install packages:

`yarn install`


#### Create a .env file at the root of the project and store the following environment variables:

`NEXT_PUBLIC_STRAPI_API_URL=the name of your server hosted on heroku`

On Heroku install the Postgres add-on
Then set these environment variables :

`CLOUDINARY-NAME=your credential`
`CLOUDINARY_KEY=your credential`
`CLOUDINARY_SECRET=your credential`
`MY_HEROKU_URL=the name of your server hosted on heroku`
`NODE_ENV=production`


#### When installation is complete, launch the project:

`yarn start`

## Roadmap

Pour améliorer ce projet voici ce que je prévois :

- nouvelle maquette
- ajout d'une page contact
- création d'un logo
- publication automatique des articles sur mon [Medium](https://medium.com/@kevin.tersigni)

