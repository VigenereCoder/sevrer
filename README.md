docker run --name vigenere -p 5432:5432 -e POSTGRES_PASSWORD=postpass -v init.sql:/docker-entrypoint-initdb.d/init.sql -d postgres
