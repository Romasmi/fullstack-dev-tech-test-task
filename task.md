# To do:

1. Create a Restful API according to the specification in the swagger.yaml;
   - Requirements:
      - Pure PHP;
      - PSR-12;
2. Create a database structure and put migrations in /database/migrations folder;
   - Example of migration is in /database/migration/1713358478_example.sql;
4. Create a web page to display the courses and categories;
   - Design layouts are in /design folder;
   - Requirements:
      - Any front-end framework can be used, but pure technologies are preferred;
   - Layout key features:
      - By default all courses should be displayed;
      - By click on the category, only courses from this category should be displayed;
      - On desktop layout, title and description are truncate with ellipsis;
   - Restrictions:
      - Each course should have only 1 category;
      - Max depth of categories tree is 4;