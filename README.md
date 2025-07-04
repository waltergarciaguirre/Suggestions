# Suggestions
Suggestions is a Angular Application for providing experiances based off location, time, and transportation. 

travel-activity-planner/
├── .devcontainer/
│   └── devcontainer.json
├── .gitignore
├── README.md
├── src/
│   ├── TravelActivityPlanner.API/
│   │   ├── Controllers/
│   │   │   ├── ActivitiesController.cs
│   │   │   ├── PlacesController.cs
│   │   │   └── LocationController.cs
│   │   ├── Models/
│   │   │   ├── Activity.cs
│   │   │   ├── Place.cs
│   │   │   └── LocationRequest.cs
│   │   ├── Services/
│   │   │   ├── IActivityService.cs
│   │   │   ├── ActivityService.cs
│   │   │   ├── IPlacesService.cs
│   │   │   └── PlacesService.cs
│   │   ├── Data/
│   │   │   ├── TravelContext.cs
│   │   │   └── Migrations/
│   │   ├── appsettings.json
│   │   ├── appsettings.Development.json
│   │   ├── Program.cs
│   │   └── TravelActivityPlanner.API.csproj
│   └── travel-activity-planner-ui/
│       ├── src/
│       │   ├── app/
│       │   │   ├── components/
│       │   │   │   ├── activity-form/
│       │   │   │   ├── activity-list/
│       │   │   │   └── suggestions/
│       │   │   ├── services/
│       │   │   │   ├── activity.service.ts
│       │   │   │   ├── location.service.ts
│       │   │   │   └── places.service.ts
│       │   │   ├── models/
│       │   │   │   ├── activity.model.ts
│       │   │   │   └── place.model.ts
│       │   │   ├── app.component.ts
│       │   │   └── app.module.ts
│       │   ├── assets/
│       │   ├── environments/
│       │   └── styles.css
│       ├── angular.json
│       ├── package.json
│       └── tsconfig.json
└── docker-compose.yml