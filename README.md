# episto

## Configuration

### Database

For development, just fill out the correct information for `adapters_local_mongo` under `config/local.js`. In a production environment, set the `MONGO_HOST`, `MONGO_PORT`, `MONGO_USER`, `MONGO_PWD`, and `MONGO_DB` environment variables instead.

## Troubleshooting

* Run `$Env:GYP_MSVS_VERSION=2013` before running `npm i` on Windows if npm is returning errors that mention ` The build tools for Visual Studio 2010 (Platform Toolset = 'v100') cannot be found.`.