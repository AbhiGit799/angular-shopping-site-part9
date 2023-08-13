# angular-shopping-site-part9

Hi,

This is a simple Angular POC created by Abhishek Choubey. In this POC I started building Shopping website <br/>
This is 9th build push for the Shopping website, for building this portal I am using Angular. <br/>

<b>Highlights of 9th Push</b> <br/>

Code added for <br/>
--------------------- <br/>
collection component code. <br/>
success component <br/>
payment gateway. <br/>


<b>Highlights of 8th Push</b> <br/>
collection component<br/>

shop--->widgets-->filter--->color form component<br/>
shop--->widgets-->filter--->brand form component<br/>
shop--->widgets-->filter--->price<br/>

http://localhost:4200/home/left-sidebar/collection/men<br/>
http://localhost:4200/home/left-sidebar/collection/women<br/>


<br/>

<b>Highlights of 7th Push</b> <br/>
Code added in shop-->product-details<br/>
Code added in cart service code added.<br/>
Code added in shop-->widgets-->new-product<br/>
Code added in category.component.html<br/>

http://localhost:4200/home/product/details/1<br/>

Third party package = zoom in and zoom out <br/>

<br/>

<b>Highlights of 6th Push</b> <br/>

Code added in:-<br/>
-----------------------<br/>
cart component<br/>
wishlist component<br/>
compare component<br/>

http://localhost:4200/home/cart<br/>
http://localhost:4200/home/wishlist<br/>
http://localhost:4200/home/compare<br/>

shared-->header-->widget-->topbar<br/>
settings.component.html<br/>

<br/>

<b>Highlights of 5th Push</b> <br/>
Code added in products.service.ts file  <br/>                                                                                                                                

Create service order in services, <br/>
ng g s orders --skip-tests <br/>

Logical thing that are used by multiple component we write inside services. <br/>

Note <br/>
===== <br/>
Code added in orders service. <br/>

2 scenarios <br/>
=========== <br/>
1) save cart item in api <br/>
2) save cart item in cookies or local storage. <br/>

Note <br/>
===== <br/>
cart.service.ts for added product in cart. <br/>

whislist service <br/>

compare.service.ts file <br/>

shop-->product component. <br/>

 <br/>
<b>Highlights of 4th Push</b> <br/>
Inside shared--->type---> created interface {for strongly typed}<br/>
product.interface.ts<br/>
order.interface.ts<br/>
cart-item.interface.ts<br/>

Inside shared-->serivces-->products.service.ts <br/>

Inside Shop --> home <br/>
Code added in product-slider , product-tab and product component.<br/>

theme and code in collectionbanner, logo, and parallax <br/>

Added code in<br/>
src-->app-->shop-->home-->slider<br/>

Used jquery for implementing product-tab.component.html and ts file.<br/>


<b>Highlights of 3rd Push</b> <br/>

Configured app.module.ts <br/>

FormsModule, <br/>
SharedModule, <br/>

Go to main.comp.html <br/>

<app-header-one> <br/>

first export from shared.module.ts <br/>
exports:[HeaderOneComponent,HeaderTwoComponent,FooterOneComponent,FooterTwoComponent] <br/>
}) <br/>
export class SharedModule { } <br/>

====================================================================================== <br/>
  imports: [ <br/>
    CommonModule, <br/>
    RouterModule, <br/>
    TranslateModule <br/>
  ],<br/>
  exports:[HeaderOneComponent,HeaderTwoComponent,FooterOneComponent,FooterTwoComponent] <br/>
}) <br/>
export class SharedModule { } <br/>


app.component.ts file added code for translation <br/>

======================================================================================<br/>

Worked on page module <br/>

page-routing.module.ts file <br/>

======================================================================================<br/>

Worked on shopmodule <br/>

shop-routing-module.ts  <br/>

======================================================================================<br/>

Configured <br/>
app-routing.module.ts file <br/>

======================================================================================<br/>

