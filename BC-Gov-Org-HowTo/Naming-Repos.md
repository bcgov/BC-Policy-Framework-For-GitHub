## Naming Repos

Naming a GitHub repo seems so simple - you'd just want something that is:

- Descriptive
- Readable
- Consistent
- Contextual
- Future-friendly
- Extensible
- Reusable
- Brief (short / succinct)

Although there is no wrong way to name a repo, some names are better than others. Here are some considerations for picking an awesome name for your GitHub repo.


### Follow Conventions
Following the naming conventions that are established for a particular project, code language or community is good place to start. But often Git projects are for websites where many languages are in play. For simplicity's sake, modeling website repos after the domain makes sense.

    http://domain.com ➔ domain.com.git
    http://sub.domain.com ➔ sub.domain.com.git

For other projects, let's keep the lowercase and dashes pattern:

    star-wars.git
    the-empire-strikes-back.git
    return-of-the-jedi.git

### What about CamelCase?
The problem with camel case is that there are often different interpretations of words - for example, checkinService vs checkInService. Also, it is difficult with auto-completion if you have many similarly named repos to have to constantly check if the person who created the repo you care about used a certain breakdown of the upper and lower cases. It's also best to avoid upper case, no one likes yelling.

### Be specific
You may find you have to differentiate between similar ideas later.

- Use wildlife-locator-rest-service instead of locator-service or wildlife-rest-service.
- Be consistent. 
- How do you want your repositories to be sorted/grouped?

Without favouring any particular naming choice, remember that a git repo can be cloned into any root directory of your choice:

    git clone https://github.com/user/repo.git myDir

Here repo.git would be cloned into the myDir directory.

So even if your naming convention for a public repo ended up to be slightly incorrect, it would still be possible to fix it on the client side.

That is why, in a distributed environment where any client can do whatever he/she wants, there isn't really a naming convention for Git repo.
(except to reserve "xxx.git" for bare form of the repo 'xxx')

### Avoid Organization Monikers
Once established, it's a simple task to change repo names, BUT it can have unintended consequences like breaking downstream links - so think about a name that can be stable over a long period of time.  Ministry, Department, Agency, Division, Branch and team names are subject to change so it’s best to avoid including them as part of repo names.  Putting “BC” in the name is fine to provide the context of the “Province of British Columbia” but let’s not start every repo that way, it makes sorting and searching a pain.
