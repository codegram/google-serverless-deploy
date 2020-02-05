# google-serverless-deploy

This is a workflow to deploy to Google Cloud using the Serverless framework.

## Usage

- Clone this repository
- Update `serverless.yml` with your desired project configuration
- Add your encrypted credentials in a `keyfile.json.gpg` file
- In your repository settings, add the `SECRET_PASSPHRASE` secret with the value of the passphrase used to encrypt your credentials

For detailed instructions, check [this blogpost](https://codegram.com/blog/a-github-actions-workflow-to-deploy-to-google-cloud-using-serverless-framework/)