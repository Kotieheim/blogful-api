# Run sql file from VScode to insert data into database

psql -U dunder_mifflin -d blogful -f ./seeds/seed.blogful_articles.sql

# Create DB

createdb -U "User Name" "DB name"
