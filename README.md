# Movies
API MS Movies
CREATE DATABASE Dbmovies;
INSERT INTO movies (title, genere, author, description, image, created_at, updated_at) 
VALUES 
('Inception', 'Sci-Fi', 'Christopher Nolan', 'A mind-bending thriller about dreams within dreams.', 'inception.jpg', NOW(), NOW()),
('The Godfather', 'Crime', 'Francis Ford Coppola', 'The story of a powerful Italian-American crime family.', 'godfather.jpg', NOW(), NOW()),
('The Dark Knight', 'Action', 'Christopher Nolan', 'Batman faces the Joker in a battle for Gotham.', 'dark_knight.jpg', NOW(), NOW()),
('Pulp Fiction', 'Drama', 'Quentin Tarantino', 'Interconnected stories of crime and redemption.', 'pulp_fiction.jpg', NOW(), NOW()),
('Forrest Gump', 'Drama', 'Robert Zemeckis', 'The life journey of a simple man with extraordinary experiences.', 'forrest_gump.jpg', NOW(), NOW());