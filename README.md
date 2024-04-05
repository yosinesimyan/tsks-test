# tsks-test
test first repo of tasks app
this project is about manage tasks.
add, remove. update and get tasks

usage:
curl -X POST http://127.0.0.1:5000/tasks -H 'Content-Type: application/json'  -d '{"title":"buy","details":"chocolate"}'
curl -X PUT http://127.0.0.1:5000/tasks/3 -H 'Content-Type: application/json'  -d '{"title":"buy","details":"boots"}'
curl -X DELETE http://127.0.0.1:5000/tasks/3 



