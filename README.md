# Stackbit DIY Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com) (v0.3.23)
.

The content of this site is managed by Sanity.io. Visit https://spectacular-steel-28bd0.sanity.studio/ to manage site content

# Developing Site Locally

1. Install [Node.js and npm](https://nodejs.org/en/)

1. Install npm dependencies:

        npm install

1. Navigate to the ["API Settings"](https://manage.sanity.io/projects/5mnnpyae/settings/api) page of this Sanity.io project. Then click "Add new token" and create new "write" token.

1. Run the following command to assign the created token to `SANITY_ACCESS_TOKEN` environment variable (replace `{sanity_write_token}` with the token):

        export SANITY_ACCESS_TOKEN={sanity_write_token}

1. [Optional] Install and run Sanity Studio locally: install sanity-cli `npm install -g @sanity/cli`, navigate to the `/studio` directory, and run `sanity install` and `sanity start`.
You may be required to login with the Sanity CLI.

1. Start the local development server:

        npm run develop

1. Browse to [http://localhost:3000/](http://localhost:3000/)

# Building Site

Follow the installation steps described in the "Running Your Site Locally".
Then run `npm run export` to build the site. The site will be generated into
the `out` folder.