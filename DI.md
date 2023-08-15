# DI
#### Providing dependency (providers, NgModule, Injectable)
#### Injecting a dependency (constructor, inject)
#### Specifying a provider token: useClass, useExisting, useFactory, (useValue, InjectionToken)
##### Can't use interface as provider token
##### Can't inject using the interface as the parameter type

<br/><br/>

#### Injection context
#### Angular provides assertInInjectionContext helper function to assert that the current context is an injection context
#### Calling inject or calling assertInInjectionContext outside of an injection context will throw error NG0203

<br/><br/>

#### Types of injector hierarchies (ModuleInjector, ElementInjector)
#### ModuleInjector: @NgModule() or @Injectable()
#### ElementInjector: providers property on @Directive() or @Component(), empty by default

<br/><br/>

#### @Injectable() providedIn property is preferable to using the @NgModule() providers array because of optimization tools can perform tree-shaking

<br/><br/>

#### root ModuleInjector (configured by MyApp)
#### ModuleInjector (configured by PlatformModule)
#### NullInjector

<br/><br/>

#### 


