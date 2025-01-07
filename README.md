<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

<p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>

## Descripción

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Configuración del Proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/AngelCortesM/nest-backend.git
   cd nest-backend
   ```

2. Instala las dependencias:
   ```bash
   npm install
   npm install @nestjs/config
   ```

3. Configura las variables de entorno:
   - Copia el archivo `.env.template` y renómbralo a `.env`.
   - Modifica las variables de entorno según sea necesario.

## Ejecución del Proyecto

1. Inicia MongoDB (si no lo tienes instalado localmente, puedes usar Docker):
   ```bash
   docker-compose up -d
   ```

2. Ejecuta la aplicación en modo desarrollo:
   ```bash
   npm run start:dev
   ```

3. La aplicación estará disponible en `http://localhost:3000`.

## Despliegue

1. Compila el proyecto:
   ```bash
   npm run build
   ```

2. Ejecuta la aplicación en modo producción:
   ```bash
   npm run start:prod
   ```

## Recursos Adicionales

- [Documentación de NestJS](https://docs.nestjs.com)
- [Canal de Discord de NestJS](https://discord.gg/G7Qnnhy)
- [Cursos oficiales de NestJS](https://courses.nestjs.com)
- [NestJS Devtools](https://devtools.nestjs.com)
- [Soporte empresarial de NestJS](https://enterprise.nestjs.com)

## Licencia

Nest tiene licencia [MIT](https://github.com/nestjs/nest/blob/master/LICENSE).