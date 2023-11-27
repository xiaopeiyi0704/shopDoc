//shopify dev document
https://www.shopify.com/partners/blog/how-to-build-a-shopify-app#apps-into-shopify - content seems out of date based on the version they use in tutoria videos
https://www.shopify.com/partners/blog/how-to-build-a-shopify-app#polaris-getting-started - content seems out of date based on the version they use in tutoria videos
https://shopify.dev/docs
https://shopify.dev/docs/api
https://shopify.dev/docs/apps
https://shopify.dev/docs/api/admin-rest


//shopify partner account
https://partners.shopify.com/3263765

//shopfy dev tool and lib
polaris - components libary like ice component
shopify - like ice IDP
shopify/cli - is a command-line interface tool that helps you build Shopify apps. It quickly generates Shopify apps and generates app extensions. 


//you can use shopify app libary/tool(shopify Cli included as dependency) to create app follow below.  just like create-idp-app OR create-react-app
//It provides a "platform"(libary package) to set up env in your local(with default dependencies) and connect your local code to shopify partner dev site thru cloudflare tunel
//then you can make code change in your local and test in provided url. 
//during the app creation you can choose to develop the app by using a dev template called remix.
//the remix dev template provide convience to create the app. e.g if you want to add a DB table, you will add the new table schema to schema.prisma.js, it will create the table for you.
//the template provide convinence like that in some other common usage as well.
//you can choose not use the template as well.
npm init @shopify/app@latest - A new app is created and Shopify CLI is installed along with all the dependencies that you need to build Shopify apps
cd project folder
npm run dev


-------------------------------useful package/lib--------------------------------
//prisma
prisma // a node js ORM
npm run prisma migrate dev -- --name add-qrcode-table //if use prisma in local and after create table in file to execute "script"
npm run prisma studio // open prisma manager like php admin


//webhook
A webhook is an HTTP-based callback function that allows lightweight, event-driven communication between 2 application programming interfaces (APIs).


//remix
shopify aquired this company to help developer create shopify app/development convinently


//setup in local
// need node js version >= 18
// checkout the code - chatbit
// cd to the dir
// npm i
// npm run dev
