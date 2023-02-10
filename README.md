# IPSSI - Express

## Installation

Installation des dépendances

```bash
$ pnpm i
```

Mettre `DATABASE_URL` dans le fichier `.env`
Mettre `JWT_SECRET` dans le fichier `.env`

Lancement des migrations en dev

```bash
$ pnpm prisma migrate dev
```

## Développement

```bash
$ pnpm dev
```

Lancement de prisma

```bash
$ pnpm prisma studio
```

Page d'inscription

```bash
/sign-up

POST:
{
  "username": "username",
  "name": "name",
  "password": "password"
}
```

Page de connexion

```bash
/sign-in

POST:
{
  "username": "username",
  "password": "password"
}
```

Méthode **GET** user && **PUT** user

```bash
/api/user

PUT:
{
  "name": "name",
  "password": "password"
}
```

Liste de tous les utilisateurs

```bash
/api/users
```

Récupération d'un utilisateur && modification d'un utilisateur && suppression d'un utilisateur (ADMIN)

```bash
/api/user/:id

PUT:
{
  "name": "name",
  "password": "password"
}
```
Utilisation de la méthode get afin de récuperer les post de l'utilisateur

```bash
/api/post


POST:
{
  "title": "title",
  "content": "content"
}
```

Utilisation de la méthode get afin de récuperer tout les post de l'utilisateur

```bash
/api/posts

```

Utilisation de la méthode get pour post, put et delete 

```bash
/api/post/:id

PUT:
{
  "title": "title",
  "content": "content"
}
```

Utilisation de la méthode get afin de récuperer tout les commentaires de l'utilisateur

```bash
/api/comments
```

Utilisation de la méthode get afin de récuperer toutes les informations sur commentaires

```bash
/api/comment/:id

POST:
{
  "content": "content"
}
```
