# orghub/notification-service
Notification service for OrgHub app

> Deployed @ https://orghub-notification-service.now.sh/api/v1

Endpoints
---------
| Endpoint              | Method    |
|:--------------------- |:----------|
| /notifications/:org   | GET, PUT, POST, DELETE   |
| /payload              | POST      |



Commands
--------
- `npm run dev`: Start development live-reload server
- `npm run build`: Build project to /dist folder
- `npm start`: Build and run project from /dist folder as in production
- `npm test`: Run tests
- `npm run coverage`: Run test coverage using nyc, outputs report to /test/coverage
- `npm run coveralls`: Run test coverage using nyc & send report to coveralls (must have specified repo_token in .coveralls.yml)
- `npm run lint`: Run eslint


Docker Support
------
```sh
docker build -t orghub/notification-service .
docker run -p 8080:8080 orghub/notification-service
```

Publish to now
--------------
```sh
npm install now -g
now && now alias
# wait a bit..
# visit url
```

Author
------
* Olle Lauri Boström (ollebostr@gmail.com)


License
-------
Licensed under the MIT License.

