# Blank Jekyll Template

This is a no-theme barebones Jekyll template that is used for HTML templating and that only. Intended for use with the UTS WebSys Web Assignment.

## Edstem Integration

If your Edstem workspace for your project does not support remote Git, you can run `./scripts/upload.sh` to automatically upload everything in `./_site` to the workspace.

To do this you will need to have the environment variables `ED_API_TOKEN` and `ED_WORKSPACE_ID` set.

The `ED_API_TOKEN` can be obtained from [https://edstem.org/au/settings/api-tokens].

The `ED_WORKSPACE_ID` can be obtained by opening up the inspect element page in your browser while you have an lesson's workspace open, and then uploading a file to that workspace. You will see a request to an endpoint that ends in `upload`, the request body will will contain a `wid` field, this is your `ED_WORKSPACE_ID`.