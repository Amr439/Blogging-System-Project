In this project I created RESTful API for a blogging system that utilizes Sequelize as the ORM to connect to a MySQL database.
The schema includes complex associations, such as post categories and comments.
Users can create posts, categorize them, and leave comments. The API provides endpoints for managing users, posts, categories, and 
comments.Also , I implementing JWT (JSON Web Token) authentication to secure sensitive endpoints and protect user data

Relationships:

-> User-Post Relationship:
Each User can have multiple Posts.
Each Post belongs to one User.

-> Post-Category Relationship:
Each Post can belong to multiple Categories.
Each Category can be associated with multiple Posts.

-> Post-Comment Relationship:
Each Post can have multiple Comments.
Each Comment belongs to one Post.
Each Comment is associated with one User.

-> Comment-User Relationship:
Each Comment is associated with one User.
Each User can have multiple Comments.