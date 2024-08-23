Project walkthrough Guide

1. Docker: turn on Microservice
2. cd ./frontend : npm run dev
3. cd ./backend : go mod tidy
                  docker exec -it db psql -U postgres
                  \l
                  \dt
                  select * from users
4. To view service : docker ps -a
5. docker compose up