<b>Direct Angular routing will not work on GitHub Pages </b> <br/>
http://localhost:4200/pages/about-us <br/>
http://localhost:4200/pages/404 <br/>
http://localhost:4200/pages/contact-us<br/>
http://localhost:4200/pages/login<br/>
http://localhost:4200/pages/faq<br/>

Note<br/>
====<br/>
Code done on all components of pages module.<br/>


Note:- Worked on Shared module <br/>
=====<br/>
shared--->footer-->widgets-->Category<br/>

=======================================================================================<br/>

shared--->Header-->widgets-->Category<br/>
left-menu<br/>
navbar-items<br/>

navbar <----------- package used smartmenu <br/>

Inside assets create folder js -----> file menu.js file <br/>
$(function() {<br/>
    $('#main-menu').smartmenus({<br/>
        subMenusSubOffsetX: 1,<br/>
        subMenusSubOffsetY: -8<br/>
    });<br/>

    $('#sub-menu').smartmenus({ <br/>
        subMenusSubOffsetX: 1,<br/>
        subMenusSubOffsetY: -8<br/>
    });<br/>
});<br/>


Load js file in header-one.component.ts file<br/>


Alignment will set later for menu<br/>

=======================================================================================<br/>

setting component done inside header-->widgets <br/>


=======================================================================================<br/>

<br/>

<b>Highlights of 2nd Push</b> <br/><br/>

From here we started developing Folder/Component Structure for our project <br/>
ng g m pages --routing<br/>
ng g m shop --routing<br/>
Inside Pages module <br/>
=================<br/>
ng g c about-us --skip-tests<br/>
ng g c contact-us --skip-tests<br/>
ng g c error-page  --skip-tests<br/>
ng g c faq --skip-tests<br/>
ng g c login  --skip-tests<br/>
ng g c registration  --skip-tests <br/>

Inside app<br/>
=========<br/>
ng g c main --skip-tests <br/>
ng g c landing-page --skip-tests<br/>
ng g m shared {no routing}<br/>
inside shared create folder validation<br/>

folder = type<br/>
cart-item.interface.ts<br/>
order.interface.ts<br/>
product.interface.ts<br/>

Inside shared = services folder<br/>
ng g s http --skip-tests <br/>
ng g s cart --skip-tests <br/>
ng g s whishlist --skip-tests<br/>
ng g s compare --skip-tests<br/>
ng g s products --skip-tests<br/>
==================================================================   <br/>                                        

Inside shared --> folder header, footer<br/>
ng g c footer-one  --skip-tests<br/>
ng g c footer-two  --skip-test<br/>
create folder --> widgets<br/>

Inside widgets create :-<br/>
ng g c category --skip-tests<br/>
ng g c copyrights --skip-tests<br/>
ng g c information --skip-tests<br/>
ng g c social --skip-tests<br/>
ng g c why-we-choose-us --skip-tests<br/>
Inside header create following compo:-<br/>
ng g c header-one  --skip-tests<br/>
ng g c header-two --skip-tests<br/>

Create folder widgets<br/>
inside widgets<br/>
ng g c left-menu --skip-tests<br/>
ng g c navbar --skip-tests<br/>
ng g c topbar --skip-tests<br/>
ng g c settings --skip-tests<br/>
=================================================================<br/>

Inside shop module<br/>
----------------------------<br/>
Create home comp<br/>
ng g c home --skip-tests<br/>

Inside home component  create <br/>
--------------------------------------------<br/>
ng g c collection-banner --skip-tests<br/>

ng g c logo --skip-tests<br/>
ng g c parallax-banner --skip-tests<br/>
ng g c slider --skip-tests<br/>
ng g c product-slider --skip-tests<br/>
ng g c product-tab --skip-tests<br/>
=======================================<br/>

Inside shop create product component<br/>
ng g c product --skip-tests<br/>
ng g c cart --skip-tests<br/>
ng g c wishlist  --skip-tests<br/>
ng g c compare  --skip-tests<br/>
ng g c checkout  --skip-tests<br/>
ng g c success  --skip-tests<br/>
ng g c product-details --skip-tests<br/>
ng g c collection --skip-tests<br/>

