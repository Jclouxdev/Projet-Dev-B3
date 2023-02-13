---
sidebar_position: 4
---

# /auth/sign-up

## POST : create()

```ts
create();
```

Create a new user.

**Properties required to create a User :**

```ts
@IsNotEmpty()  username: string;
@IsNotEmpty()  password: string;
@IsNotEmpty()  email: string;
```
