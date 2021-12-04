Frontend: Take Home Test



## Getting started on your machine

The first step is to fork this repo so that a fork exists on your own GitLab account. After you have forked the repo, clone your forked version down onto your machine.

Install the repo's dependencies:

`yarn`

Then start the local server:

`yarn start`

You should be able to see the app running on port `1234`!

Some boilerplate is setup for you. Remember to use the data schema provided. You can add more data if you want.

The parcel configuration has deliberate bugs in it which you can aatempt as brownie points otherwise you can choose any boilerplate or starter toolkit of your choice like CRA and Vue-CLI to get right to the meat of the problem.

Please remember to commit often so we can see how you're tracking...

Now Code Away!! 

## Deploy

Once done, publish a minified build of the project to any web publishing of your choice like [Surge](https://surge.sh/) or [Netlify](https://www.netlify.com/) etc, and share the public URL.
To generate the build, run:

    $ yarn build

And then upload the generated `dist` folder. For example,

    $ surge -d my-project-url.surge.sh -p dist

