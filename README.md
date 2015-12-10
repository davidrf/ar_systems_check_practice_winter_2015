Design a schema and create the necessary migrations and models to represent artists and the venues where they perform:

#### Artist

* Artist must have a name.
* Artist can optionally have a genre.
* Artists perform at many venues.

#### Venue

* A venue must have a name.
* A venue can optionally have a person capacity.
* A venue can have many artists performing at it.

### Tips

* You should feel free to add whatever additional migrations/models etc. you need to make these associations work.
* This challenge is focused solely on **migrations**, **models**, and the database **schema**. The relevant files that will be checked are:
  - All files in the `app/models` directory.
  - All files in the `db/migrate` directory.
  - The `db/schema.rb` file.
* Include database constraints and model validations where appropriate.
* Draw out the ER Diagram on paper so that you can understand what data you will need to save and the relationships that you will need to create.
* Test your models in `pry` by running `pry -r "./app.rb"`.
* You do not need to add any routes to the application to make the app functional.
