# Proyecto Tools App

<div align="center">
 
![Next.js Badge](https://img.shields.io/badge/Next.js-000?logo=nextdotjs&logoColor=fff&style=for-the-badge)
![TypeScript Badge](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=for-the-badge)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

## Build-With:

-   prisma
-   jotai
-   cookies-next
-   tailwindcss
-   next-auth
-   bcryptjs

# Development

Pasos para levantar la app en desarrollo

1. Levantar la base de datos

```
docker compose up -d
```

2. Crear una copia de el .env.template a .env
3. Reemplazar las variables de entorno
4. Ejecutar el comando `npm install`
5. Ejecutar el comando `npm run dev`
6. Ejecutar estos comandos de prisma

```
    npx prisma migrate dev
    npx prisma generate
```

7. Ejecutar el SEED para localhost:3000/api/seed

## Nota: Usuario por defecto

**email** : demo@example.com
**contraseña** : 123456

# Prisma commnads

```
npx prisma init
npx prisma migrate dev
npx prisma generate
```

<p align="center">
<img width="1704" alt="Captura de pantalla 2023-12-30 a la(s) 09 48 59" src="https://github.com/dsagredo/project-tools-nextjs/assets/24228373/54b89a15-07ed-468f-9a8e-751a764f51ec">
<img width="1703" alt="Captura de pantalla 2023-12-30 a la(s) 09 49 31" src="https://github.com/dsagredo/project-tools-nextjs/assets/24228373/2562c720-e79f-46e6-b046-1b19c93fd987">
<img width="1704" alt="Captura de pantalla 2023-12-30 a la(s) 09 49 15" src="https://github.com/dsagredo/project-tools-nextjs/assets/24228373/b328c1b5-588b-405b-9189-01a052053eb1">
</p>

## Deploy on Vercel

https://project-tools-nextjs.vercel.app

