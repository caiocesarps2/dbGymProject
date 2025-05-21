# dbGymProject

#Lista os usuários
curl http://localhost:5001/users

#Adiciona usuários
curl -X POST http://localhost:5001/api/auth/register \
  -H "Content-Type: application/json" \
  -d '{"username": "testeuser",
  "email": "teste@exemplo.com",
  "password": "senha123",
  "age": 25,
  "weight": 70,
  "height": 175,
  "goal": "Hipertrofia",
  "availability": "3 dias"}'
