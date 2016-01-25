# App Name

App description goes here.

## Quick Info

#### Dev

- URL: 
- DB: 
- Log: 

#### Staging

- URL: 
- DB: 
- Log: 
- Deploy:

#### Production

- URL: 
- DB: 
- Log:
- Deploy:

## Tasks

#### Installing & Running

- `npm install`
  - Installs modules
- `npm start`
  - Starts server and master process
- `npm run seed`
  - Destroys, creates, and seeds development database
- `npm run app`
  - Builds app
  - Runs a watch task
- `npm run dev`
  - Run seed
  - Builds app
  - Runs a watch task

#### Testing  
  
- `npm test`
  - Runs active Mocha test files
  - Fails after first test failure
- `npm run mocha`
  - Runs all Mocha test files
  - Does not stop after failures
- `npm run mocha -- <file>`
  - Run single test file (or subset of test files)
- `npm run mocha -- <file> --bail`
  - Run single test file, stop after first failure
  
#### Database Tasks
  
- `npm run importDB <file>`
  - Imports `<file>` to database
- `npm run seedDB`
  - Imports seed DB file to database
- `npm run dropDB`
  - Drops database
- `npm run reloadDB`
  - Executes `npm run dropDB && npm run seedDB`
- `npm run createDB`
  - Creates database
- `npm run deleteDB`
  - Deletes database
- `npm run exportDB <file>`
  - Exports database to `<file>`

#### Cron Jobs

**Cron Job #1**

- details
  
**Cron Job #2**

- details

#### Build System

- step #1
- step #2

## Architecture Notes

#### Section #1

- note #1
- note #2

#### Section #2

- note #1
- note #2

## User Roles

#### Role #1

#### Role #2

## API Endpoints

#### Endpoint Group #1

| Name        | Path                |
| ----------- | ------------------- |
| Endpoint #1 | `/path/to/endpoint` |
| Endpoint #2 | `/path/to/endpoint` |

**Details**

- Path: /link
- Request type: POST
- Content: form-encoded data

**Fields**

- field #1
- field #2

**Result**

- Content-Type: application/json
- Content:
	- prop #1
	- prop #2
	
## Setup	
	
#### App Dependencies

- dep #1
- dep #2

#### Dev Dependencies

- dep #1
- dep #2

#### Dev Install

1.
2.
3.

#### Dev Routine

1.
2.

#### Useful Dev Links

- http://a.com
- http://b.com

#### Staging Install

1.
2.
3.
4.
5.

#### Production Install

1.
2.
3.

## Database Details

For basic tasks, Tasks section above.

Other database actions:

#### Get Access

#### Create User

## Tests

| Name         | Details |
| ------------ | ------- |
| Test File #1 | details |
| Test File #2 | details |

To run tests, see Tasks section above. 

To deactivate tests, prefix the filename with an underscore.

## Credits

Main contributors:

- Contributor #1
- Contributor #2

(c) 2016 App Author