# tty.space

A small community on a small server.
This is the base configuration for the tty.space server.
As soon as changes hit master on this repo, it will be applied on the server.

## Creating a user

To setup a user, open a PR and add a `user.url` or a `user.keys` on the `files/users` folder.

For the `.url` file, the content should be a url with the public keys you want added for the user.

For the `.keys` file, the content should be a list of public keys you want added for the user.

After that file is on master, you should have your account ready to login, with the default password 'changeme'.
You will be prompted to update your password on first login.
