# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
PS C:\Users\lisas> cd C:\Users\lisas\Downloads\Anythink-Market-czoed-main\Anythink-Market-czoed-main
PS C:\Users\lisas\Downloads\Anythink-Market-czoed-main\Anythink-Market-czoed-main> docker-compose up
[+] Running 10/10
 - mongodb-node Pulled                                                                                            47.2s
   - 675920708c8b Pull complete                                                                                    7.9s
   - 6f9c8c301e0f Pull complete                                                                                    7.9s
   - 73738965c4ce Pull complete                                                                                    8.2s
   - 7fd6635b9ddf Pull complete                                                                                    8.5s
   - 73a471eaa4ad Pull complete                                                                                    8.5s
   - bcf274af89b0 Pull complete                                                                                    8.6s
   - 04fc489f2a3b Pull complete                                                                                    8.7s
   - 6eff8a505292 Pull complete                                                                                   40.1s
   - a5ef4431fce7 Pull complete                                                                                   40.2s
[+] Building 54.2s (11/11) FINISHED
 => [anythink-market-czoed-main-anythink-backend-node internal] load build definition from Dockerfile              0.0s
 => => transferring dockerfile: 181B                                                                               0.0s
 => [anythink-market-czoed-main-anythink-frontend-react internal] load build definition from Dockerfile            0.0s
 => => transferring dockerfile: 50B                                                                                0.0s
 => [anythink-market-czoed-main-anythink-backend-node internal] load .dockerignore                                 0.1s
 => => transferring context: 2B                                                                                    0.0s
 => [anythink-market-czoed-main-anythink-frontend-react internal] load .dockerignore                               0.0s
 => => transferring context: 2B                                                                                    0.0s
 => [anythink-market-czoed-main-anythink-frontend-react internal] load metadata for docker.io/library/node:16      7.1s
 => [auth] library/node:pull token for registry-1.docker.io                                                        0.0s
 => [anythink-market-czoed-main-anythink-frontend-react 1/1] FROM docker.io/library/node:16@sha256:0c672d547405f  46.0s
 => => resolve docker.io/library/node:16@sha256:0c672d547405fe64808ea28b49c5772b1026f81b3b716ff44c10c96abf177d6a   0.0s
 => => sha256:ca988c6e7f4a41a18030a7adae34a5ea6f9faf7e4f84c8d886ce1afa0080d84a 2.21kB / 2.21kB                     0.0s
 => => sha256:c8af85aa302708c56365de9a85ab2733bfb24f3085e1f007327dd81931a1ccab 7.74kB / 7.74kB                     0.0s
 => => sha256:76dff75df4d9dbdf29a4459adaec745740bfb476cd915906e33eddd9cd94db93 50.44MB / 50.44MB                  18.9s
 => => sha256:0c672d547405fe64808ea28b49c5772b1026f81b3b716ff44c10c96abf177d6a 776B / 776B                         0.0s
 => => sha256:3e8c90a1c4bb422a88cc9ff532712db3c6a7a8cdc5030af2e60ec51947f2c8aa 7.86MB / 7.86MB                     1.4s
 => => sha256:b3662c1050803c4e17c1848dffe636eae5e6e5aafb8f1fffcf82248ccfef21c2 10.00MB / 10.00MB                   4.5s
 => => sha256:ad5dcb7dd59206e662084addf318ef296595c82800a9107e362439db4c158df9 51.84MB / 51.84MB                  13.8s
 => => sha256:fa57cc7ce3410dc0507beaaf475eb582c5ffccea2d603d2c024b77a69990aba2 192.51MB / 192.51MB                36.0s
 => => sha256:2d623c8b550da907caf76137bf8b96ef0c967ce72e592833d6297476190c91d0 4.20kB / 4.20kB                    15.8s
 => => sha256:56ed828b953cceaa532513ebb7d667d6360b14da2c28246c9c6244be05906750 34.86MB / 34.86MB                  20.7s
 => => sha256:09ff1abee05c67b5c7d66e3317ea90ac739daf2499ab847b4588736cdd453cd9 2.29MB / 2.29MB                    21.5s
 => => extracting sha256:76dff75df4d9dbdf29a4459adaec745740bfb476cd915906e33eddd9cd94db93                          2.5s
 => => sha256:b596abc1ac9615e1bf66e40b75c2d5bceeaf88d5d125c51c61977d6f023ce1d9 450B / 450B                        21.1s
 => => extracting sha256:3e8c90a1c4bb422a88cc9ff532712db3c6a7a8cdc5030af2e60ec51947f2c8aa                          0.3s
 => => extracting sha256:b3662c1050803c4e17c1848dffe636eae5e6e5aafb8f1fffcf82248ccfef21c2                          0.3s
 => => extracting sha256:ad5dcb7dd59206e662084addf318ef296595c82800a9107e362439db4c158df9                          2.9s
 => => extracting sha256:fa57cc7ce3410dc0507beaaf475eb582c5ffccea2d603d2c024b77a69990aba2                          7.6s
 => => extracting sha256:2d623c8b550da907caf76137bf8b96ef0c967ce72e592833d6297476190c91d0                          0.0s
 => => extracting sha256:56ed828b953cceaa532513ebb7d667d6360b14da2c28246c9c6244be05906750                          1.4s
 => => extracting sha256:09ff1abee05c67b5c7d66e3317ea90ac739daf2499ab847b4588736cdd453cd9                          0.1s
 => => extracting sha256:b596abc1ac9615e1bf66e40b75c2d5bceeaf88d5d125c51c61977d6f023ce1d9                          0.0s
 => [anythink-market-czoed-main-anythink-backend-node] https://raw.githubusercontent.com/vishnubob/wait-for-it/ma  0.5s
 => [anythink-market-czoed-main-anythink-backend-node] exporting to image                                          0.1s
 => => exporting layers                                                                                            0.0s
 => => writing image sha256:542e40066de66bbdf1e2656741055781249119dd5df7be0dd2b3a957b7f2809e                       0.0s
 => => naming to docker.io/library/anythink-market-czoed-main-anythink-frontend-react                              0.0s
 => => writing image sha256:98ff1bc2492227369f236d8047760a26196152d162bc76efb002d99123c9ea11                       0.0s
 => => naming to docker.io/library/anythink-market-czoed-main-anythink-backend-node                                0.0s
 => [anythink-market-czoed-main-anythink-backend-node 2/3] ADD https://raw.githubusercontent.com/vishnubob/wait-f  0.5s
 => [anythink-market-czoed-main-anythink-backend-node 3/3] RUN chmod +x /wait-for-it.sh                            0.4s
