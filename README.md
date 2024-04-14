# How to generate access token in git

Follow these steps

- Login to you git account
- Click on profile icon 
- Choose settings option
- On let side last option developer settings
- Click on Personal access tokens
- Choose Tokens (classic)
- Click on Generate new token
      
Direct access Link

- Click here [https://github.com/settings/tokens](https://github.com/settings/tokens)

> [!WARNING]
> Copy the code Before leave the page

### How to add the code for clone
``` php
git clone https://<access-token>@github.com/<username>/<repo-name>.git
```
#### Example

``` php

git clone https://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@github.com/shivam50091/stripe-concepts.git

```
In this example 
- This is token "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"
- This is username "shivam50091"
- This is Repo name "stripe-concepts.git"


# How to generate Fine-grained personal access tokens

Follow these steps

- Login to you git account
- Click on profile icon 
- Choose settings option
- On let side last option developer settings
- Click on Personal access tokens
- Fine-grained personal tokens
- Click on Generate new token

Direct access Link

- Click here [https://github.com/settings/tokens?type=beta](https://github.com/settings/tokens?type=beta)


> [!WARNING]  
> Copy the code Before leave the page

### How to add the code for clone
``` php
git clone https://username:access-token@github.com/username/repo-name.git
```

#### Example

``` php
git clone https://shivam50091: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@github.com/shivam50091/git-documentation.git
```

Or go to repo click on code and choose HTTPS
copy the url after https:// add user name then (:) key @

