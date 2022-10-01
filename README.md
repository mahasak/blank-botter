Messenger Bot Starter Pack for Firebase Cloud Function
===
This project is a starter pack for quickly prototype messenger bot using Firebase cloud function

Instuction
===
## Environment Variable

* Assign new environment variable 
```
firebase functions:config:set <feature>.<config_name>=<value> --project <project-id>
```

* Using environment variable in local (emulator)
```
firebase functions:config:get --project <project-id> > functions/.runtimeconfig.json
```

## Running local emulator
- change directory to functions/ folder
```
npm serve
```
or
```
firebase emulators:start --only functions --project <project-id>
```