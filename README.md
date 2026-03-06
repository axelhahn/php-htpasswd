# php-htpasswd

This PHP 8 class provides an easy way to manage htpasswd files.

After setting a **.htpasswd** file you can

- add - a user and password
- exists - check if a given user exists
- list - list all uses
- remove - a user
- update - a user and password - optional after verifying the current password
- verify - a password of an existing user

There is a 2nd class to handle **.htgoups** file too. It can handle goups:

- add
- rename
- delete groups
- list all groups or members

... and memberships

- userAdd
- userRemove

👤 Axel Hahn \
📄 Source: <https://github.com/axelhahn/php-htpasswd/> \
📜 Licence: GNU GPL 3 \
📗 Docs: <https://www.axel-hahn.de/docs/php-htpasswd/>

---

## Related projects

### Htman

I built a cli tool on top: **htman**. It can manage htpasswd and htgroups files. 

You can run it if you have php installed as a single file or for Linux 64 bit you can download the binary. [Releases](https://github.com/axelhahn/ht-manager/releases/latest).

📄 Source: <https://github.com/axelhahn/ht-manager> \
📜 Licence: GNU GPL 3

![Screenshot](docs/images/screenshot-htman.png)

