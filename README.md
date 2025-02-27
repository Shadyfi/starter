# Shadyfi Starter Kit

Click on `Use this template` to copy the Shadyfi starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development



```
npm i -g shadyfi
```

Run the following command at the root of your documentation (where docs.json is)

```
shadyfi dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Shadyfi dev isn't running - Run `shadyfi install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.json`
