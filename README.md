### Steps

-   Change const HOME (from dashboard to admin) in RouteServiceProvider.php
-   Create route group with middleware (name and prefix 'admin')
-   Create admin.dashboard route, move dashboard view into admin folder
-   Make Model with migration (-m) and seeder (-s)
-   Make Controller (resource -r) in Admin/Project, link to model=Project
