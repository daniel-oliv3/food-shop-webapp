### Food Shop.

## Comandos para a criação do projeto.
- ng new food-shop-webapp

#### Roda o projeto.
- ng serve

## Bootstrap.
- Site - https://getbootstrap.com/

## Include via CDN

- #### CSS only.
- < link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css">

- #### JavaScript Bundle with Popper.
- < script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js">

- Colocar o link CDN no arquivo index.html

## Components.
- #### Component Navbar - Barra de navegação
- ng g c navbar

- #### Component Footer - Rodapé
- ng g c footer

- #### Component Pages Menu - Menu (Cardápio)
- ng g c menu

- #### Component Pages Home - Home (Inicio)
- ng g c home

- #### Component Pages About - Sobre
- ng g c about

- #### Component Pages Contact - Contato
- ng g c contact

## Routes, adicionando as rotas no arquivo - app-routing.module.ts.
- import { HomeComponent } from './pages/home/home.component';
- import { MenuComponent } from './pages/menu/menu.component';
- import { AboutComponent } from './pages/about/about.component';
- import { ContactComponent } from './pages/contact/contact.component';

### const routes: Routes = [
- {path: '', component:HomeComponent},
- {path: 'menu', component:MenuComponent},
- {path: 'about', component:AboutComponent},
- {path: 'contact', component:ContactComponent}
### ];

## Bootstrap Icons Via CDN
- < link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.3/font/bootstrap-icons.css">
- Colocar o link CDN no arquivo index.html