[+] Running 4/4
 - Network anythink-market-czoed-main_default  Created                                                             0.9s
 - Container anythink-frontend-react           Created                                                             0.2s
 - Container mongodb-node                      Created                                                             0.1s
 - Container anythink-backend-node             Created                                                             0.1s
Attaching to anythink-backend-node, anythink-frontend-react, mongodb-node
anythink-frontend-react  | yarn install v1.22.19
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.941+00:00"},"s":"I",  "c":"NETWORK",  "id":4915701, "ctx":"-","msg":"Initialized wire specification","attr":{"spec":{"incomingExternalClient":{"minWireVersion":0,"maxWireVersion":17},"incomingInternalClient":{"minWireVersion":0,"maxWireVersion":17},"outgoing":{"minWireVersion":6,"maxWireVersion":17},"isInternalClient":true}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.942+00:00"},"s":"I",  "c":"CONTROL",  "id":23285,   "ctx":"-","msg":"Automatically disabling TLS 1.0, to force-enable TLS 1.0 specify --sslDisabledProtocols 'none'"}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.944+00:00"},"s":"I",  "c":"NETWORK",  "id":4648601, "ctx":"main","msg":"Implicit TCP FastOpen unavailable. If TCP FastOpen is required, set tcpFastOpenServer, tcpFastOpenClient, and tcpFastOpenQueueSize."}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.945+00:00"},"s":"I",  "c":"REPL",     "id":5123008, "ctx":"main","msg":"Successfully registered PrimaryOnlyService","attr":{"service":"TenantMigrationDonorService","namespace":"config.tenantMigrationDonors"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.945+00:00"},"s":"I",  "c":"REPL",     "id":5123008, "ctx":"main","msg":"Successfully registered PrimaryOnlyService","attr":{"service":"TenantMigrationRecipientService","namespace":"config.tenantMigrationRecipients"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.945+00:00"},"s":"I",  "c":"REPL",     "id":5123008, "ctx":"main","msg":"Successfully registered PrimaryOnlyService","attr":{"service":"ShardSplitDonorService","namespace":"config.tenantSplitDonors"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.945+00:00"},"s":"I",  "c":"CONTROL",  "id":5945603, "ctx":"main","msg":"Multi threading initialized"}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.946+00:00"},"s":"I",  "c":"CONTROL",  "id":4615611, "ctx":"initandlisten","msg":"MongoDB starting","attr":{"pid":1,"port":27017,"dbPath":"/data/db","architecture":"64-bit","host":"cef45bea21bc"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.946+00:00"},"s":"I",  "c":"CONTROL",  "id":23403,   "ctx":"initandlisten","msg":"Build Info","attr":{"buildInfo":{"version":"6.0.1","gitVersion":"32f0f9c88dc44a2c8073a5bd47cf779d4bfdee6b","openSSLVersion":"OpenSSL 1.1.1f  31 Mar 2020","modules":[],"allocator":"tcmalloc","environment":{"distmod":"ubuntu2004","distarch":"x86_64","target_arch":"x86_64"}}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.946+00:00"},"s":"I",  "c":"CONTROL",  "id":51765,   "ctx":"initandlisten","msg":"Operating System","attr":{"os":{"name":"Ubuntu","version":"20.04"}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.946+00:00"},"s":"I",  "c":"CONTROL",  "id":21951,   "ctx":"initandlisten","msg":"Options set by command line","attr":{"options":{"net":{"bindIp":"*"}}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:07.951+00:00"},"s":"I",  "c":"STORAGE",  "id":22315,   "ctx":"initandlisten","msg":"Opening WiredTiger","attr":{"config":"create,cache_size=3413M,session_max=33000,eviction=(threads_min=4,threads_max=4),config_base=false,statistics=(fast),log=(enabled=true,remove=true,path=journal,compressor=snappy),builtin_extension_config=(zstd=(compression_level=6)),file_manager=(close_idle_time=600,close_scan_interval=10,close_handle_minimum=2000),statistics_log=(wait=0),json_output=(error,message),verbose=[recovery_progress:1,checkpoint_progress:1,compact_progress:1,backup:0,checkpoint:0,compact:0,evict:0,history_store:0,recovery:0,rts:0,salvage:0,tiered:0,timestamp:0,transaction:0,verify:0,log:0],"}}
anythink-frontend-react  | [1/5] Validating package.json...
anythink-frontend-react  | [2/5] Resolving packages...
anythink-backend-node    | yarn install v1.22.19
anythink-backend-node    | warning package.json: No license field
anythink-backend-node    | warning anythink-market-backend@1.0.0: No license field
anythink-backend-node    | [1/5] Validating package.json...
anythink-backend-node    | warning anythink-market-backend@1.0.0: No license field
anythink-backend-node    | [2/5] Resolving packages...
anythink-backend-node    | [3/5] Fetching packages...
anythink-frontend-react  | warning Resolution field "autoprefixer@10.4.5" is incompatible with requested version "autoprefixer@^10.4.7"
anythink-frontend-react  | [3/5] Fetching packages...
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.468+00:00"},"s":"I",  "c":"STORAGE",  "id":4795906, "ctx":"initandlisten","msg":"WiredTiger opened","attr":{"durationMillis":5517}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.468+00:00"},"s":"I",  "c":"RECOVERY", "id":23987,   "ctx":"initandlisten","msg":"WiredTiger recoveryTimestamp","attr":{"recoveryTimestamp":{"$timestamp":{"t":0,"i":0}}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.493+00:00"},"s":"I",  "c":"WT",       "id":4366408, "ctx":"initandlisten","msg":"No table logging settings modifications are required for existing WiredTiger tables","attr":{"loggingEnabled":true}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.516+00:00"},"s":"W",  "c":"CONTROL",  "id":22120,   "ctx":"initandlisten","msg":"Access control is not enabled for the database. Read and write access to data and configuration is unrestricted","tags":["startupWarnings"]}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.516+00:00"},"s":"W",  "c":"CONTROL",  "id":22178,   "ctx":"initandlisten","msg":"/sys/kernel/mm/transparent_hugepage/enabled is 'always'. We suggest setting it to 'never'","tags":["startupWarnings"]}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.516+00:00"},"s":"W",  "c":"CONTROL",  "id":5123300, "ctx":"initandlisten","msg":"vm.max_map_count is too low","attr":{"currentValue":65530,"recommendedMinimum":1677720,"maxConns":838860},"tags":["startupWarnings"]}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.516+00:00"},"s":"I",  "c":"STORAGE",  "id":20320,   "ctx":"initandlisten","msg":"createCollection","attr":{"namespace":"admin.system.version","uuidDisposition":"provided","uuid":{"uuid":{"$uuid":"4333a7cc-1dcc-4ccd-b09f-9f3152781761"}},"options":{"uuid":{"$uuid":"4333a7cc-1dcc-4ccd-b09f-9f3152781761"}}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.544+00:00"},"s":"I",  "c":"INDEX",    "id":20345,   "ctx":"initandlisten","msg":"Index build: done building","attr":{"buildUUID":null,"collectionUUID":{"uuid":{"$uuid":"4333a7cc-1dcc-4ccd-b09f-9f3152781761"}},"namespace":"admin.system.version","index":"_id_","ident":"index-1--8270775565785077576","collectionIdent":"collection-0--8270775565785077576","commitTimestamp":null}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.544+00:00"},"s":"I",  "c":"REPL",     "id":20459,   "ctx":"initandlisten","msg":"Setting featureCompatibilityVersion","attr":{"newVersion":"6.0"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.544+00:00"},"s":"I",  "c":"REPL",     "id":5853300, "ctx":"initandlisten","msg":"current featureCompatibilityVersion value","attr":{"featureCompatibilityVersion":"6.0","context":"setFCV"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.544+00:00"},"s":"I",  "c":"NETWORK",  "id":4915702, "ctx":"initandlisten","msg":"Updated wire specification","attr":{"oldSpec":{"incomingExternalClient":{"minWireVersion":0,"maxWireVersion":17},"incomingInternalClient":{"minWireVersion":0,"maxWireVersion":17},"outgoing":{"minWireVersion":6,"maxWireVersion":17},"isInternalClient":true},"newSpec":{"incomingExternalClient":{"minWireVersion":0,"maxWireVersion":17},"incomingInternalClient":{"minWireVersion":17,"maxWireVersion":17},"outgoing":{"minWireVersion":17,"maxWireVersion":17},"isInternalClient":true}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.544+00:00"},"s":"I",  "c":"NETWORK",  "id":4915702, "ctx":"initandlisten","msg":"Updated wire specification","attr":{"oldSpec":{"incomingExternalClient":{"minWireVersion":0,"maxWireVersion":17},"incomingInternalClient":{"minWireVersion":17,"maxWireVersion":17},"outgoing":{"minWireVersion":17,"maxWireVersion":17},"isInternalClient":true},"newSpec":{"incomingExternalClient":{"minWireVersion":0,"maxWireVersion":17},"incomingInternalClient":{"minWireVersion":17,"maxWireVersion":17},"outgoing":{"minWireVersion":17,"maxWireVersion":17},"isInternalClient":true}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.544+00:00"},"s":"I",  "c":"REPL",     "id":5853300, "ctx":"initandlisten","msg":"current featureCompatibilityVersion value","attr":{"featureCompatibilityVersion":"6.0","context":"startup"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.548+00:00"},"s":"I",  "c":"STORAGE",  "id":5071100, "ctx":"initandlisten","msg":"Clearing temp directory"}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.549+00:00"},"s":"I",  "c":"CONTROL",  "id":20536,   "ctx":"initandlisten","msg":"Flow Control is enabled on this deployment"}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.551+00:00"},"s":"I",  "c":"FTDC",     "id":20625,   "ctx":"initandlisten","msg":"Initializing full-time diagnostic data capture","attr":{"dataDirectory":"/data/db/diagnostic.data"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.553+00:00"},"s":"I",  "c":"STORAGE",  "id":20320,   "ctx":"initandlisten","msg":"createCollection","attr":{"namespace":"local.startup_log","uuidDisposition":"generated","uuid":{"uuid":{"$uuid":"75caef5f-b9f9-495c-ac0b-fca701ad2716"}},"options":{"capped":true,"size":10485760}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.579+00:00"},"s":"I",  "c":"INDEX",    "id":20345,   "ctx":"initandlisten","msg":"Index build: done building","attr":{"buildUUID":null,"collectionUUID":{"uuid":{"$uuid":"75caef5f-b9f9-495c-ac0b-fca701ad2716"}},"namespace":"local.startup_log","index":"_id_","ident":"index-3--8270775565785077576","collectionIdent":"collection-2--8270775565785077576","commitTimestamp":null}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.580+00:00"},"s":"I",  "c":"REPL",     "id":6015317, "ctx":"initandlisten","msg":"Setting new configuration state","attr":{"newState":"ConfigReplicationDisabled","oldState":"ConfigPreStart"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.580+00:00"},"s":"I",  "c":"STORAGE",  "id":22262,   "ctx":"initandlisten","msg":"Timestamp monitor starting"}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.582+00:00"},"s":"I",  "c":"NETWORK",  "id":23015,   "ctx":"listener","msg":"Listening on","attr":{"address":"/tmp/mongodb-27017.sock"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.582+00:00"},"s":"I",  "c":"CONTROL",  "id":20712,   "ctx":"LogicalSessionCacheReap","msg":"Sessions collection is not set up; waiting until next sessions reap interval","attr":{"error":"NamespaceNotFound: config.system.sessions does not exist"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.582+00:00"},"s":"I",  "c":"NETWORK",  "id":23015,   "ctx":"listener","msg":"Listening on","attr":{"address":"0.0.0.0"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.582+00:00"},"s":"I",  "c":"NETWORK",  "id":23016,   "ctx":"listener","msg":"Waiting for connections","attr":{"port":27017,"ssl":"off"}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.582+00:00"},"s":"I",  "c":"STORAGE",  "id":20320,   "ctx":"LogicalSessionCacheRefresh","msg":"createCollection","attr":{"namespace":"config.system.sessions","uuidDisposition":"generated","uuid":{"uuid":{"$uuid":"3e1c37f5-acd0-4504-b183-4dca20766d94"}},"options":{}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.623+00:00"},"s":"I",  "c":"INDEX",    "id":20345,   "ctx":"LogicalSessionCacheRefresh","msg":"Index build: done building","attr":{"buildUUID":null,"collectionUUID":{"uuid":{"$uuid":"3e1c37f5-acd0-4504-b183-4dca20766d94"}},"namespace":"config.system.sessions","index":"_id_","ident":"index-5--8270775565785077576","collectionIdent":"collection-4--8270775565785077576","commitTimestamp":null}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:13.623+00:00"},"s":"I",  "c":"INDEX",    "id":20345,   "ctx":"LogicalSessionCacheRefresh","msg":"Index build: done building","attr":{"buildUUID":null,"collectionUUID":{"uuid":{"$uuid":"3e1c37f5-acd0-4504-b183-4dca20766d94"}},"namespace":"config.system.sessions","index":"lsidTTLIndex","ident":"index-6--8270775565785077576","collectionIdent":"collection-4--8270775565785077576","commitTimestamp":null}}
anythink-backend-node    | [4/5] Linking dependencies...
anythink-backend-node    | warning " > mongoose-unique-validator@3.0.0" has incorrect peer dependency "mongoose@^6.0.0".
anythink-backend-node    | [5/5] Building fresh packages...
anythink-backend-node    | Done in 18.97s.
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:28.226+00:00"},"s":"I",  "c":"NETWORK",  "id":22943,   "ctx":"listener","msg":"Connection accepted","attr":{"remote":"172.20.0.4:55590","uuid":"72bdca17-f66e-4df1-98ba-007903973540","connectionId":1,"connectionCount":1}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:28.226+00:00"},"s":"I",  "c":"NETWORK",  "id":22944,   "ctx":"conn1","msg":"Connection ended","attr":{"remote":"172.20.0.4:55590","uuid":"72bdca17-f66e-4df1-98ba-007903973540","connectionId":1,"connectionCount":0}}
anythink-backend-node    | yarn run v1.22.19
anythink-backend-node    | warning package.json: No license field
anythink-backend-node    | $ nodemon ./app.js
anythink-backend-node    | [nodemon] 1.19.4
anythink-backend-node    | [nodemon] to restart at any time, enter `rs`
anythink-backend-node    | [nodemon] watching dir(s): *.*
anythink-backend-node    | [nodemon] watching extensions: js,mjs,json
anythink-backend-node    | [nodemon] starting `node ./app.js`
anythink-backend-node    | (node:84) DeprecationWarning: current URL string parser is deprecated, and will be removed in a future version. To use the new parser, pass option { useNewUrlParser: true } to MongoClient.connect.
anythink-backend-node    | (Use `node --trace-deprecation ...` to show where the warning was created)
anythink-backend-node    | (node:84) [MONGODB DRIVER] Warning: Current Server Discovery and Monitoring engine is deprecated, and will be removed in a future version. To use the new Server Discover and Monitoring engine, pass option { useUnifiedTopology: true } to the MongoClient constructor.
anythink-backend-node    | Listening on port 3000
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.360+00:00"},"s":"I",  "c":"NETWORK",  "id":22943,   "ctx":"listener","msg":"Connection accepted","attr":{"remote":"172.20.0.4:55592","uuid":"9bda57ee-64e6-4a69-b1a0-512bc7ba01cd","connectionId":2,"connectionCount":1}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.367+00:00"},"s":"I",  "c":"NETWORK",  "id":51800,   "ctx":"conn2","msg":"client metadata","attr":{"remote":"172.20.0.4:55592","client":"conn2","doc":{"driver":{"name":"nodejs","version":"3.6.6"},"os":{"type":"Linux","name":"linux","architecture":"x64","version":"5.10.16.3-microsoft-standard-WSL2"},"platform":"'Node.js v16.17.0, LE (legacy)"}}}
anythink-backend-node    | Mongoose: users.ensureIndex({ username: 1 }, { unique: true, background: true })
anythink-backend-node    | Mongoose: items.ensureIndex({ slug: 1 }, { unique: true, background: true })
anythink-backend-node    | (node:84) DeprecationWarning: collection.ensureIndex is deprecated. Use createIndexes instead.
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.387+00:00"},"s":"I",  "c":"NETWORK",  "id":22943,   "ctx":"listener","msg":"Connection accepted","attr":{"remote":"172.20.0.4:55594","uuid":"7b338205-d5c2-43c9-b728-1fba4f270722","connectionId":3,"connectionCount":2}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.388+00:00"},"s":"I",  "c":"NETWORK",  "id":51800,   "ctx":"conn3","msg":"client metadata","attr":{"remote":"172.20.0.4:55594","client":"conn3","doc":{"driver":{"name":"nodejs","version":"3.6.6"},"os":{"type":"Linux","name":"linux","architecture":"x64","version":"5.10.16.3-microsoft-standard-WSL2"},"platform":"'Node.js v16.17.0, LE (legacy)"}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.389+00:00"},"s":"I",  "c":"STORAGE",  "id":20320,   "ctx":"conn3","msg":"createCollection","attr":{"namespace":"anythink-market.users","uuidDisposition":"generated","uuid":{"uuid":{"$uuid":"4f6fc36d-c86e-4580-b70c-1bb7d11af2dc"}},"options":{}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.391+00:00"},"s":"I",  "c":"STORAGE",  "id":20320,   "ctx":"conn2","msg":"createCollection","attr":{"namespace":"anythink-market.items","uuidDisposition":"generated","uuid":{"uuid":{"$uuid":"5d96d55c-5360-4051-933b-ff0778dbbccc"}},"options":{}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.439+00:00"},"s":"I",  "c":"INDEX",    "id":20345,   "ctx":"conn3","msg":"Index build: done building","attr":{"buildUUID":null,"collectionUUID":{"uuid":{"$uuid":"4f6fc36d-c86e-4580-b70c-1bb7d11af2dc"}},"namespace":"anythink-market.users","index":"_id_","ident":"index-9--8270775565785077576","collectionIdent":"collection-7--8270775565785077576","commitTimestamp":null}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.439+00:00"},"s":"I",  "c":"INDEX",    "id":20345,   "ctx":"conn3","msg":"Index build: done building","attr":{"buildUUID":null,"collectionUUID":{"uuid":{"$uuid":"4f6fc36d-c86e-4580-b70c-1bb7d11af2dc"}},"namespace":"anythink-market.users","index":"username_1","ident":"index-11--8270775565785077576","collectionIdent":"collection-7--8270775565785077576","commitTimestamp":null}}
anythink-backend-node    | Mongoose: users.ensureIndex({ email: 1 }, { unique: true, background: true })
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.444+00:00"},"s":"I",  "c":"INDEX",    "id":20438,   "ctx":"conn3","msg":"Index build: registering","attr":{"buildUUID":{"uuid":{"$uuid":"32240f13-4787-475e-a64a-fbe5cfb60ad4"}},"namespace":"anythink-market.users","collectionUUID":{"uuid":{"$uuid":"4f6fc36d-c86e-4580-b70c-1bb7d11af2dc"}},"indexes":1,"firstIndex":{"name":"email_1"},"command":{"createIndexes":"users","v":2,"indexes":[{"name":"email_1","key":{"email":1},"unique":true,"background":true}],"ignoreUnknownIndexOptions":false}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.449+00:00"},"s":"I",  "c":"INDEX",    "id":20345,   "ctx":"conn2","msg":"Index build: done building","attr":{"buildUUID":null,"collectionUUID":{"uuid":{"$uuid":"5d96d55c-5360-4051-933b-ff0778dbbccc"}},"namespace":"anythink-market.items","index":"_id_","ident":"index-10--8270775565785077576","collectionIdent":"collection-8--8270775565785077576","commitTimestamp":null}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.449+00:00"},"s":"I",  "c":"INDEX",    "id":20345,   "ctx":"conn2","msg":"Index build: done building","attr":{"buildUUID":null,"collectionUUID":{"uuid":{"$uuid":"5d96d55c-5360-4051-933b-ff0778dbbccc"}},"namespace":"anythink-market.items","index":"slug_1","ident":"index-12--8270775565785077576","collectionIdent":"collection-8--8270775565785077576","commitTimestamp":null}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.463+00:00"},"s":"I",  "c":"INDEX",    "id":20345,   "ctx":"conn3","msg":"Index build: done building","attr":{"buildUUID":null,"collectionUUID":{"uuid":{"$uuid":"4f6fc36d-c86e-4580-b70c-1bb7d11af2dc"}},"namespace":"anythink-market.users","index":"email_1","ident":"index-13--8270775565785077576","collectionIdent":"collection-7--8270775565785077576","commitTimestamp":null}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.463+00:00"},"s":"I",  "c":"INDEX",    "id":20440,   "ctx":"conn3","msg":"Index build: waiting for index build to complete","attr":{"buildUUID":{"uuid":{"$uuid":"32240f13-4787-475e-a64a-fbe5cfb60ad4"}},"deadline":{"$date":{"$numberLong":"9223372036854775807"}}}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:23:29.463+00:00"},"s":"I",  "c":"INDEX",    "id":20447,   "ctx":"conn3","msg":"Index build: completed","attr":{"buildUUID":{"uuid":{"$uuid":"32240f13-4787-475e-a64a-fbe5cfb60ad4"}}}}
anythink-backend-node    | (node:84) [DEP0066] DeprecationWarning: OutgoingMessage.prototype._headers is deprecated
anythink-backend-node    | GET /api/ping 200 1593.723 ms - 60
anythink-frontend-react  | [4/5] Linking dependencies...
anythink-frontend-react  | warning " > bootstrap@4.6.1" has unmet peer dependency "popper.js@^1.16.1".
anythink-frontend-react  | warning " > react-redux@5.1.2" has incorrect peer dependency "react@^0.14.0 || ^15.0.0-0 || ^16.0.0-0".
anythink-frontend-react  | warning " > eslint-config-prettier@8.3.0" has unmet peer dependency "eslint@>=7.0.0".
anythink-frontend-react  | warning " > eslint-plugin-react@7.27.1" has unmet peer dependency "eslint@^3 || ^4 || ^5 || ^6 || ^7 || ^8".
anythink-frontend-react  | [5/5] Building fresh packages...
anythink-frontend-react  | success Saved lockfile.
anythink-frontend-react  | Done in 81.77s.
anythink-frontend-react  | yarn run v1.22.19
anythink-frontend-react  | $ REACT_APP_WILCO_ID=${WILCO_ID:-"$(cat ../.wilco)"} react-scripts start
anythink-frontend-react  | (node:83) [DEP_WEBPACK_DEV_SERVER_ON_AFTER_SETUP_MIDDLEWARE] DeprecationWarning: 'onAfterSetupMiddleware' option is deprecated. Please use the 'setupMiddlewares' option.
anythink-frontend-react  | (Use `node --trace-deprecation ...` to show where the warning was created)
anythink-frontend-react  | (node:83) [DEP_WEBPACK_DEV_SERVER_ON_BEFORE_SETUP_MIDDLEWARE] DeprecationWarning: 'onBeforeSetupMiddleware' option is deprecated. Please use the 'setupMiddlewares' option.
anythink-frontend-react  | Starting the development server...
anythink-frontend-react  |
anythink-frontend-react  | Compiled successfully!
anythink-frontend-react  |
anythink-frontend-react  | You can now view anythink-market-front in the browser.
anythink-frontend-react  |
anythink-frontend-react  |   Local:            http://localhost:3001
anythink-frontend-react  |   On Your Network:  http://172.20.0.2:3001
anythink-frontend-react  |
anythink-frontend-react  | Note that the development build is not optimized.
anythink-frontend-react  | To create a production build, use yarn build.
anythink-frontend-react  |
anythink-frontend-react  | webpack compiled successfully
anythink-backend-node    | Mongoose: users.countDocuments({ email: 'lisasouza4345@gmail.com' }, {})
anythink-backend-node    | Mongoose: users.countDocuments({ _id: ObjectId("6317586c80bddb00541e787b") }, {})
anythink-backend-node    | POST /api/users 422 75.772 ms - 36
anythink-backend-node    | Mongoose: users.countDocuments({ email: 'lisasouza4345@gmail.com' }, {})
anythink-backend-node    | Mongoose: users.countDocuments({ _id: ObjectId("6317587180bddb00541e787c") }, {})
anythink-backend-node    | POST /api/users 422 56.364 ms - 36
anythink-backend-node    | Mongoose: users.countDocuments({ username: 'lizapizza' }, {})
anythink-backend-node    | Mongoose: users.countDocuments({ email: 'lisasouza4345@gmail.com' }, {})
anythink-backend-node    | Mongoose: users.countDocuments({ _id: ObjectId("6317587680bddb00541e787d") }, {})
mongodb-node             | {"t":{"$date":"2022-09-06T14:25:58.303+00:00"},"s":"I",  "c":"NETWORK",  "id":22943,   "ctx":"listener","msg":"Connection accepted","attr":{"remote":"172.20.0.4:55662","uuid":"24944588-c993-4be1-8cb3-3198a747a9a0","connectionId":4,"connectionCount":3}}
mongodb-node             | {"t":{"$date":"2022-09-06T14:25:58.303+00:00"},"s":"I",  "c":"NETWORK",  "id":51800,   "ctx":"conn4","msg":"client metadata","attr":{"remote":"172.20.0.4:55662","client":"conn4","doc":{"driver":{"name":"nodejs","version":"3.6.6"},"os":{"type":"Linux","name":"linux","architecture":"x64","version":"5.10.16.3-microsoft-standard-WSL2"},"platform":"'Node.js v16.17.0, LE (legacy)"}}}
anythink-backend-node    | Mongoose: users.insertOne({ role: 'user', favorites: [], following: [], _id: ObjectId("6317587680bddb00541e787d"), username: 'lizapizza', email: 'lisasouza4345@gmail.com', salt: 'fe56555a933351986503a96fe825201d', hash: 'fbf72b86c7d7b0ae07bc67780863b25e2d3a3bbf1ebf881ccfe0e1b487aa6707629cb599145b1dd94f9cac53d8ad119fd1acf11d629e344ee98201691708e5e0a8793e5de3612eb437fa692cd40ffc2520a4b80c5f7a75ef34d0eb303a14e611464882a1a99926638a8c4dade4c853f03920b8848728144c9e40bc872a66b3d2198843da262c5ada2f31239d1706a84139d101e61b0c1dd079030b6e6db3c8be8cca95699e8566c08ba28197f0356588545e2f204cb6309538670b6b7249e14b1ec63cd6b01113a21c8f1e739ee0202907334cd488c7d828dbdc579b6435bbbfc28c7e81d4816d97eb86ec43e187af7a314ecd441ace551488284dd8c19728a65ce4fd4482a6730b7f5d91b2b775244fff79a8bda77f6c89c9171f5d9db8a60cfce445ffe9c00b9d3697b53a73d8e82d53caf48da095c0a458e8c1180490aa6bf20d448d3baac20933b96a8d738314722f3b641c3dc631afd5fa36e27d669c92955c5cbaa588c9336c168a66cf121417cb3a8b3a8103d34bca50d0f9a1420278e30b7eab615a4659b608f7ee5156ae817787558f2a85e56634ab16a0460b6764073caa62edb35f5cdc9f9b288b742768f96a4bdb7b857a8d6bc29e98ecae8626b8e28974a197e821356848926d755302791197fc2d6d82529e3092bd9e85ec940e4e7a61dc8eddb1b52331f7ed2297e1b6193ae5ff4f94ddef66fa4694320339', createdAt: new Date("Tue, 06 Sep 2022 14:25:58 GMT"), updatedAt: new Date("Tue, 06 Sep 2022 14:25:58 GMT"), __v: 0}, { session: null })
anythink-backend-node    | POST /api/users 200 68.869 ms - 293
anythink-backend-node    | Mongoose: users.findOne({ username: 'lizapizza' }, { projection: {} })
anythink-backend-node    | Mongoose: users.findOne({ _id: ObjectId("6317587680bddb00541e787d") }, { projection: {} })
anythink-backend-node    | Mongoose: users.findOne({ username: 'lizapizza' }, { projection: {} })
anythink-backend-node    | GET /api/profiles/lizapizza 200 22.047 ms - 122
anythink-backend-node    | Mongoose: items.find({ seller: ObjectId("6317587680bddb00541e787d") }, { limit: 500, skip: 0, sort: { createdAt: -1 }, projection: {} })
anythink-backend-node    | Mongoose: items.count({ seller: ObjectId("6317587680bddb00541e787d") }, {})
anythink-backend-node    | Mongoose: users.findOne({ _id: ObjectId("6317587680bddb00541e787d") }, { projection: {} })
anythink-backend-node    | (node:84) DeprecationWarning: collection.count is deprecated, and will be removed in a future version. Use Collection.countDocuments or Collection.estimatedDocumentCount instead
anythink-backend-node    | GET /api/items?seller=lizapizza&limit=500&offset=0 200 24.341 ms - 27
