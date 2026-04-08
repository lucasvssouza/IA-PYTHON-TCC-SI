Criar tabela usuarios:
CREATE TABLE usuarios (
  id INT AUTO_INCREMENT PRIMARY KEY,
  nome VARCHAR(100) NOT NULL,
  email VARCHAR(150) NOT NULL UNIQUE,
  senha_hash VARCHAR(255) NOT NULL,
  data_inclusao TIMESTAMP DEFAULT CURRENT_TIMESTAMP()
);

# Chave para JWT
JWT_SECRET=iafjianfpemwtwpemwpetmwpetaksnmdsak122049820gkk

# Porta do servidor Fastify
PORT=8082

#Chave do Gemini
API_KEY=AIzaSyD-xpHSwAraFZncVmpj7VqklDUmGz-HFZU