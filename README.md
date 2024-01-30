# Resources file for Angular, Microfrontend with Single-Spa, SpringBoot, IOS Development, AWS DevOPS and CSS libraries 

# Angular

### Angular CLI

- npm install -g @angular/cli@15.1.1 (To install a particular angular version)
- ng generate new MyApp (To create a new angular application)
- ng generate component my-component (To generate a angular components)
- ng generate service services/my-service (To generate a angular components)
- ng generate module module-name (To generate a module)
- ng generate interceptor interceptor-name (To generate interceptor to edit curl headers)
- ng generate guard auth (To generate auth guard)

### Angular Microfrontend Single-Spa creation

- https://single-spa.js.org/docs/ecosystem-angular/#angular-15
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
- https://tailwindcss.com/

#### Bootstrap CSS
- ng add ngx-bootstrap
- https://valor-software.com/ngx-bootstrap

#### NG ZORRO CSS
- npm install -g @angular/cli
- https://ng.ant.design/docs/introduce/en

#### TW Elements CSS
- npm install tw-elements
- https://tw-elements.com/docs/standard/getting-started/quick-start/

#### Prime Faces CSS
- https://primefaces.org/sakai-ng/#/documentation

### Springboot Commands
- mvn clean compile (removes target folder)
- mvn package (creates jar)
- mvn spring-boot:run (to run application)

### API Endpoints open-sources
- https://freeapi.miniprojectideas.com/index.html

- ### Open-sources contributions
- dummy

