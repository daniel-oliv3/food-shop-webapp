### Food Shop

## Comandos para a criação do projeto.
- Component Navbar - Barra de navegação
- ng g c navbar

- Component Footer - Rodapé
- ng g c footer

- Component Pages Menu - Menu (Cardápio)
- ng g c menu

- Component Pages Home - Home (Inicio)
- ng g c home

- Component Pages About - Sobre
- ng g c about

- Component Pages Contact - Contato
- ng g c contact

## Routes
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


