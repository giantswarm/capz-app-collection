[![CircleCI](https://dl.circleci.com/status-badge/img/gh/giantswarm/capz-app-collection/tree/master.svg?style=svg&circle-token=6262f4107cdd1ef7125a2c00e917599e31951c3e)](https://dl.circleci.com/status-badge/redirect/gh/giantswarm/capz-app-collection/tree/master)

# capz-app-collection

This is a template repository containing some basic files every repository
needs.

To use it just hit `Use this template` button or [this link][generate].

Things to do with your newly created repo:

1. Run`devctl replace -i "REPOSITORY_NAME" "$(basename $(git rev-parse
   --show-toplevel))" --ignore '.git/**' '**'`.
2. Run `devctl replace -i "template" "$(basename $(git rev-parse
   --show-toplevel))" --ignore '.git/**' '**'`.
3. Go to https://github.com/giantswarm/REPOSITORY_NAME/settings and make sure `Allow
   merge commits` box is unchecked and `Automatically delete head branches` box
   is checked.
4. Go to https://github.com/giantswarm/REPOSITORY_NAME/settings/access and add
   `giantswarm/bots` with `Write` access and `giantswarm/employees` with
   `Admin` access.
5. Add this repository to https://github.com/giantswarm/github.
6. Create quay.io docker repository if needed.

[generate]: https://github.com/giantswarm/template/generate
