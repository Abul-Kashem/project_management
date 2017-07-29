rails g scaffold project title:string description:text
rails generate model task content:string project:references
rails generate controller tasks
rails generate migration add_completed_at_to_task completed_at:datetime