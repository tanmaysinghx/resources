# Resources file for Angular, Microfrontend with Single-Spa, SpringBoot, IOS Development and CSS libraries 

# Angular

### Angular CLI

- npm install -g @angular/cli@15.1.1 (To install a particular angular version)
- ng generate new MyApp (To create a new angular application)
- ng generate component my-component (To generate a angular components)
- ng generate service services/my-service (To generate a angular components)
- ng generate module module-name (To generate a module)
- ng generate interceptor interceptor-name (To generate interceptor to edit curl headers)

### Angular Microfrontend Single-Spa creation

- ng new job-app-ui-profile --routing --prefix job-app-ui-profile
- cd job-app-ui-profile

- npm install @angular/material

- ng add single-spa-angular

- Edit file - app-routing.module.ts
1) Add providers: 
2) Add empty path: { path: '**', component: EmptyRouteComponent }
3) Change path: "customWebpackConfig": {
              "path": "./extra-webpack.config.js",
              "libraryName": "job-app-ui-header",
              "libraryTarget": "umd"
            },
4) Add environments file

### Angular Stying Libraries

#### Material UI
- npm install @angular/material
- https://material.angular.io/

#### Tailwind CSS
- npm install tailwindcss postcss autoprefixer
- npx tailwindcss init
- @import 'tailwindcss/base';
  @import 'tailwindcss/components';
  @import 'tailwindcss/utilities';

