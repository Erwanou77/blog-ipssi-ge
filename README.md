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
```

Page de connexion

```bash
/sign-in
```

Méthode **GET** user && **PUT** user

```bash
/api/user
```

Liste de tous les utilisateurs

```bash
/api/users
```

Récupération d'un utilisateur && modification d'un utilisateur && suppression d'un utilisateur (ADMIN)

```bash
/api/user/:id
```

get des post du user && post post

```bash
/api/post
```

get posts sur tous les posts avec tous les comments

```bash
/api/posts
```

get post && put post && delete post

```bash
/api/post/:id
```

get sur tous les comments

```bash
/api/comments
```

get comment && post comment && put comment && delete comment

```bash
/api/comment/:id
```