Inside shop create folder widgets<br/>

Inside widgets create:---------------<br/>
ng g c new-product --skip-tests<br/>
ng g c category --skip-tests<br/>

Create folder filter<br/>
Inside filter folder create---<br/>
ng g c color --skip-tests<br/>
ng g c brand --skip-tests<br/>
ng g c price --skip-tests<br/>

=================================<br/>

assets-->i18<br/>

kenwheeler.github.io/slick/ <br/>

<br/>

<b>Highlights of 1st Push</b> <br/><br/>

ng g new customerportal //for creating project <br/>
stylesheet format would you like to use? = SCSS <br/>
npm i bootstrap //for installing bootstrap <br/>
npm install font-awesome //for installing font awesome <br/>

<br/><br/>

routing = yes <br/>
scss = selected <br/>
setting ---> assets <br/>
themify icons search google ---->download icon font <br/>
theme.scss <br/>
Inside assets folder create file = app.scss <br/>
and put reference of theme.scss and css/themify-icons.css <br/>
npm install bootstrap <br/>
npm install ng-bootstrap  <br/>
npm install font-awesome  <br/>
npm install ngx-toastr  <br/>
npm install @angular/animations   <br/>
inside app.scss put import of toastr, bootstrap.scss,font-awesome.scss  <br/>
npm install ng5-slider  <br/>
npm install ngx-bar-ratting  <br/>
npm install ngx-infinite-scroll  <br/>
npm install slick-carousel <---- for image slider  <br/>
npm install smartmenus  <br/>
node-sass <--- package {depcreated in latest version}  <br/>
npm i node-sass  <br/>
ngx-translate  <br/>
npm install @ngx-translate/core  <br/>
npm install @ngx-translate/http-loader  <br/>
https://stackoverflow.com/questions/51020285/loading-httploaderfactory-translator-not-work-after-resume-network-connectivity  <br/>

<b>ng-bootstrap ; Installing from npm is simply doing </b> <br/>
npm install @ng-bootstrap/ng-bootstrap  <br/>
npm install @angular/localize --save  <br/>

Version Used ==> ng-bootstrap v15.1.0 <br/>
https://ng-bootstrap.github.io/#/components/progressbar/examples <br/>
npm i --save-dev @types/feather-icons  <--------------- This worked <br/>

const feather = require('feather-icons');  //<--------------------- This is required when we use above command inside ts file. <br/>
https://stackoverflow.com/questions/41292559/could-not-find-a-declaration-file-for-module-module-name-path-to-module-nam <br/>
https://feathericons.com/?query=git     <------------------ Official site which contains icons. <br/>
ng g c feather-icon --skip-tests  <br/>

ngx-toastr <br/>
========
<br/>
npm i ngx-toastr@12.0.0
<br/>
npm install @angular/animations@12.0.0 --save
<br/>

<b>Important Note </b> <br/>
tsconfig.json <br/>
{
<br/>
...
<br/>
  complilerOptions: { <br/>
        ...
        "skipLibCheck": true <br/>
    } <br/>
} 

<br/>
Inside styles.css -----------> @import '../node_modules/ngx-toastr/toastr-old.css';  //<=============Imp
<br/>

npm i sweetalert2@11.7.1
<br/>
https://sweetalert2.github.io/#examples
<br/>
https://sweetalert2.github.io/#usage
<br/> <br/>

<b> Version details of third party packages </b>
<br/>

"bootstrap": "^5.2.3",<br/>
"feather-icons": "^4.29.0",<br/>
"font-awesome": "^4.7.0",<br/>
"ngx-toastr": "^12.0.0",<br/>
"rxjs": "~7.5.0",<br/>
"sweetalert2": "^11.7.1",<br/>


Software Used <br/>
node --version = v14.20.0 <br/>
npm --version = 6.14.17 <br/>
ng version <br/>
Angular CLI: 14.0.0 <br/>

Check my work 👉👉👉👉 https://abhigit799.github.io/angular-shopping-site-part9/

<br/>
