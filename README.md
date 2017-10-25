# Rendere2

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.5. In this project i have implemented @ViewChild using Directive.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

# Project Details:
  # @ViewChild:
    It can instantiate a directive within a component and in this way the component will be able to access the directive methods. 
    
   Step1: Create the directives and we have to refer the directives in parent component using @ViewChild.
   
   Note:
   
   # AfterViewInit
     This is a lifecycle hook that is called after a component view has been fully initialized. 
     
     
   # Syntax for Rendere
   
   createElement()  ----  createElement(name: string, namespace?: string|null): any 
   
   createText()     ----  createText(value: string): any
   
   appendChild()   -----  appendChild(parent: any, newChild: any): void
   
   insertBefore()  -----  insertBefore(parent: any, newChild: any, refChild: any): void 
   
   removeChild()   -----  removeChild(parent: any, oldChild: any): void 
   
   selectRootElement() -  selectRootElement(selectorOrNode: string|any): any 
   
   setAttribute()  ----   setAttribute(el: any, name: string, value: string, namespace?: string|null): void
   
   removeAttribute() --  removeAttribute(el: any, name: string, namespace?: string|null): void 
   
   setProperty()   ----  setProperty(el: any, name: string, value: any): void
   
   addClass()      ----  addClass(el: any, name: string): void 
   
   removeClass()   ----  removeClass(el: any, name: string): void 
   
   setStyle()      ----  setStyle(el: any, style: string, value: any, flags?: RendererStyleFlags2): void 
   
   removeStyle()   ----  removeStyle(el: any, style: string, flags?: RendererStyleFlags2): void 
   
   parentNode()   -----  parentNode(node: any): any 
   
   createComment() ----  createComment(value: string): any
   
   listen()        ----  listen(target: 'window'|'document'|'body'|any, eventName: string, callback: (event: any) => boolean | void): () => void 
