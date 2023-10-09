# Should I deploy today?

This action checks the website [shouldideploy.today](https://shouldideploy.today/) and stops deployments if the site tells us not to do so. 

## Clarification
We decided to maintain this action because we use it in our own projects. We are not affiliated with the website [shouldideploy.today](https://shouldideploy.today/). If you have any questions regarding the website please contact the maintainers of the website.

## Inputs

### `timezone`

**Required** The timezone which your product team is working in. Default `"UTC"`.

## Force deploy
If you want to force the build and skip the check you can add `force deploy` to your commit message. 

## Example usage

```
uses: actions/shouldideploy-action@v1
with:
  timezone: 'UTC'
```
