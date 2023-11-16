https://partners.shopify.com/3263765?

https://www.shopify.com/partners/blog/how-to-build-a-shopify-app#apps-into-shopify 
https://shopify.dev/docs/apps

polaris - components libary like ice component
@shopify/cli - is a command-line interface tool that helps you build Shopify apps. It quickly generates Shopify apps and generates app extensions. 

//you can use shopify app libary/tool(shopify Cli included as dependency) to create app follow below. 
//It provides a "platform"(libary package) to set up envin your local(with default dependencies) and connect your local code to shopify partner dev site thru cloudflare tunel
//then you can make code change in your local and test in provided url. 
//during the app creation you can choose to develop the app by using a dev template called remix.
//the remix dev template provide convience to create the app. e.g if you want to add a DB table, you will add the new table schema to schema.prisma.js, it will create the table for you.
//the template provide convinence like that in some other common usage as well.
//you can choose not use the template as well.
npm init @shopify/app@latest - A new app is created and Shopify CLI is installed along with all the dependencies that you need to build Shopify apps
cd project folder
npm run dev

//Another option is use shopify Cli directly without using @shopify/app@latest
