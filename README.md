## first thing you should do is to create af file `.env` in the root of the project with this content

CONNECTION=YOUR_CONNECTION_STRING_TO_ATLAS

DB_NAME=semester_case

#SKIP_AUTHENTICATION=true

USE_USER_DB_FACADE_FOR_AUTHENTICATION=true

PORT=5555

DEBUG=game-project

## HINTS

Remember you can run individual typescript files using ts-node like this:

`ts-node -r dotenv/config ./src/PATH_TO_FILE`
