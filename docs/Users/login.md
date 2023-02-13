---
sidebar_position: 5
---

# /auth/login

## POST : login()

```
login()
```

Login as user or admin.

**Properties required to login a User :**

```ts
@IsNotEmpty()  password: string;
@IsNotEmpty()  email: string;
```
