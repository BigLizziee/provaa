cd api
npm i prisma -g
npm init -y
npm i express cors dotenv
    prisma init --datasource-provider mysql
    prisma migrate dev --name init
