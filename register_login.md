npx ts-node src/index.ts

# Student Registration
curl -X POST http://localhost:3000/api/auth/register \
-H "Content-Type: application/json" \
-d '{
  "email": "newuser@example.com",
  "password": "securepassword",
  "firstName": "Jane",
  "lastName": "Doe",
  "role": "STUDENT"
}'

# Student login
curl -X POST http://localhost:3000/api/auth/login \
-H "Content-Type: application/json" \
-d '{
  "email": "newuser@example.com",
  "password": "securepassword"
}'

# Adnin Registration
curl -X POST http://localhost:3000/api/auth/register \
-H "Content-Type: application/json" \
-d '{
  "email": "adminuser@example.com",
  "password": "securepassword",
  "firstName": "Admin",
  "lastName": "User",
  "role": "ADMIN"
}'

# Admin Login

curl -X POST http://localhost:3000/api/auth/login \
-H "Content-Type: application/json" \
-d '{
  "email": "adminuser@example.com",
  "password": "securepassword"
}'

# Register an Intsructor

curl -X POST http://localhost:3000/api/auth/register \
-H "Content-Type: application/json" \
-d '{
  "email": "instructor@example.com",
  "password": "securepassword",
  "firstName": "Instructor",
  "lastName": "User",
  "role": "INSTRUCTOR"
}'

# Instructor Login

curl -X POST http://localhost:3000/api/auth/login \
-H "Content-Type: application/json" \
-d '{
  "email": "instructor@example.com",
  "password": "securepassword" # eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTgsInJvbGUiOiJJTlNUUlVDVE9SIiwiaWF0IjoxNzQzNDY0OTQ5LCJleHAiOjE3NDM0Njg1NDl9.mzbf-l8YjhXET3C05WSe0XKOMMJxyE8JaMlFKnnEanY
}'

# login Tokens

eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTQsInJvbGUiOiJTVFVERU5UIiwiaWF0IjoxNzQzNDU5MDUzLCJleHAiOjE3NDM0NjI2NTN9.IpHlxY2VhiTpPuVaJbHjgBc8BIYvXR-Ev97-J1vbTBg

eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTYsInJvbGUiOiJTVFVERU5UIiwiaWF0IjoxNzQzNDYzNjUyLCJleHAiOjE3NDM0NjcyNTJ9.868OQ433da30TjJwCqe9RYlF9-QyTeI1wtp2NCyUOuY

admin: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTcsInJvbGUiOiJBRE1JTiIsImlhdCI6MTc0MzQ2Mzk3OSwiZXhwIjoxNzQzNDY3NTc5fQ.QhKViXDpWvp49J-c1292bBFlov-BF3zFMau6S5xALdk

eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTcsInJvbGUiOiJBRE1JTiIsImlhdCI6MTc0MzQ2NDA3NCwiZXhwIjoxNzQzNDY3Njc0fQ.hRB9xSwvW3EYtoGL9kvUND8hMxIqB6fLPe8dXd4rprg

admin registration token: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTgsInJvbGUiOiJJTlNUUlVDVE9SIiwiaWF0IjoxNzQzNDY0NjUzLCJleHAiOjE3NDM0NjgyNTN9.2Tcx3C03B2oqCG2vEYEXe1TvC25dkWLG84gaFGzg-sQ

eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTgsInJvbGUiOiJJTlNUUlVDVE9SIiwiaWF0IjoxNzQzNDY1MTcyLCJleHAiOjE3NDM0Njg3NzJ9.Qp_A-Ki116ju5MuKdgNpnfZLcYkxUzVmMLYUEZ4zg2k