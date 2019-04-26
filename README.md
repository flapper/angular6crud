# angular6crud
Angular 6 CRUD example  from https://www.devglan.com/angular/angular-6-example

Modified avoiding errors by version mismatch.

You can make this step by step like this.

`ng new angular6-example`  
`ng g service service/user`  
`ng g service service/auth`  
`app.routing.ts` is same as `app-routing.module.ts`  
 so don't erase or make another  
 
`app/auth.service.ts`  
 https://gist.github.com/flapper/693fd9f8f82e0989227bd5c8404b9f87  
 
`app/app.module.ts`  
https://gist.github.com/flapper/8c163547d9c1a11e230a213485c41b47#file-app-module-ts  

`app/model/user.model.ts`  
https://gist.github.com/flapper/b5b6ca2d51120e50211f20955f70f25b#file-user-model-ts  

`app.component.html 
`<router-outlet></router-outlet>` 만 남기고 모두 지우기  

`list-user.component.html`  
https://gist.github.com/flapper/4e628115213acb33497bcd8de8e13296  
