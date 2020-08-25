## TLC Api

# DevDen API

This API stores information on the user and a resource, resource being devposts. It allows users to register as users of the API and add, delete & edit posts.

## Important Links

- [DevDen Client Repo](https://github.com/TLC-Tender-Lovin-Code/TLC_client)
- [Deployed DevDen API]()
- [Deployed DevDen Client](https://tlc-tender-lovin-code.github.io/TLC_client/)
- [Project Checklist](https://docs.google.com/document/d/1IpbqtpYSixUEgInpalWcN8SgG26YpPCgs8_X65td73c/edit?usp=sharing)

## API URL

```js
  production: 'https://aqueous-atoll-85096.herokuapp.com',
  development: 'http://localhost:4741'
```

## API End Points

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/sign-up`             | `users#signup`    |
| POST   | `/sign-in`             | `users#signin`    |
| DELETE | `/sign-out`            | `users#signout`   |
| PATCH  | `/change-password`     | `users#changepw`  |
| GET    | `/devposts`            | `devposts#index`  |
| GET    | `/devpost/:id`            | `devposts#index`  |
| POST   | `/create-post`            | `devposts#create` |
| PATCH  | `/update-post/:id`        | `devposts#update` |
| DELETE | `/delete-post/:id`            | `devposts#delete`  |

All data returned from API actions is formatted as JSON.

## API Routes

```md
1. User routes
2. Devposts routes
```

## Resources & Attributes

Devposts will be my resources. Attributes can be seen in the ERD below

## API ERD

![alt-text](https://i.imgur.com/QDpDWWk.png "DevDen: ERD")

[Link to ERD](https://i.imgur.com/QDpDWWk.png)
