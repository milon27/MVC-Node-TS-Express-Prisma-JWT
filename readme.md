## # Node Express Sequelize -MVC-setup

Set up MVC using Node, Express,Prisma (MySQL) , JWT and bcrypt.
___ 

>> Using Technology
 * NODE JS 
 * TypeScript
 * Express JS
 * Prisma(MySQL)
 * JWT+Http Only Cookie+bcryptJS(Auth)

>> How to contribute
___
* Put this comment on file where you will work
```javascript
/**
 * @design by your_git_username
 */
```
>> How to use
* Use following commad to clone the repo.

```
    $ git clone https://github.com/milon27/MVC-Node-TS-Express-Prisma-JWT .
    $ git checkout -b features_a
    $ npm install
    $ modify .env file 
    $ npm run dev (run by nodemon port 2727)
    $ npm start (run by node port 2727)
    
```


>> Folder Structure
___
 * routers
    * /middleware
        * AuthMid.ts
        * ErrorMid.ts
    * authRouter.ts
    * testRouter.ts
 * controllers
   * AuthController.ts
   * TestController.ts
 * models
   * ApiResponse.ts (response format)
 * utils
   * Define.ts (all constant value)
   * DB_Define.ts (all SQL+DB constant value)
   * Helper.ts (all helper functions)
 * server.ts
 * package.json
 * .env

># Deployments

>> scripts in package.json
```json
"scripts": {
    "build": "rm -r dist/* &&  tsc",
    "clean": "rm -r dist/*",
    "serve": "node dist/server.js",
    "p-init": "prisma init",
    "p-mg": "prisma migrate dev --name init && prisma generate",
    "p-generate": "prisma generate",
    "dev": "nodemon server.ts"
  },

```

>> how to deploy

```javascript
  //build the project
  npm run build
  //serve locally
  npm run serve 
  //serve in dev mode
  npm run dev
```



<br/><br/><br/><br/>
___

>> Developed By milon27
* site : https://milon27.web.app
* gmail: mdjahidulislammilon@gmail.com
* phone: +8801646735359
