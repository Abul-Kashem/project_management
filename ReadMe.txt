rails g scaffold project title:string description:text
rails generate model task content:string project:references
rails generate controller tasks