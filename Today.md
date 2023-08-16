#### 1. ngTemplateOutlet, ngTemplateOutletContext
#### 2. ng-container vs ng-template vs ng-content
#### 3. providedIn: root, any, platform
#### 4. Bootstrap (layout, grid, css grid, utilities)


export const heroServiceProvider =
  { provide: HeroService,
    useFactory: heroServiceFactory,
    deps: [Logger, UserService]
  };
