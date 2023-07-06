
# Welcome 

Here you can find all the source code
involved in bringing [maixnor.github.io](https://maixnor.github.io) to you.

### Issues

If there is anything you would like to ask 
or change about the site just open an issue.
I am open for conversation.

### Tailwind

Since I am no longer using the CDN version of tailwind you 
will have to generate the CSS yourself.

This can be done by running tailwind.sh.
You may need to grab the correct latest artifact from [here](https://github.com/tailwindlabs/tailwindcss/releases/) 
if your platform is not Linux x64.

For development you can run 
`./tailwindcss -i input.css -o dist/bundle.css --watch`
to start a watch and continually regenerate the css. 

### Deployment

Deployment is handled by Github Actions.

Therefore the `dist/bundle.css` must be checked in so that it can be deployed.

